# Install JDK
How to Set up JDK

### On Linux
1. Download and Extract JDK
2. In your home directory, open the BASHRC file(~/.bashrc)
3. Add the following two lines at the bottom of the file
```bash
export JAVA_HOME=/path_to_jdk/jdk-x.y.z
export PATH=${JAVA_HOME}/bin:${PATH}
```
4. To verify that the JAVA_HOME variable is set correctly, execute the following command
```bash
echo $JAVA_HOME
```
5. To see Java version, execute the following command
```console
java -version
```
