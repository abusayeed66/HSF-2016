How To Get Away With Murder-350
What time did the file start downloading to the machine?
https://s3.amazonaws.com/hsf2016/History
Your answer should follow this format: XXXX-XX-XX XX:XX:XX XXX

We are given a sqli database. Download a DB Browser for SQL to open it.

We're looking for the start of a download time which is 13115115452298564.

Looking online, we need to convert this datetime to unixepoch.

http://forensicswiki.org/wiki/Google_Chrome

>>> (13115115452298564/1000000)-11644473600
1470641852L

Which in calendar format is Mon, 08 Aug 2016 07:37:32 GMT

Answer: 2016-08-08 07:37:32 GMT
(or at one point the unix timestamp was accepted so 1470641852)
