
<p align="center">
  <p align="center">
    <img src="https://user-images.githubusercontent.com/5221349/72841405-93c2ce80-3c96-11ea-844b-3e1ff782b1ae.png" height="100" alt="Blockcore" />
  </p>
  <h3 align="center">
    About Blockcore RocksDB Native
  </h3>
  <p align="center">
    Native APIs for RocksDB by Facebook, used by the Blockcore RocksDB NuGet package.
  </p>
  <p align="center">
      <a href="https://github.com/block-core/blockcore-rocksdb-native/actions"><img src="https://github.com/block-core/blockcore-rocksdb-native/workflows/Build/badge.svg" /></a>
      <a href="https://github.com/block-core/blockcore-rocksdb-native/actions"><img src="https://github.com/block-core/blockcore-rocksdb-native/workflows/Release/badge.svg" /></a>
    <a href="https://www.nuget.org/packages/rocksdb/"><img src="https://img.shields.io/nuget/v/blockcore-rocksdb.svg?maxAge=0&colorB=brightgreen" /></a>
  </p>
</p>

Introduction
----------------------------

This repository contains code to download the official source code from RocksDB and build native libraries for Windows, Mac and Linux.

Libaries are available under releases in this repository.

The libraries is consumed by the Blockcore RocksDB NuGet package, available at:

https://github.com/block-core/blockcore-rocksdb

Go there to get the package you want, if you want to use RocksDB in your .NET projects.

### Background

This library is based upon a fork of the original work by [warrenfalk](https://github.com/warrenfalk) and [theolivenbaum](https://github.com/theolivenbaum)

Due to the major modifications to the setup, including adding support for GitHub Workflows and Releases, this repository is based upon a source-copy and not a linked git-fork.

https://github.com/warrenfalk/rocksdb-sharp

https://github.com/curiosity-ai/rocksdb-sharp

### License

[BSD 2-Clause License](LICENSE)