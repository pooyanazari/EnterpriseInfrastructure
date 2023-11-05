# Build and Run WSO2-IS
How to Build and Run WSO2 Identity Server (wso2-is)

### Build
1. Install [Oracle JDK](https://github.com/pooyanazari/EnterpriseInfrastructure/blob/main/JavaFamily/InstallJDK.md) __11.0.14__ on your system
2. Install [Apache Maven](https://github.com/pooyanazari/EnterpriseInfrastructure/blob/main/JavaFamily/InstallMaven.md) __3.9.5+__ on your system
3. Download and Extract [WSO2-IS 6.1.0+](https://github.com/wso2/product-is/releases/tag/v6.1.0)
4. Run one of the following maven commands from `product-is-X.Y.Z` directory
```bash
$ mvn clean package
# or
$ mvn clean package -DskipTests
```
5. After success build, `wso2is-X.Y.Z.zip` file can be found in `modules/distribution/target`.

### Run
1. Navigate to `product-is-X.Y.Z/modules/distribution/target` directory and extract `wso2is-X.Y.Z.zip`.
2. Navigate to `bin` directory and run wso2server.[sh/bat] 