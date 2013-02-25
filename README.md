munin-wcc
=========

Creates Munin graphs from the stats [wcc](https://github.com/cmur2/wcc) collects in it's *stats.yml*
usually placed at */var/tmp/wcc/stats.yml* (or another location specified via env.wcc_stats_file).

Install
-------

Clone this repository or download the wcc_ file and create a
symlink as *root* in /etc/munin/plugins by using e.g.:

	cd /etc/munin/plugins; ln -s /path/to/wcc_ wcc_<mode>

where <mode> is one of runs|update|changes.

**Don't forget to restart your munin-node deamon.**
