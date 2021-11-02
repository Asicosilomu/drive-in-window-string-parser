# drive-in-window-string-parser
[Drive-in Window](https://esolangs.org/wiki/Drive-In_Window) is an esoteric programming language created by User:JWinslow23 in 2013. The layout is similar to what someone would order at a restaurant.

I'm pretty sure this won't really help anyone, but I created this to make outputting strings easier. You simply input your string, and you get the code back. Pretty cool, huh? Here's how the generated code works:

For every character in the string...

Person (person) needs (charcode) dollars more for his order! - Adds the ASCII decimal charcode of the character to the specified person's value.

Person (person) will pay for his order! - Output person's value as an ASCII character.

Person (person) needs (charcode) dollars less for his order! - Subtracts the ASCII decimal charcode of the character from the specified person's value. (making it zero again)

And do the same thing for the rest of the characters.
  
You can check out Drive-in Window over at <https://tio.run/#drive-in-window>
