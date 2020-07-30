gg was made for log analysis of supportconfig/hb report messages logs.
It does highlighting of warnings, errors, and other important messages. This makes them easier to spot and reduces the time needed when analysing logs.
It has aggressive filtering which can be enabled with -i (disabled by default) to remove the (typically) unneeded logs.

**Install:**
```
zypper addrepo http://smt.suse.cloud/collective/collective.repo
zypper in gg-highlight
```
**Usage:**
```
gg [-i] [file]
```
