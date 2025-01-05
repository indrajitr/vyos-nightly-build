[![VyOS nightly build](https://github.com/indrajitr/vyos-nightly-build/actions/workflows/nightly-build.yml/badge.svg)](https://github.com/indrajitr/vyos-nightly-build/actions/workflows/nightly-build.yml)

# vyos-nightly-build
Scheduled ISO nightly builds for current branch

An official download page https://vyos.net/get/nightly-builds/

## How to check an image signature
```
wget https://raw.githubusercontent.com/indrajitr/vyos-nightly-build/main/minisign.pub
wget https://github.com/indrajitr/vyos-nightly-build/releases/download/1.5-rolling-202501050641/vyos-1.5-rolling-202501050641-amd64.iso
wget https://github.com/indrajitr/vyos-nightly-build/releases/download/1.5-rolling-202501050641/vyos-1.5-rolling-202501050641-amd64.iso.minisig
minisign -Vm vyos-1.5-rolling-202501050641-amd64.iso
```
