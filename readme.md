Create a manifest file and pass the main class file in 
main-class attribute in the file

jar cmf Hello.mf Hello.jar Hello.class Hello.java

format

This will create the jar file-Hello.jar

Then use the follwing command to check if the jar is working:

java -jar Hello.jar

this will run the class file mentioned in the manifest file

lets create a local dependency from the jar to 

