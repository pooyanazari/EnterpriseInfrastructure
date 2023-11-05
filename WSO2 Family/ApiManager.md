# Build and Run WSO2-APIM
How to Build and Run WSO2 API Manager (wso2-apim)

### Build
1. Install [Oracle JDK](https://github.com/pooyanazari/EnterpriseInfrastructure/blob/main/JavaFamily/InstallJDK.md) __11.0.14__ on your system
2. Install [Apache Maven](https://github.com/pooyanazari/EnterpriseInfrastructure/blob/main/JavaFamily/InstallMaven.md) __3.9.5+__ on your system
3. Download and Extract [wso2-apim 4.2.0](https://github.com/wso2/product-apim/releases/tag/v4.2.0)
4. Run one of the following maven commands from `product-apim-X.Y.Z` directory
```bash
$ mvn clean package
# or
$ mvn clean package -Dmaven.test.skip=true
```
5. After success build, `wso2am-X.Y.Z.zip` file can be found in `modules/distribution/product/target/`.

### Run
1. Navigate to `product-apim-X.Y.Z/modules/distribution/product/target/` directory and extract `wso2am-X.Y.Z.zip`.
2. Navigate to `bin` directory and run api-manager.[sh/bat]