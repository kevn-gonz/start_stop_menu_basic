# BASIC application(s) control script
Use this script if you want a centralized script to manage different application's (or components of a singe app) start/stop process.

There are scenarios in which you manage several applications at a time, OF COURSE, each application has different procedures to start/stop its components so you have 2 options:
1. Memorize the procedures to start/stop each and every single one of your applications.
2. Create a centralized script that you can execute using the same command (**./script start|stop app**) no matter which platform you are currently working on.

In other words, you just have to implement the procedure to start/stop the application you need inside the script, and run the script.
At the end, you can have +50 applications in different servers, and ALL of them will be started/stopped using the same command.
* ./script start app
* ./script stop app

Finally, another advantage is that you can use Configuration Management apps/systems such as SaltStack, Puppet, Chef or the one you preffer and run **the same** command to start/stop apps no matter which one it is.