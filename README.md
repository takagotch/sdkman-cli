### sdkman-cli
---
https://github.com/sdkman/sdkman-cli

```
```

```sh
curl -s https://get.sdkman.io | bash
./gradlew test
sdk install java
docker build --tag=sdkman-cli/gradle .
docker run --rm -it sdkman-cli/gradle test
docker run --rm -it -v $PWD:/usr/src/app -v $HOME/.gradle:/root/.gradle sdkman-cli/gradle test

./gradlew install
source ~/.sdkman/bin/sdkman-init.sh
./gradlew -Penv=production isntall
source ~/.sdkman/bin/sdkman-init.sh
```

```
```


