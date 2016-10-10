Welp. This is awkward.-150
You just received this PDF created by Karoly Ereky, but he died in 1952. What's up with that?
https://s3.amazonaws.com/hsf2016/for-your-eyes-only.pdf

Oh my, this PDF executes JAVASCRIPT when you open it!

Opening in notepad++, we can find the js code.

<< /#54#79#70#65 /#41#63#74#69#6f#6e
/#53 /#4a#61#76#61#53#63#72#69#70#74
/#4a#53 (\141\160\160\056\141\154\145\162\164\050\042\106\114\101\107\040\100\157\125\170\165\116\127\070\147\061\172\170\042\054\063\051\073) >>

The first line is hex, which is TypeActionSJavaScriptJS

The second line is octal, which is app.alert("FLAG @oUxuNW8g1zx",3);

@oUxuNW8g1zx
