---
layout: post
title:  "Notes - Python"
date:   2023-06-05 21:23:23 -0700
categories: jekyll update
---

This is my notebook for Python. 

# Run executables using subprocess

{% highlight ruby %}
import subprocess

# List of executables and input files
executables = ["executable1", "executable2", "executable3"]
input_files = ["input1.txt", "input2.txt", "input3.txt"]

# Loop through the executables and input files
for executable, input_file in zip(executables, input_files):
	
	subprocess.run([executable, input_file], capture_output=True)


{% endhighlight ruby %}
