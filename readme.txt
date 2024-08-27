# LFS Demo 

The repo contains dummy files generated using [random file generator](https://myjob.page/tools/random-file-generator) for given size. 

We then `lfs-track` the binary files, and can try pulling out specific files as needed.  

This exercise would help those who want to maintain a repo, which has many LFS files, but do not want to pull all the LFS files every time. They may not even work on all LFS files, so they ould selectively choose what they want to pull, work on it and push back. 

The *.bin files are LFS tracked. The *.txt files are regular files.  

Try out various use cases. One can be that, you want to pully only folder B contents and a single specific LFS file, in root say `R_10KiB.bin`

