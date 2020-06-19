# Strings

## Capitalization

More fun with strings.  Take this one for example:

> "kEvIn mAlOnE"

I find it disrepectful to list his name like this.  We're going to look at how to fix this.

**Demonstration:**

Manipulate Kevin's name to show it in title form, all uppercase and all lowercase.

> name = "kEvIn mAlOnE"
> 
> name.title()
> 
> name.upper()
> 
> name.lower()

## Index

Strings can be broken down by letters.  Each letter is assigned an index within the string.  Given the example above, the indexes are as follows (Indexes start at 0 in programming):

0=k
1=E
2=v
3=I
etc.

Thankfully we don't have to memorize where everything is.  We can see what letter is at a specific index by calling it.

> print(name[4])

Any guesses on what this will return?

We can even make some new words out of our first string.

> print((name[3] + ' ' + name[7] + name[6] + ' ' + name[3] + name[4] + ' ' + name[8] + name[9] + name[2] + name[1]).title())

**Assignment:**

Can you create a new sentence using the letters from the string "The worst thing about prison was the Dementors."?
