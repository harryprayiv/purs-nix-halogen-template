An attempt to get Halogen template working with purs-nix tooling.   Currently stuck on the javascript aspect and how I bundle the app to work properly.  If I can't get this simple hello world working, I might quit this project for the twentieth time and go back to focusing on Haskell.


Currently, after I bundle the app, I get this message when I go to run it.
```
purs-nix run                                                                       nix-shell-env
file:///~/simpleDraft/output/Effect.Aff/foreign.js:530
                throw util.fromLeft(step);
                ^

ReferenceError: window is not defined
    at windowImpl (file:///~/simpleDraft/output/Web.HTML/foreign.js:2:3)
    at file:///~/simpleDraft/output/Effect/foreign.js:10:16
    at file:///~/simpleDraft/output/Effect/foreign.js:10:16
    at __do (file:///~/simpleDraft/output/Halogen.Aff.Util/index.js:45:119)
    at runAsync (file:///~/simpleDraft/output/Effect.Aff/foreign.js:96:20)
    at run (file:///~/simpleDraft/output/Effect.Aff/foreign.js:331:22)
    at file:///~/simpleDraft/output/Effect.Aff/foreign.js:637:15
    at drain (file:///~/simpleDraft/output/Effect.Aff/foreign.js:118:9)
    at Object.enqueue (file:///~/simpleDraft/output/Effect.Aff/foreign.js:139:11)
    at Object.run (file:///~/simpleDraft/output/Effect.Aff/foreign.js:636:23)
```