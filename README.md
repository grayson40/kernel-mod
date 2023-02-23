# COP4600 Linux Kernel module

## How to build, install, and test

1. Open a terminal and cd into the directory of this project.
    
2. Execute the following commands:

    - Make the project module.
    
        `make`
    
    - Install the module.
    
        `sudo insmod lkmasg1`
    
    - Check the kernel console.

        `sudo dmesg`
    
    - Test the module.

        `sudo ./test /dev/lkmasg1`
        
    - Uninstall the module.
        
        `sudo rmmod lkmasg1`
