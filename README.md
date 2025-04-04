# For Alpine Only.
- As you know, "lrzsz" removed from alpine package manager mirror.
- Please feel free to use:

## Install Commands For "Alpine"
```bash
wget -qO- https://github.com/ccieliu/lrzsz-alpine-bin/releases/download/0.12.20/lrzsz-0.12.20-alpine-bin.tgz | tar -xz
chmod +x lr* ls* && cp lr* ls* /usr/local/bin/
```



```text
lrzsz is a X/Y/ZModem package built from the public-domain version of
Chuck Forsberg´s rzsz package. This package contains NO code from later
releases of rzsz which would preclude it from being released under the
GPL.
It has been heavily modified by me and others.

Please note that credit should be given to Chuck Forsberg (rzsz) and Stephen
Satchell/Satchell Evaluations (crc routines) for this package. Any later
modifications were minor and merely introduced to increase performance,
reliability or compatability.

There is a mailing list for lrzsz: <uwe-lrzsz@bulkmail.ohse.de>. 
To subscribe send a mail to <uwe-lrzsz-subscribe@bulkmail.ohse.de>.

I prefer to get bug reports sent using the `lrzszbug' shell script which
you can find in the `src' subdirectory (this script is not installed together
with the programs because i don't expect many bug reports). Nethertheless
you can still send bug reports to <bugs@bulkmail.ohse.de> as normal
electronic mails. Bugs received at this address may be forwarded to the
mailing list.

Please read:
- INSTALL for installation instructions
- NEWS for a list of major changes between the releases
- ChangeLog for the list of minor changes.
- AUTHORS and THANKS to see whom to thank for this package.
- README.cvs for informations about CVS access to the lrzsz sources.
- README.tests for information about how to do a self test
- README.systems for a list of systems lrzsz has been compiled
  and passed a simple self test under.

In case you want to report a successful build:
	make success
or
	make fastcheck && \
	sh systype | mail uwe-generic-counter@ohse.de
"sh systype" alone shows what data this script sends.

Uwe Ohse
```
