# Clean-GCR-Repository

cleargcr.sh cleans up tagged or untagged images pushed before specified date

for a given repository (an image name without a tag/digest).

## USAGE:
  cleargcr.sh REPOSITORY DATE

## EXAMPLE
  cleargcr.sh gcr.io/test/my-app 2019-04-14
  
  would clean up everything under the gcr.io/test/my-app repository
  pushed before 2019-04-14.
