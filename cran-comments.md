## Test environments
* local R installation, R 4.0.4
* win-builder (devel)
* R-hub windows-x86_64-devel (r-devel)
* R-hub ubuntu-gcc-release (r-release)
* R-hub fedora-clang-devel (r-devel)

## R CMD check results

0 errors | 0 warnings | 1 notes

On windows-x86_64-devel (r-devel), ubuntu-gcc-release (r-release), fedora-clang-devel (r-devel)
  
   Possibly mis-spelled words in DESCRIPTION:
   LSM (2:48, 22:45, 22:212, 22:801, 22:1123)
   Longstaff (22:1189)
  
 * This is an acronym and a name, and they are spelt correctly

  Found the following (possibly) invalid DOIs:
      From: DESCRIPTION
    DOI: 10.1093/rfs/14.1.113

 * This DOI is correct

* New submission

## Downstream Dependencies

* 'NFCP' is a downstream dependency. I have run R CMD check, which passed with 0 errors, warnings and notes.

* This is an update of an existing release (0.2.0 -> 0.2.1)
