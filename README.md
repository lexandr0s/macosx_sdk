# Readme

This repository is for the MacOSX10.11.sdk.tar.gz, mostly used for the bitcoin OSX building.

### Usage

pushd ./gitian-builder
mkdir -p inputs
wget -P inputs https://bitcoincore.org/cfields/osslsigncode-Backports-to-1.7.1.patch
wget -P inputs http://downloads.sourceforge.net/project/osslsigncode/osslsigncode/osslsigncode-1.7.1.tar.gz
popd
