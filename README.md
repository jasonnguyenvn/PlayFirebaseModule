# PlayFirebaseModule

A simple module for your Play 2 Project to intergated with firebase.

## Usage

1. Add dependency to your build.sbt

```
libraryDependencies += "com.google.firebase" % "firebase-admin" % "5.4.0"
```

2. Copy the file `FirebaseModule.java` to the folder modules of your project.

3. Put your secret key (.json) to the folder conf/META-INF/firebase.json

4. In file conf/application.cnf, enable the module:

```
play.modules.enabled += "modules.firebase.FirebaseModule"
```
 
