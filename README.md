# ubuntu-kernel-management

This is a WIP resulting from ukuu leaving open source and becoming a paid and closed source application. Having a GUI for this was nice, but the same and more can be accomplished with some easy scripts.

First portion of this repository is to focus on managing the installed kernels. The second portion (maybe) will address the installation of mainline kernels. Installation of mainline kernels in Ubuntu is really not recommended for most users but can be quite handy for development and testing. Due to that, it is not a primary focus.

I hope to eventually end up with a script to perform the functionality I liked in ukuu. By collecting the proper scripts, I hope this set of queries to remain open source and not reply on a GUI or paid development.

## Key Parts
1. List all installed kernels
1. Show the currently active kernel
1. Repair a default kernel that will not update in your package manager
1. Remove unsused kernels
1. Remove specific kernels
1. Update the default kernel
1. Update a non default kernel
