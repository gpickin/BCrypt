BCrypt
======

This is a simple CFC for using BCrypt - Based on **Seth Feldkamp's ColdBox Plugin**.
https://github.com/sfeldkamp/coldbox-plugin-BCrypt

Getting BCrypt.jar
------------------

This plugin depends on a BCrypt.jar file which is not packaged with this plugin.
Download jBCrypt from http://www.mindrot.org/projects/jBCrypt/.
Compile BCrypt.java to a .class file named BCrypt.class.   
>$ javac jBCrypt-0.3/BCrypt.java 

Package *BCrypt.class* into a jar file named *BCrypt.jar*.
> $ jar cvf BCrypt.jar BCrypt.class 

> added manifest

> adding: BCrypt.class(in = 20490) (out= 14027)(deflated 31%)


Now we have our jar file, we can put it in our ColdFusion Classpath

