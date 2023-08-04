Steps to reproduce:
1. Set up a debian-based build environment
1. Check out and build the upstream dcgm-exporter binary from https://github.com/NVIDIA/dcgm-exporter
1. Copy the build/* files into the dcgm-exporter repository checkout
1. Install nfpm
1. cd into the dcgm-exporter repository checkout
1. run `nfpm package -p deb`
