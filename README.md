# Java-Windows-Tutorial
Just Java problems the tutorial:
1. Download your JDK from
https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

2. Find your JDK bin path
https://drive.google.com/file/d/1Ua8oM7nmGPvjpUwRvsSH8y9YVXxAi6Xw/view?usp=sharing

3. Go open your environment variable settings
https://drive.google.com/file/d/1Bze9nD3jSpCgG8PBZt2rgyBBFI5lm09B/view?usp=sharing

4. Open environment variables
https://drive.google.com/file/d/1vouONOnXbSbdpOp4scyZwpGQtxhqwDmI/view?usp=sharing

5. Find path and click edit
https://drive.google.com/file/d/14Gi2jsSSLRSTmA1TWMdWrnY4XWFYPX8b/view?usp=sharing

6. Delete any existing Java paths and click new then enter the bin path that we found in step 2. Click "OK" once you finish doing this.
https://drive.google.com/file/d/1ecvsaShxYRmM3-jXzsqgrvJJ_6ClUFJZ/view?usp=sharing

7. Add a new variable named JAVA_HOME to your system variables with the same path we found in step 2.
https://drive.google.com/file/d/1mjcxMRgGIvbsIykL2yfL4QoetwYaF1uJ/view?usp=sharing
https://drive.google.com/file/d/1pYXVSw3jEmOO5yY19dN0xChaUMEiJTVI/view?usp=sharing

Now your console commands should be working test them out as well as "java -version" command.

Part II VSCode and Java, the trials of direction.

1. Open up vs code and go to your settings
https://drive.google.com/file/d/1HE6aFznE9IsvIIfr8la1BF8kqQcRO73V/view?usp=sharing

2. Type in java home and open up the settings.json
https://drive.google.com/file/d/1zaav4gSZMOdCyBouMVRh16diwvpOPi9M/view?usp=sharing

3. Find your JDK folder path
https://drive.google.com/file/d/1bkldJN7c3a4syZ-zbS_q0bTh1uYTdSVl/view?usp=sharing

4. Edit the settings.json to have Visual studio point to java home
https://drive.google.com/file/d/1Zl6pVpAyUzEH6DyTHVuu6fykS3KsDvTm/view?usp=sharing
Make sure to change your single \ to double \\
e.g
"C:\Program Files\Java\jdk1.8.0_201"
becomes
"C:\\Program Files\\Java\\jdk1.8.0_201"
