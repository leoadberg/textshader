# [textshader.com](https://textshader.com)

I'm a fan of [Shadertoy](https://shadertoy.com) and wanted to create something similar but text-based to give it a different, retro vibe.

I whipped this up in a weekend and am not looking to expand it too heavily, but might add features when I feel like it. Please don't make any comments on code quality :), this is not ever intended to be production code and I'm by no means a front-end expert. The original intention was to just work on it myself but if you want to send me a PR I'd consider merging it!

Goals I started out with:
 - Statically hosted (no backend to maintain)
 - Single portable file
 - No / minimal dependencies
   - I pulled in the amazing [Ace editor](https://ace.c9.io) because creating my own is a monumental effort and not worth it
   - I use [Pastebin](https://pastebin.com) to store shared shaders (click the 🔗 button!) because without a backend I have to use something else to persist data
     -  Also a cors proxy to access it client-side

TODO (when I get around to it, maybe never):
 - More inputs (keyboard, mouse clicks, microphone, webcam)
 - Access to the previous buffer
 - More customization
   - User defined charsets and css themes
 - Remember stuff on refresh
 - More examples
 - Ability to render gif of the output
 - Embeddable version
