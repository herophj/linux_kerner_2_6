# linux_kerner_2_6



# Problem SEGMENT_SIZE Undeclared error
> https://lkml.org/lkml/2012/3/31/4
look around kerner/include/linux/a.out.h
SEGMENT_SIZE is not defined

BTW, no one is using a.out on ARM anymore

solve : CONFIG_BINFMT_AOUT [n]
Kernel support for a.out and ECOFF binaries
-> Userspace binary formats



