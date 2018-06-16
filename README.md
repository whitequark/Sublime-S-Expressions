S Expressions for Sublime Text 3
--------------------------------

This package contains a Sublime Text 3 syntax definition for S-Expressions.

It features:
  * Atoms and parens `(one (two three))`
  * Integer and floating point numbers `123`, `12.34`;
  * Strings `"i'm quoted in new york times"`;
  * Line comments `; hello`;
  * Expression comments `(one #;(hide me) two)`;
  * Block comments with nesting `#| one #| two |# three |#`.

This happens to be the syntactic features recognized by [sexplib][], e.g. as used
in [Dune][] configuration files.

[sexplib]: https://github.com/janestreet/sexplib
[dune]: https://github.com/ocaml/dune

License
-------

[0-clause BSD](LICENSE-0BSD.txt)
