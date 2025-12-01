# Advent of Code 2025

I like to use [Advent of Code](https://adventofcode.com) to tinker and learn new things.

This year I'm playing with [Haxall](https://haxall.io)

Follow the setup instructions to start a Haxall server. I named mine advent-of-code and set it up to run on port 1225 (Because Christmas is 12/25)

Create an `io` directory under the new project (in my case, `~/haxall-4.0.3/bin/advent-of-code/io`) and copy problem input into that directory as `in.txt`

I haven't set up a script to run anything yet, so heres some hacks to run it:
Put advent.trio in the io directory as well

Enable math library (use the console): `if(libs().find(rec => rec->name == "hx.math").isNull) libAdd("hx.math")`

To run e.g. day1a: ```ioReadTrio(`io/advent.trio`).find(rec => rec->name == "day1a")->src.eval.call```
