# mythtv-alpine-linux

mythtv on alpine linux so far only tested on arm 32bit(armv7). 

## Completed So far:
    * Worked out build dependencies
    * Worked out needed code modifications for musl
    * Compile test passed mythtv-fixes-35
    * Patch created
    * mythfrontend tested using vc4-kms-v3d
    


 ## Todo: 
    * Test on x86_64
    * Work out all runtime deps.
    * Create custom mythfrontend.conf.d & mythfrontend.init.d files
       * Add wrapper for mariadb TLS work around for connection to servers not using TLS.
    * Create a proper apk package.
    * Test package install on minimal images
    * Upload configuration sources
    * Make release pkg
    * repeat for fixes/36
    



    
