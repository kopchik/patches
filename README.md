README
======

Here are some patches that I believe are useful.


qemu_ifname.patch
-----------------

Adds support for named tap interfaces.
Details:
http://lists.gnu.org/archive/html/qemu-devel/2013-03/msg03859.html

openntpd_adj_min_offset.patch
-----------------------------

Adds switch -o <min_adj> to openntpd that changes minimum offset
that will be immidiately compensated on startup (implies -s).
