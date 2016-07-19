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

# It's not magic: descriptors exposed / Facundo Batista
### 2016-07-16 12:00

- https://docs.google.com/presentation/d/1cSSwG_kpfg7DsvytUkhs_NPzcFZfOJ4Cj49LTKkKELM/edit#slide=id.p

# High Performance Networking / Yury Selvanov
### 2016-07-19 10:40

- Coroutines are a king of generators, but not an instance of it. They share a lot of code.
- AsyincIO is a toolbox for frameworks and protocols and not exactly a framework itself.
- There are pros and cons for asyincio being part of the standard library.
- Asyncio: standarized pluggable event loop / interfaces for protocols and transports / factories for servers and
  connections; streams. / futures and tasks: callbacks + coroutines, timeouts, cancellaitons , etc. / Subprocess,
queues, synchronisation primitives.
- Use loop.sock methods for easy porting / prototyping stuff.
- Use streams for implementing protocols with async/await / Use protocols and transports for Performance 
- loop.create_future() was added in 3.5.2


# The Joy of Simulation for Fun and Profit
### 2016-07-19 

- http://koaning.io










 
