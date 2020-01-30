# EON-CP-BootAnimation


I have included both a PNG and JPEG export of the required files, I always see to use PNG but ive had more luck with JPEG, well, if your here that means you probably know wht your doing.... pls share secrets

If you notice anything wrong with any of the pictures or find out why this particular animation is not working HMU on the Comunity Pilot Discord

If you want to keep the stock comma boot animation, please back it up, I also have copies and it can be found on their github for your specific bootloader

If anyone is interested also in the Gimp files I can provide


Im also not sure if the provided bootanimation.zip is a working version, sorry.


## How to Use
[Useful Guide 1](https://usmile.at/blog/how-to-customize-your-android-boot-animation)
[Useful Guide 2](https://android.googlesource.com/platform/frameworks/base/+/master/cmds/bootanimation/FORMAT.md)


### To Zip

Make sure you have WinRar installed
1. Highlight all the files in bootanimation
2. Right click and choose the "send to archive" winrar shortcut

NOTE: You must zip the contents inside the bootanimation folder NOT the bootanimation folder

3. Set the name to bootanimation.zip
4. For "compression method" choose "STORE" (It must be an uncompressed zip file!!)



### To Transfer
1. [SSH into EON](https://medium.com/@jfrux/comma-eon-getting-connected-with-ssh-3ed6136e4a75)
2. `mount -o remount,rw /system`
3. Transfer new bootanimation to /system/media using FileZilla
4. `chmod 666 /system/media/bootanimation.zip`
5. Reboot & Enjoy




## License
Copyright 2020 End Of Line

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
