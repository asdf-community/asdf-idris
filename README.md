# asdf-idris

[Idris](http://idris-lang.org) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager


## Install

```shell
asdf plugin-add idris https://github.com/vic/asdf-idris.git
```

## Requirements


#### OSX

For OSX this plugin has no aditional requirements as it will download and install the 
[pre-packaged binaries](http://www.idris-lang.org/pkgs/) as built by the Idris team.

One important difference with downloading and installing the pkg by hand is that using
`asdf` allows you to have many versions of Idris installed alongside.

If you are on OSX and want to install from `cabal` be sure to set
`ASDF_IDRIS_INSTALL=cabal` in your shell environment.

#### Linux, Windows and Installing-from-source

When installing on other platforms (Linux, Windows), or when installing a specific source revision,
you will need to have `cabal install` and `cabal sandbox` working on your system. 

The easiest way to get them is by installing the [Haskell Platform](https://www.haskell.org/platform/).
Follow the [Installation Instructions](https://github.com/idris-lang/Idris-dev/wiki/Installation-Instructions)
for installing any aditional build-time dependency for your platform.

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Idris.

