##Submission of revised version: v 0.1.1 - March 7, 2025

* Updates to URLs, author list, and documentation locations.
* Added helper function for which.max to mimic behavior of na.rm=TRUE so
  terra::app would work in vignettes with rasters containing NA values.

* Results for Windows (R-devel) from rhub::rhub_check() 
 + ── R CMD check ─────────────────────────────────────────────────────────────────
 + using log directory 'D:/a/msdrought/msdrought/check/msdrought.Rcheck'
 + using R Under development (unstable) (2025-03-06 r87893 ucrt)
 + using platform: x86_64-w64-mingw32
 + R was compiled by
 +  gcc.exe (GCC) 13.3.0
 +    GNU Fortran (GCC) 13.3.0
 + running under: Windows Server 2022 x64 (build 20348)
 + using session charset: UTF-8
 + using options '--no-manual --as-cran'
 + checking for file 'msdrought/DESCRIPTION' ... OK
 + this is package 'msdrought' version '0.1.1'
 + ...
 + checking installed files from 'inst/doc' ... OK
 + checking files in 'vignettes' ... OK
 + checking examples ... OK
 + checking for unstated dependencies in vignettes ... OK
 + checking package vignettes ... OK
 + checking re-building of vignette outputs ... [21s] OK
 + checking for non-standard things in the check directory ... OK
 + checking for detritus in the temp directory ... OK
 + DONE
 + Status: OK 

* Results for MacOS-arm64 (R-devel) from rhub::rhub_check() 
 + ── R CMD check ─────────────────────────────────────────────────────────────────
 + using log directory ‘/Users/runner/work/msdrought/msdrought/check/msdrought.Rcheck’
 + using R Under development (unstable) (2025-03-06 r87893)
 + using platform: aarch64-apple-darwin20
 + R was compiled by
 +    Apple clang version 14.0.0 (clang-1400.0.29.202)
 +    GNU Fortran (GCC) 14.2.0
 + running under: macOS Sonoma 14.7.2
 + using session charset: UTF-8
 + using options ‘--no-manual --as-cran’
 + checking for file ‘msdrought/DESCRIPTION’ ... OK
 + this is package ‘msdrought’ version ‘0.1.1’
 + ...
 + checking installed files from ‘inst/doc’ ... OK
 + checking files in ‘vignettes’ ... OK
 + checking examples ... OK
 + checking for unstated dependencies in vignettes ... OK
 + checking package vignettes ... OK
 + checking re-building of vignette outputs ... [11s/12s] OK
 + checking for non-standard things in the check directory ... OK
 + checking for detritus in the temp directory ... OK
 + DONE
 + Status: OK

