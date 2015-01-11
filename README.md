# pt-kill

This is a patched version of [pt-kill](http://www.percona.com/doc/percona-toolkit/2.2/pt-kill.html) from the
[Percona Toolkit](http://www.percona.com/software/percona-toolkit) that fixes issues with `--busy-time` and prepared
statements.

Patch taken from https://bugs.launchpad.net/percona-toolkit/+bug/1016272.

It also has a change that pipes the query ID to `--execute-command`, so you can actually do something useful with it.
