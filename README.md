# install-WHL-file-with-conda-commands
This is a tutorial for installing WHL files by anaconda environment.


For installing the PyTorch package in an Apple ARM architecture PC, in some cases, anaconda is unable to find a proper PyTorch package to install. Thus, it is recommended that use WHL extension file for this reason.

after downloading WHL extension file from <a href=https://ossci-macos-build.s3.amazonaws.com/torch-1.8.0a0-cp38-cp38-macosx_11_0_arm64.whl>https://ossci-macos-build.s3.amazonaws.com/torch-1.8.0a0-cp38-cp38-macosx_11_0_arm64.whl</a>, it is turn to run the following command and structures:
1- Open Anaconda Command prompt or open terminal windows,
2- Activate the goal environment using "conda activate Your_Environment_name",
3- Run the command: "conda install torch-1.8.0a0-cp38-cp38-macosx_11_0_arm64.whl", and
4- Enjoy it.

