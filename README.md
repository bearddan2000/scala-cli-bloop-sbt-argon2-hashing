# scala-cli-bloop-sbt-argon2-hashing

## Description
Argon2 has a hard time with
bloop-sbt compiler so this is more
or less a copy of code found online.

After reading through the build script
it looks like a lib or at least some
code is pulled from github.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/outr/scalapass.git)
