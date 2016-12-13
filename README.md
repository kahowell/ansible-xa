What is this?
-------------
I wanted to play around with xamarin-android. I also like to use ansible to
automate things. Put those two together and ta-da.

I have a small patch in there that I noticed was necessary for whatever reason
to compile monogame projects. Not sure that it should be necessary though...
(I honestly don't understand xamarin well enough to judge). I just noticed if
I try to use the `xabuild` script with say v4.2, then I get missing references
to OpenTK...

This probably isn't useful for many... I mainly just wanted to push it out so
I don't lose it, but if it helps you, cool!

License
-------
MIT licensed.
