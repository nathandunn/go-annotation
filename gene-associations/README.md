sjcarbon@moiraine:~/local/src/svn/geneontology.org/trunk/gene-associations$:) svn update
Updating '.':
At revision 45667.

Success will be these all returning empty:
```
zgrep -L "^\![[:space:]]\?gaf\-ver" *.gz
zgrep -c "^\![[:space:]]\?gaf[-_]ver" *.gz | grep 2
zgrep "^\![[:space:]]\?gaf_ver" *.gz
```