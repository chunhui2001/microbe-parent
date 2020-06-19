#################
#### 电子商务 ####
#################
### 商品信息库微服务 -- products micro
$ mvn archetype:generate -DgroupId=com.microbe.products -DartifactId=microbe-products -DarchetypeArtifactId=pom-root -DinteractiveMode=false -DarchetypeGroupId=org.codehaus.mojo.archetypes -DarchetypeVersion=RELEASE -DarchetypeCatalog=local
### 商品信息库微服务 -- products ett
$ mvn archetype:generate -DgroupId=com.microbe.products.ett -DartifactId=microbe-products-ett -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local
### 商品信息库微服务 -- products rmi
$ mvn archetype:generate -DgroupId=com.microbe.products.rmi -DartifactId=microbe-products-rmi -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local
### 商品信息库微服务 -- products app
$ mvn archetype:generate -DgroupId=com.microbe.products.app -DartifactId=microbe-products-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local