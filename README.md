# nmag
NMAG - Computationall Micromagnetics [Micromagnetic modelling tool based on finite elements]

# "Nmag Migration 2020"

Nmag has not been activily developed further since around 2012. However, it is still in use 
by several research groups; citations for the nmag paper are around 185 (Web of Science) 
and 300 (Google Scholar) at the end of 2019.

## What is the status of the software?

It is essentially usable: the deployment method chosen has proved surprisingly robust. 
Based on a tarball of all required libraries, Nmag can be compiled with a little bit of care and manual corrections, but doesn't work out of the box.

Nmag documentation is available at https://nmag-project.github.io/.

Software is available at https://nmag-project.github.io/download.html

  
## Help needed (2020)!

The original developers had to move on to other tasks. 

This is a call to the Nmag users: those with interest and/or skill to hepl with the above
tasks, please step forward and contact nmag.project@gmail.com to offer to help. 

## Status of migration and TODOs (started 2020)

- [X] The server nmag.soton.ac.uk needs to be decommissed. It would be good to take all data on there, 
  and make it available elsewhere. This includes the documentation, the content of the Wiki and binaries. 

- [ ] update tar-ball to compile automatically and make available (https://github.com/fangohr/nmag/issues/2)
  The compilation as described on the current webpages doesn't work automatically. 
  It would be good if this could be fixed and a fixed version made available.
  There are patches available (for example https://groups.google.com/forum/#!topic/nmag-users/XglwvaFdQs8), somebody 
  needs to integrate them, and ideally create a new tarball that extracts and compiles out of the box (at least on Linux, 
  ideally also on OS X).
  
- [X] move nmag webpage to nmag.github.io (https://github.com/fangohr/nmag/issues/1)

- [X] Update the new webpages to point to new URLs (https://github.com/fangohr/nmag/issues/3)
- [X] Save information from https://nmag.soton.ac.uk/community/wiki/nmag (https://github.com/fangohr/nmag/issues/4)
- [X] Shut down old server (https://github.com/fangohr/nmag/issues/5)
- [X] The documentation from https://nmag.soton.ac.uk/nmag/0.2/manual/singlehtml/manual.html is available at http://nmag.readthedocs.io/en/latest/. The source of the documentation is available at https://github.com/fangohr/nmag-doc. Thanks @rpep for this.

### Optional activities

- [X] Compile Nmag in container (https://github.com/fangohr/nmag/issues/6)

--------------

# Related repositories
- https://github.com/fangohr/nmag - meta repository (this one)
- https://github.com/fangohr/nmag-containers - use nmag from singularity container image
- https://github.com/fangohr/nmag-www - source of nmag webpages
- https://github.com/fangohr/nmag.github.io - hosting of documentation
- https://github.com/fangohr/nmag-doc - source for documentation
- https://github.com/fangohr/nmag-src - nmag and nsim source
- https://github.com/fangohr/nmag-dist - building tarball distribution


# Related information

- Virtual micromagnetics provides a compiled version of Nmag in a virtual machine (http://virtualmicromagnetics.org)

- Recent paper reviewing Nmag; comments on installation: https://arxiv.org/abs/1601.07392, section 4.12
