# Builders project

This respository contains multi-module sample project

## How to build it

Please, open on Windows OS open command line or PowerShell and type in path to downloaded sources, using this command:

```
cd path\to\sources\builders\
```

And, next step is just use this maven command to build files: `jar` for admin-module and `war` for web module. These files 
will appears in appropriate target folders:

```
mvn clean install
```
## Execute tests

To execute all tests need to use another command from `../builders` folder:
```
mvn test
```