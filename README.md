# WordCount
Hadoop Exercise on 2018/03/31
## Note
1. args[0] is the name of the program being excuted which is WordCount in this case. Using args[1] and args[2] instead.
2. If see `java.io.IOException: Mkdirs failed to create /var...`, it's because that the filesystem of OSX is case-insensitive. So remove `META-INF/LICENSE` from the jar file.  
```zip -d mahout-examples-0.6-cdh4.0.0-job.jar META-INF/LICENSE```