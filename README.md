# MONEU binaries for Linux

Prebuilt node, ready to run. No libraries to install.

## Download and run

    tar xzf moneu-0.2.2-linux-x86_64.tar.gz
    cd MONEU-linux
    ./moneu-test-noise
    ./moneud -daemon

The rest is in README.txt inside the archive.

## Check what you downloaded

    sha256sum -c SHA256SUMS

## Check who built it

    gpg --import moneu-binary-releases-key.asc
    gpg --verify moneu-0.2.2-linux-x86_64.tar.gz.asc moneu-0.2.2-linux-x86_64.tar.gz

It should say:

    Good signature from "natusor (MONEU binary releases signing)"

The key fingerprint is:

    9B3E AC79 B47A A748 AFA2  DE54 62ED 724E 57AF 49D9

Source code: https://github.com/natusor/MONEU
Website: https://moneu.cc
