Stratum Relay
====================

See the document stratum_relay.pdf to understand how it works.

The rest of documentation is in the code :)

It is designed for python3

Usage
====================

    strelay.py [-h] [-s POOL] [-t PORT] [-u USERNAME] [-a PASSWORD]
               [-l LISTEN] [-p LISTEN_PORT] [-c CONTROL] [-x CONTROL_PORT]
               [-o LOG] [-q] [-v VERBOSE]

    optional arguments:
      -h, --help       show this help message and exit
      -s POOL          Hostname of stratum mining pool
      -t PORT          Port of stratum mining pool
      -u USERNAME      Username for stratum mining pool
      -a PASSWORD      Password for stratum mining pool
      -l LISTEN        IP to listen for incomming connections (miners)
      -p LISTEN_PORT   Port to listen on for incoming connections
      -c CONTROL       IP to listen for incomming control remote management
      -x CONTROL_PORT  Control port to listen for orders
      -o LOG           File to store logs
      -q               Enable quite mode, no stdout output
      -v VERBOSE       Verbose level from 0 to 4

Contact
-------

Created and currently maintained by p4u p4u(at)dabax.net

Donation
--------

BTC: 1BaE7aavLF17jj618QKYFc5x6NGxk7uBkC

Thanks ;)

