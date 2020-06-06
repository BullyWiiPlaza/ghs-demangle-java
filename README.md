### ghs-demangler-java

A demangler implementation in `Java` for the `GHS compiler` used on the `Nintendo Wii U`.

### Usage
This is a command line application which can be used as follows:  
`ghs-demangler.jar [input-file-path]`  
The output will be the demangled name.

### Compiling

[`Java JDK 8`](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) or newer as well as a [`maven`](https://maven.apache.org/download.cgi) installation are required.

For compiling, simply run `mvn package`.

### Credits
* `Chadderz` for the [original `GHS demangler`](https://github.com/Chadderz121/ghs-demangle) in `C#`
* `Maschell` for the `Java` rewrite
* `BullyWiiPlaza` for an improved build `pom.xml` and writing a `README`