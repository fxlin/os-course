# PROJECTS

This course centers on a series of *projects*, each offering its own set of experiences: 

| **Project**   | **You will build ...**                               | **Experience**                                               |
| ------------------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------ |
| [kernel](https://github.com/fxlin/p1-kernel)                 | A tiny, modern  kernel for Raspberry Pi 3            | roll-your-own  kernel, baremetal programming, Armv8, SoC hardware |
| [concurrency](https://github.com/fxlin/p2-concurrency)       | Scaling up data  structures on multicores            | programming a  large number of cores, profiling, performance debugging |
| [TEE](https://github.com/fxlin/p3-tee)                       | A machine learning  service secured by Arm TrustZone | security,  hardware-based isolation, embedded AI             |
| [persistence](https://github.com/fxlin/p4-fs)  (a [Lite](https://github.com/fxlin/p4-fs/tree/master/lite) version) | Filesystem image  forensics                          | reverse  engineering, binary data structures, working with hexdumps |

## Access the course server

Using your CS credentials (not UVA). See [wiki page](https://www.cs.virginia.edu/wiki/doku.php?id=compute_resources). Contact felixlin@ if you do not have CS credentials. 

First SSH to **portal.cs.virginia.edu**. From there SSH over to **labsrv06**

Note: 

1. Avoid typing password everytime! Enable SSH key authenatication and     do ssh-copy-id. (Google this)

1. You have to take two hops. i.e. SSH proxy won't work. I tried. They     turned off SSH forwarding on portal. 

(Aug/31: we are in the processing of getting a server with MORE cores for p2. Stay tuned)

 

# Turn in assignments

Turn in via the MS teams assignment page. There are two types of assignments. 

1. Answer questions: upload your     answer in docx or PDF. 

2. Coding: 

3. - Create a [tarball](https://www.howtogeek.com/248780/how-to-compress-and-extract-files-using-the-tar-command-on-linux/) of your code and upload it 

- Guidelines for what's     included in your code tarball:

- - Name format: [computingid].**tar.gz**

  - - E.g. lg8sp.tar.gz
    - It is recommended you use       the command 'tar -czvf' as suggested in the link above to generate       `.tar.gz`. 

  - Content:

  - - Your code obviously. You       can name your source files however you want but make sure you include       two files:

    - - Makefile: so that TA can        build your code and try it out
      - README: anything you want        to address to TA (e.g. any caveats of your code that TA shall be aware        of, extra build instructions) 

    - Do not include any binaries       (e.g. *.elf, *.o, *.bin) in the tarball. 10%       penalty if you do so. 

