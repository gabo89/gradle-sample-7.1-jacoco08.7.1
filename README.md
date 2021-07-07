# sample gradle example with 7.1 and jacoco 0.8.7

first install gradle in your computer  and clone this repositories to work 


buid.gradle have a custom task called jacocoFullReport, you can invoke it by using 

```
gradle jacocoFullReport --warning-mode all
```

to view all custom tasks enabled for this gradle proyect you can use

```
gradle task
```

the order to execute is 

```
gradle build
gradle jacocoFullReport --warning-mode all
```



# gradle-sample-7.1-jacoco08.7.1
