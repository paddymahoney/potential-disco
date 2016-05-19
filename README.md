# potential-disco
Trying to emulate the NES again in Common Lisp  

TODO: Other mapppers besides NROM  
TODO: Fix laggy input  
TODO: Write more idiomatic Lisp
#### Examples
![Super Mario Bros](https://i.gyazo.com/82acf346cc33b2f2a57ac7bacb09fdc3.gif)
![Galaga](https://i.gyazo.com/d9af4b6f32a1b6790be46627c2035306.gif)
![Donkey Kong](https://i.gyazo.com/edfc1dc4245ce0bfbbf99af8e84870e0.gif)
![Volley Ball](https://i.gyazo.com/ef21cd65df7267662637c735aa406bde.gif)
![NesTest](https://i.gyazo.com/f6f0767f3806388b99fb343190406b71.png)  
#### Usage
In your favorite common lisp repl (I have't tested outside of
sbcl), just run
```
(asdf:load-system :console)
(nes:setup-and-emulate path-to-rom)
```
Where path to rom is a string  
The controls map to..
Start: Tab  
Select: Grave  
Left, Down, Right, Up: W, A, S, D  
A, B: Left Arrow, Down Arrow  
I'm sorry, they aren't re-mappable yet. =(
