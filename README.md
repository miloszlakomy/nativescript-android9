# nativescript-android9

This repository includes the NativeScript CLI along with the Android SDK with the following toolchain versions:

* NodeJS 10
* Java 8

## NativeScript

Toolchain versions:

* NativeScript 5.3.4
* Android SDK tools for API Level 28 (build tools 28.0.3)

## Running

`$ git clone https://github.com/qwrtln/nativescript-android9.git && cd nativescript-android9`

`$ docker build -t nativescript .` <-- this might take a while

`$ docker run -i -t nativescript /bin/bash`


Optionally see if it's working:

`$ tns doctor`

...and run a "Hello, World" app:

`$ tns create my-hello-world-ng --ng`

Follow the instructions afterwards.

