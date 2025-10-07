## Running Java code

### Single file
```bash
java path/to/File.java
```

### Packaged (with `package`)
```bash
mkdir -p out
javac -d out $(find . -name "*.java")
java -cp out your.package.Main
```

