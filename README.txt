This README did not come with the official pcc.  It is to explain the paploo
git respository.

I have an interest in emulating a processor (probably MIPS) in a software
environment, but want to utilize a C compiler to generate code.  This repo
allows me to hack on the code on multiple computers.

As a note, if you want to compile to big-endian mips, you would use the following:
  $ ./configure --prefix=/usr/local/pcc-installs/smips --target=mipsbe-linux
(mips-linux can be used if you want little endian)
