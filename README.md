Zen.Fortune
===========

converted http://zenhabits.net/simple-living-manifesto-72-ideas-to-simplify-your-life/ to use in "fortune"

How To Use
----------

1. Add `"zen"` and `"zen.dat"` to your fortune directory.
2. Use `"$ fortune -files"` to locate your directory
3. Use this command to list your random "72 ideas to simplify your life" `$ fortune zen | cowsay | lolcat`


Important
---------

If you add a new quote on "zen.dat", always run this command:

    $ strfile -c % zen zen.dat
	

