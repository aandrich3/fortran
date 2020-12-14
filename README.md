# Paht's fortran learning README
Documenting my Fortran learning with examples. 

These sets of codes are compiled using a makefile and fortdepend for auto-dependancy generation. This means that you do not need to specify 
```
something.o:
  depends_on_1.o
  depends_on_2.o
```

This is automatically generated by fortdepend and is included in the makefile `include(my_project.dep)`
To get started (this works on linux but can work on windows if you want)
<li>
  <ol>Install fortdepends using `pip install fortdepend`</ol>
  <ol>In terminal do `find -name fortdepend` that is your reference path that you need to set in the make file. It should reference the binary. 
  You should simply be able to call fortdepend in your folder and have it generate a dependancy file `fortdepend -o Makefile.dep`. If this doesn't work then that's not the right file</ol>
</li>

Give this project a try once you've set up fortdepends by running `make`
