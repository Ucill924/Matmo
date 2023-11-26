
# Guide Intsallation Node Validator Neutron Quark Tesnet

<p style="font-size:14px" align="left">
<a href="https://twitter.com/Ucillny2" target="_blank">Follow my twitter</a>
</p>


## Requirements Hardware

For running a production grade public fullnode:
CPU: 8 cores, 16 threads (Intel Xeon Skylake or newer).
Memory: 32GB RAM.
For running the public fullnode for development or testing:
CPU: 2 cores.
Memory: 4GB RAM.

## Configuring validator

## Code 
```bash
code

matmo tar -xvf <path to data directory>
curl -o <path to genesis JSON> -sL <URL to genesis JSON>

validator init \
	 --datadir="<your data directory>" \
	 "<path to genesis JSON>"
	curl -o <path to data directory> -sL <URL to data director
\
\\
##open-validator


 --matmo=<goerli RPC url> \
        --matmo=<matmo-validator authenticated RPC url> \
        --network=beta-1
        --rpc.addr=127.0.0.6 \
        --rpc.port=9445 \
      
```
