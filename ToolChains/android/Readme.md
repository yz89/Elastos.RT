
***
#If you want to use the new ndk version, you can:
##1. Download the ndk

##2. Enter the folder: ../ndk/build/tools

##3. You can use the script make-standalone-toolchain.sh to generate your ndk toolchains
eg:
./make-standalone-toolchain.sh --platform=android-21 --system=linux-x86_64 --ndk-dir=/xxx/android-ndk-r10d --toolchain=arm-linux-androideabi-4.8 --install-dir=/xxx/Elastos.RT/ToolChains/android/Ndk

* At some ndk version, --ndk-dir may be invalid, you don't have to use it.

##4. Copy the ndk files
Copy the ndk files to /yourfolder/Elastos.RT/ToolChains/android/Ndk

##5. Rebuild Elastos.RT
  
  
  
  
***
#Verified the ndk version
##Now, we verify the ndk can be use:
* android-ndk-r10d
* android-ndk-r14b
