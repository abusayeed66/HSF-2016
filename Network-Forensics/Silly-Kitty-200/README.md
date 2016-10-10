Silly kitty, onions are for...hackers?-200
My cat was surfing the dark web again. If you're anything like me, you'd think his lack of thumbs would prevent that. Turns out he's got an affinity for holding the mouse.
https://s3.amazonaws.com/hsf2016/kitty.pcapng

Extracting HTML objects, we find a pastebin page.


Suspicious sites:
pastebin.com/DQ8yiYcQ
vrpexywsisp5izxx.onion.to

The pastebin doesn't have anything too interesting besides a buncha "urls" that don't actually work.

The onion link does work- and its clearly a site made for the competition.

Looking at robots.txt, it disables you from accessing /images/. There isn't a whole lot that could be exploited in this website, so I was poking around the source.

menu: [
			{title: 'all', category: ''},
			{title: 'cats', category: 'cat'},
			{title: 'mild dank', category: 'mild'},
			{title: 'medium dank', category: 'medium'},
			{title: 'pure dank', category: 'pure'},
			{title: 'top5', category: 'top5'},
			{title: 'harambe', category: 'gorilla'},
			{title: 'l337hax', category: 'hax'},
			{title: 'lorem ipsum', category: 'lorem'},
			//{title: 'admin', category: '/admin.html'},
		]

Aha! https://vrpexywsisp5izxx.onion.to/admin.html

"key: there-are-no-dank-memes-like-neal-memes"

Answer: there-are-no-dank-memes-like-neal-memes
