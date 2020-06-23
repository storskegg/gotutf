# gotutf
This pen demonstrates how to identify, highlight, "entitize," and remove special characters as defined as ascii characters beyond decimal 127, as well as UTF characters.

A caveat here is that while the browser may support the display of UTF-32 characters, Javascript will not return the full UTF-32 character code--only the first two bytes.

I wrote and later refined this tool in response to updating content that had been copy/pasted from Word or some other tool that replaces basic punctuation with UTF characters, or inserted invisible UTF whitespace into a string for who knows why. I hope that someone else happens to find it useful, too.
