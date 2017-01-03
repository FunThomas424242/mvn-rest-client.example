# mvn-rest-client.example

* Currently *mvn clean install* not working because there is an issue at 


```
[INFO] ------------------------------------------------------------------------
[INFO] Building mvn-rest-client.example 1.0.12
[INFO] ------------------------------------------------------------------------
Downloading: http://jcenter.bintray.com/com/github/cjnygard/mvn/rest-maven-plugin/0.1.4/rest-maven-plugin-0.1.4.pom
Downloading: http://jcenter.bintray.com/com/github/cjnygard/mvn/rest-maven-plugin/0.1.4/rest-maven-plugin-0.1.4.pom
[WARNING] The POM for com.github.cjnygard.mvn:rest-maven-plugin:jar:0.1.4 is missing, no dependency information available
Downloading: http://jcenter.bintray.com/com/github/cjnygard/mvn/rest-maven-plugin/0.1.4/rest-maven-plugin-0.1.4.jar
Downloading: http://jcenter.bintray.com/com/github/cjnygard/mvn/rest-maven-plugin/0.1.4/rest-maven-plugin-0.1.4.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 3.002 s
[INFO] Finished at: 2017-01-03T17:09:02+01:00
[INFO] Final Memory: 9M/107M
[INFO] ------------------------------------------------------------------------
[ERROR] Plugin com.github.cjnygard.mvn:rest-maven-plugin:0.1.4 or one of its dependencies could not be resolved: Could not find artifact com.github.cjnygard.mvn:rest-maven-plugin:jar:0.1.4 in central (http://jcenter.bintray.com) -> [Help 1]
[ERROR] 

```