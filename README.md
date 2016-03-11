## About ## 
- It contains some of the example codes using `chapel` programing language.  
- you need to set your env. first to run these codes.  

## Setting environment (In linux systems) ##  
- Download it from [this][http://chapel.cray.com/download.html] link.  
- Unzip the .tar file and get inside the directory.  
- Set up your environment to use Chapel in "Quick Start" mode by `. util/quickstart/setchplenv.sh`.  
- Build the compiler and runtime libraries using:  `make` or `gmake` whiever works on your system.  
- Optionally, check that your Chapel installation is working correctly: `make check`  
- Compile an example program using: `chpl -o hello examples/hello.chpl`  
- Execute the resulting executable: `./hello`  
- Experiment with Chapel in Quick Start mode to your heart's content.
     * Once you are comfortable with Chapel and interested in using a full-featured version in the preferred configuration:
     	i. Open up a new shell to avoid inheriting the previous environment settings.  
     	ii. Repeat steps 1-7 above, but in Step 2, use util/setchplenv.* instead of util/quickstart/setchplenv.*  

 ### Enjoy using chapel ###

