BootStrap: docker
From: lofaruser/imaging-pipeline:latest

%post


%runscript
  # For debugging purposes
  printenv
  # Sanity check for LOFAR s/w
  source  /lofarsoft/lofarinit.sh
  genericpipeline.py -h
