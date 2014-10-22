# Snippets
Snippets are pieces of code that helps to speed up your coding.

## How to install it
You can write your own snippets on Tools->Manage snippets, but you may want to add them all now. You can search your gedit folder (usually `usr/share/gedit/plugins/snippets`) and copy the XML files there. 

## How to write new snippets
Snippets consist of text and places. Also places with default text.
This is not a good explanation, but an example wil help.

For example you want to make a snippet to help you to make `if-else` statements. Let's see how it will be:
	
	if $1:
		$2
	else $3:
		$0

If you use this snippet, you only have to write on these places ($1 $2 $3..) and it finishes on $0.

You can also set default values. Let's se a `for` loop.

	for ${1:i} in ${2:xrange}(${3:count}):
		$0

If you use it and you don't type anything, then your code will look like this:
	
	for i in xrange(count):
		



# Contributing
Feel free to push new snippets or whatever you want.
