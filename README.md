# android_kernel_bq_bulma-UC
#WHAT IS THIS?
Linux Underclocked Kernel source code to 1.7GHZ for the device bq Aquaris E6
#BUILD INSTRUCTIONS?
Specific sources are separated by branches and each version is tagged with it's corresponding number. First, you should clone the project:

	$ git clone git@github.com/theandroid02/android_kernel_bq_bulma-UC.git

After it, choose the version you would like to build:

	$ cd aquaris-E6/
	$ git checkout 1.1.0_20140908-0900


Finally, build the kernel:

	$ ./makeMtk -t bulma n k
