A working template for a Purs-nix Purescript Halogen app using Vite for bundling and serving.  

To get this up and running using nix, I like to load it in direnv but you could use 

```
git clone https://github.com/harryprayiv/purs-nix-halogen-template.git
cd purs-nix-halogen-template/
nix develop
purs-nix compile
vite --open
```
