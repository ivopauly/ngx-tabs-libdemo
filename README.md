## Angular Tabs - Demo Library

> **WARNING**: This is **not a production ready library**, but rather just an example
> to showcase how to release custom Angular libraries.

This repo is meant to demonstrate the creation of an Angular library, following the [Angular Package Format](https://docs.google.com/document/d/1CZC2rcpxffTDfRDs6p1cfbmKNLA6x5O-NtkJglDaBVs/preview).

## Contents

So what's in this repo?

* **[setup with ng-packagr (master)](https://github.com/juristr/ngx-tabs-libdemo) -** the `master` branch shows the _suggested approach_, namely to setup your library with [ng-packagr](https://github.com/dherges/ng-packagr).
* **[NX workspace setup (with-demoproj-setup)](https://github.com/juristr/ngx-tabs-libdemo/tree/with-demoproj-setup) -** Setup that shows how you can use [Nrwl/NX](https://nrwl.io/nx) to setup a nice workspace containing a library project and demo it straight away.
* **[Building libraries with Bazel (bazel)](https://github.com/juristr/ngx-tabs-libdemo/tree/bazel) -** This branch shows how to use Bazel to generate an Angular package.
* **[manual setup (manual-setup)](https://github.com/juristr/ngx-tabs-libdemo/tree/manual-setup) -** the `manual-setup` branch on the other hand, demonstrates how to assemble the different tooling in order to get a manual setup with simple npm scripts that are being executed one after the other. This allows for full flexibility and serves for educational purposes, to learn how things are done behind the scenes. _This is a slightly improved version of the talk given at NG-BE (see link below)._

## Useful links

[Angular Package Format v6.0](https://goo.gl/4wRtRG), design document at Google Docs

## Bugs, questions,...

Open an issue here on the repo
