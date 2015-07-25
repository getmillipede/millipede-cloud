millipede-cloud
===============

Scripts and utility to run millipede on your favorite cloud infrastructure

Run millipede on Scaleway
=========================

::

 # Install Scaleway CLI
 $> curl -L https://github.com/scaleway/scaleway-cli/releases/download/v1.1.0/scw-`uname -s`-`uname -m` > /usr/local/bin/scw
 chmod +x /usr/local/bin/scw

 # Login
 $> scw login --token=<your_token> --organization=<your_organization>

 # Run millipede on your C1 server
 $> ./provider/scaleway.sh
 [+] Creating your millipede server...
 [+] Server created: 77b531d8-b954-405f-988e-82e79486acf7
 [+] Booting...
 [+] Server is booted
 [+] Installing millipede...
 [+] Running millipede
 My millipede is magnificent
     ╚⊙ ⊙╝
   ╚═(███)═╝
  ╚═(███)═╝
 ╚═(███)═╝
  ╚═(███)═╝
   ╚═(███)═╝
    ╚═(███)═╝
     ╚═(███)═╝
     ╚═(███)═╝
    ╚═(███)═╝
   ╚═(███)═╝
  ╚═(███)═╝
 ╚═(███)═╝
  ╚═(███)═╝
   ╚═(███)═╝
    ╚═(███)═╝
     ╚═(███)═╝
     ╚═(███)═╝
    ╚═(███)═╝
   ╚═(███)═╝
  ╚═(███)═╝
 [+] Stopping the server
 [+] Server stopped
 [+] Deleting server
 [+] Server deleted

