# com.dz4k.FruitCredits

This is a Vala+GTK application, which is pretty easy to package as a Flatpak.
Unfortunately, it depends on a Haskell program ([hledger]).

The dependency manifest in <hledger-dep.json> describes how to compile hledger and all its dependencies from source.
It is generated by <scripts/build-hledger-dep-manifest.sh>,
which uses the program [cabal-flatpak].

[hledger]: https://hledger.org
[cabal-flatpak]: https://hackage.haskell.org/package/cabal-flatpak
