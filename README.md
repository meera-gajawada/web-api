# Web API

Sample project for prototype

## Build

```
    mvn clean install
```

## Build with an image tag

``` 
    mvn jib:build -Djib.to.tags=local.04
```

## installing helm chart locally

```
helm upgrade demo-devops-webapp -f k8s/helm/values.yml ./k8s/helm -i --set image.tag=local.04
```


## Running locally - added comment



```
 mvn spring-boot:run
```

open localhost:8080
