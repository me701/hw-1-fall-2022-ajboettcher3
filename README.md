# ME 701 -- Homework 1 -- Aidan Boettcher

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

Something I routinely do on a computer at both internships and school is use CAD software to design or look at parts. Most software such as CATIA, SolidWorks, or Creo are rather expensive to gain access to. In some quick research, I found a free open-source alternative called FreeCAD. This software offers many of the features of a typical CAD system such as FEA or CAM/CNC workbenches. Since the software is open source, it is available to all and users can aid in bug fixes and new feature addition.

## Problem 2 -- Test

## Statement 

Something here.

### Solution

## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

Using the command “cat /proc/cpuinfo” in the command line, relevant CPU information was displayed. The command “cat” is shorthand for concatenate and allows us to view the contents of the specified file. My processor speed is 1.30 GHz and my CPU has 4 cores. 

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution

Using the command “top” in the command line displays the different tasks managed by Linux. The command “top” is shorthand for table of processes and it shows real time data from the system. It displays a list of the tasks, along with relevant associated information such as percentage of CPU and memory usage. 

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution

Using the command “which bash” in the command line I determined that bash is located at “/usr/bin/bash” in my Linux system. By using the command “bash –version” in the command line I learned that I am using version 5.0.16(1) of bash. 
