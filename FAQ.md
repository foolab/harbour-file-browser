
# FAQ for File Browser for Sailfish OS 

### What is File Browser?

File Browser is a simple tool to access file system without 
enabling developer mode or registering to Yandex and installing
a file manager from there.

### Why copying files gives an error message 'Failure to write block'?

Your storage (phone or sd card) is most likely full.

### What does error 'Unknown error' mean?

One reason for this error message can be that you tried to move
a folder between the phone and the SD Card. Instead of 
moving (cut-paste), you should copy the folder.

### Why opening a file does not work, but gives error "No application to open the file"?

It means that the xdg-open command used to open files does not recognize
the file type or it doesn't find a preferred program to open it.

The Sailfish OS is still at beta stage, so it doesn't have all bindings
for all media formats.

### Why accessing SD Card gives error 'SD Card not found'?

Perhaps your SD Card is not properly inserted to the phone.
Perhaps it has a file system which is not recognized by the phone.
You can also try to access the SD Card with another file manager, 
such as Cargo Dock.

### How to copy files to Android Storage?

File Browser can't copy files to Android Storage, because of its permissions.
Try an Android file manager, such as ES File Explorer (available in 
Yandex store), it can access Android and Jolla native file system.

### How to copy multiple files?

It is not possible. Try the Cargo Dock file manager app in 
the Jolla store, it can manage multiple files.

### Does it have XXX feature?

It can't change owners, sudo, multi-select files, create links,
edit files, share files, send email, mms or sms, open ftp sites, 
connect to samba server, simulate vi and it does not blend or make coffee.

### Are there any alternative apps?

There is the wonderful Cargo Dock file manager in the Jolla store.
You can also try the Jolla's own file manager called Files,
which can be installed with 'pkcon install jolla-fileman' 
in Terminal (requires Developer Mode).

For best access to Android storage, try ES File Explorer in Yandex store.
It can access Android storage and Jolla file system.

