## R CMD check results

0 errors | 0 warnings | 0 notes


There is one NOTE that is only found on Windows Server 2022, R-devel, 64 bit:
```
* checking for detritus in the temp directory ... NOTE
Found the following files/directories:
  'lastMiKTeXException'
```

As noted in [R-hub issue #503](https://github.com/r-hub/rhub/issues/503), this could be due to a bug/crash in MiKTeX and can likely be ignored.
