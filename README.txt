AWS Code Pipeline Stage: OK
Jenkins Build is getting: 
Started by an SCM change
Building in workspace /var/lib/jenkins/workspace/HelloWorld_AWSPipeL
[WS-CLEANUP] Deleting project workspace...
[WS-CLEANUP] Done
[AWS CodePipeline Plugin] Job '246e7bd7-8d47-43a8-b413-a7fd100e3049' received
[AWS CodePipeline Plugin] Clearing workspace '/var/lib/jenkins/workspace/HelloWorld_AWSPipeL' before download
[AWS CodePipeline Plugin] Detected compression type: Zip
[AWS CodePipeline Plugin] Successfully downloaded artifact from AWS CodePipeline
[AWS CodePipeline Plugin] Extracting '/var/lib/jenkins/workspace/HelloWorld_AWSPipeL/VgFq1uU.zip' to '/var/lib/jenkins/workspace/HelloWorld_AWSPipeL'
[AWS CodePipeline Plugin] Artifact uncompressed successfully
[HelloWorld_AWSPipeL] $ /home/ec2-user/apache-maven-3.3.9/bin/mvn package
[INFO] Scanning for projects...
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building my-app 1.0-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ my-app ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /var/lib/jenkins/workspace/HelloWorld_AWSPipeL/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ my-app ---
[INFO] Changes detected - recompiling the module!
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 2 source files to /var/lib/jenkins/workspace/HelloWorld_AWSPipeL/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ my-app ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /var/lib/jenkins/workspace/HelloWorld_AWSPipeL/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ my-app ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ my-app ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ my-app ---
[INFO] Building jar: /var/lib/jenkins/workspace/HelloWorld_AWSPipeL/target/my-app-1.0-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 8.201 s
[INFO] Finished at: 2016-08-15T00:28:30-05:00
[INFO] Final Memory: 14M/33M
[INFO] ------------------------------------------------------------------------
[AWS CodePipeline Plugin] Publishing artifacts
[AWS CodePipeline Plugin] Uploading artifact: {Name: MyAppBuild,Location: {Type: S3,S3Location: {BucketName: codepipeline-us-west-2-624318484677,ObjectKey: hello_world/MyAppBuild/BCJMgOj}}}, file: /var/lib/jenkins/workspace/HelloWorld_AWSPipeL/target/my-app-1.0-SNAPSHOT.jar
[AWS CodePipeline Plugin] Upload successful
[AWS CodePipeline Plugin] Build succeeded, calling PutJobSuccessResult
Finished: SUCCESS



Beta Stage is getting:
Action execution failed
Deployment d-FZ1RVAE7H failed
Link to execution details


