ElixirFM
========

[http://bitbucket.org/otakar-smrz/elixir-fm](http://bitbucket.org/otakar-smrz/elixir-fm)

[http://github.com/otakar-smrz/elixir-fm](http://github.com/otakar-smrz/elixir-fm)

[http://otakar-smrz.github.io/elixir-fm](http://otakar-smrz.github.io/elixir-fm)


New things
----------

- ElixirFM now uses [Jupyter](http://jupyter.org) to provide example-driven insights and documentation. Check out the [IHaskell](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/README.ipynb), [IPython](http://github.com/otakar-smrz/elixir-fm/tree/master/Python/ElixirFM/README.ipynb), and [IShell](http://github.com/otakar-smrz/elixir-fm/tree/master/README.ipynb) notebooks!

- The [Haskell](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM) library and executable pretty-print the output of the [resolve](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/Elixir/Resolve.hs), [inflect](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/Elixir/Inflect.hs), [derive](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/Elixir/Derive.hs), [lookup](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/Elixir/Lookup.hs), and and [merge](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/Elixir/Template.hs) modes in a column-oriented format for both clarity and convenient processing. You can `cut` or `grep` the information on the [command line](http://github.com/otakar-smrz/elixir-fm/tree/master/README.ipynb) as well as [unpretty](http://github.com/otakar-smrz/elixir-fm/tree/master/Python/ElixirFM/README.ipynb) the output into nested data structures using [Python](http://github.com/otakar-smrz/elixir-fm/tree/master/Python/ElixirFM/ElixirFM/__init__.py) or [Perl](http://github.com/otakar-smrz/elixir-fm/tree/master/Perl/ElixirFM/lib/ElixirFM.pm).

- There is support for calling the Haskell executable in its different modes from within [Python](http://github.com/otakar-smrz/elixir-fm/tree/master/Python/ElixirFM) as if it were a native function.

- The ElixirFM [lexicon](http://github.com/otakar-smrz/elixir-fm/tree/master/Haskell/ElixirFM/Elixir/Lexicon.hs) gets incrementally improved. Most notably, the lexicon now internally expands its verbal entries into masdars and active and passive participles. This is done via the derive mode and it increases the coverage of the resolve, lookup, and inflect modes. Check out our [web service](http://otakar-smrz.github.io/elixir-fm).


Join us
-------

Since [ElixirFM](http://github.com/otakar-smrz/elixir-fm) is now hosted on [GitHub](http://github.com/otakar-smrz) and [Bitbucket](http://bitbucket.org/otakar-smrz), it becomes yet easier to join the project and contribute to it. We do need new features, applications, interfaces, and documentation. Feel free to contact us or clone the project!
