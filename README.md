# Ubuntu Image for WSL 

This Ubunt Image (.tar) for WSL is splited to upload to github. Combine parts (.tar-*) of the image by below 
command.

```sh
# Command to combine parts of image:
cat [Image Name].tar-* > [Image Name].tar
```

# Ubuntu Image List
1. ubuntu: Ubuntu20.04 Image
1. ubuntu_cuda11_7: Ubuntu20.04 + CUDA11_7
1. ubuntu_cuda11_7_etc: Ubuntu20.04 + CUDA11_7 + Docker + Nvida Container Toolkit

# Note to myself

```sh
# Command to split image:
split -b 99m -a 1 [Image Name].tar [Image Name].tar-
```