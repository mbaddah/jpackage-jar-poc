# jpackage-jar

Proof of concept to test out jpackage library as part of JDK14 and generator own installer.

```aidl
/Library/Java/JavaVirtualMachines/temurin-16.jdk/Contents/Home/bin/jpackage --type exe --name HelloJarPkg --input .  --main-jar out/artifacts/HelloJar_jar/HelloJar.jar --main-class mainjar

```