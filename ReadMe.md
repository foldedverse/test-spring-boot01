Setup
```
    curl -s "https://get.sdkman.io" | bash
    source "$HOME/.sdkman/bin/sdkman-init.sh"
    sdk help
    sdk install gradle 8.1.1

    git config --global user.name "folded verse"
    git config --global user.email johndoe@example.com
    git remote add origin https://[TOKEN]@github.com/foldedverse/test-spring-boot01.git

```

For Setting up Gradle 
```
    gradle wrapper
    gradlew build
    ./gradlew build
    ./gradlew bootRun
    ./gradlew build
    ./gradlew bootRun
```

