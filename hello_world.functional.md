```haskell
-- Haskell
main :: IO()
main = putStrLn "Hello, World!"
```

```fsharp
-- F#
open System
[<EntryPoint>]
let main argv =
   printfn "Hello, World!"
   0
```

```elixir
-- Elixir
defmodule M do
   def main do
      IO.puts "Hello, World!"
   end
end
```

```erlang
-- Erlang
-module(hello_world).
-compile(export_all).
hello() ->
   io:format("Hello, World!").
```

```pascal
-- Pascal
program Hello;
begin
   writeln ('Hello, World!');
end.
```

```ocaml
-- OCaml
let () = 
   print_string "Hello, World!";
```

```clojure
-- Clojure
(ns hello-world.core)
(defn -main [& args]
  (println "Hello, World!"))
```

```elm
-- Elm
module HelloWorld exposing (..)
import Html exposing (text)
main = 
   text "Hello, World!"
```

```lisp
-- Common-Lisp
(defun hello ()
   (format t "Hello, World!"))
```
