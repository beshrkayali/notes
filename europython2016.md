# What python can learn from Haskell packaging / Domen Kozar
### 2016-07-18 10:30

- Cabal (Haskell Package Management tool) has a couple of build-types: Simple, Make, Custom (run Haskell code)
- Python PEP 518
- Cabal has Flag support built-in with simple language for conditional validation
- Haskell code wouldn't compile because version changes between packages might change types and the usage of
  these packages might not be correct anymore. Cabal Hell.
- Elm forces semantic versioning to overcome this problem. If there's an API change that breaks usage, major version
  should get updated.
- Stackage: Maintained packages for Haskell. Crowdsourced requirements.txt and dependency tree. Community members pick a
  tree in repo and make sure that code compiles fine, tests pass and so on. Then provide LTS support for a package.
- Nix  nixpkgs Haskell
- More declarative Python packaging

More:
http://cryp.to/nixcon-2015-slides.pdf
