I submitted this on 10/11 and received an email from Kurt Hornik
saying that it wouldn't install. I don't get this error on my 
computers, but I think I fixed it by editing the makevars.win file.


## Test environments
* local Windows install, R 3.3.1
* UNIX on a cluster, R 3.1.2
* win-builder

## R CMD check results
There were no ERRORs or WARNINGs or NOTEs on Windows using R 3.3.1.

I get two notes on UNIX that don't seem like real problems (NEWS.md and installed package size).

I fixed the two simple notes that came up on win-builder (title case and remove an import).

## Downstream dependencies

None, this is the first release.