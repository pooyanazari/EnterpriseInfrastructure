# Install Maven
How to Set up Maven

### On Linux
1. [Have a JDK installation on your system](https://github.com/pooyanazari/EnterpriseInfrastructure/blob/main/JavaFamily/InstallJDK.md)
2. Download and Extract Maven
3. In your home directory, open the BASHRC file(~/.bashrc)
4. Add the following two lines at the bottom of the file
```bash
export PATH=$PATH:/path_to_maven/apache-maven-x.y.z/bin/
```
5. To see Maven version, execute the following command
```console
mvn -v
```
