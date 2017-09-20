### インストール
```
$ brew install opam
$ brew install ocaml
$ opam init
$ echo 'alias ocaml="rlwrap ocaml"' >> ~/.zshrc
$ echo 'let printer ppf = Format.fprintf ppf "\"%s\"";;' >> .ocamlinit
$ echo '#install_printer printer;;' >> .ocamlinit
```

```
$ ocaml
    OCaml version 4.05.0

# 1 + 2;;
- : int = 3
# "こんにちは";;
- : string = "こんにちは"
#
```


