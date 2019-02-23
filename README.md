# Java-Windows-Tutorial

##Just Java problems the tutorial:
1. Download your JDK from
https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

2. Find your JDK bin path
<img src="https://lh6.googleusercontent.com/-QCXFj70pponp0bMu2gY4BK0CJsNLTC9tRFZ0Iu3uueQb3itzLQBZuGQfFbIDjXSuZj0tKp_3do8V6gcPFZV=w1920-h902-rw" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_48_07-bin.png" aria-hidden="true">

3. Go open your environment variable settings
<img src="https://lh3.googleusercontent.com/xZvoOGjpVXTIY0Aw0VJOfCn0SHS0_9-0xrHj1A5nt5NA9HefBmC9iwSIwKNSNON-WT58AENuoKT0qgY0yK0e=w1920-h902-rw" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_51_07-Microsoft Edge.png" aria-hidden="true">

4. Open environment variables
<img src="https://lh3.googleusercontent.com/SIzH35xs1tx4VrLup7UoLMgOOoS9rRIVMgnBTRUt3J502WP7Q4f0maZLsynKLYnR7nQ44n-sFzmpAg7nW3o9=w1920-h902" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-20 20_57_32-System Properties.png" aria-hidden="true">

5. Find path and click edit
<img src="https://lh4.googleusercontent.com/BBB0yp0wVMcr0oW-ah8eWhPOgp21aHiHMhNBUfe3lUzuqxZzUQ91gVMu2kFY03WRGNN1J-PaM6MeAdAtWTxy=w1920-h902" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_52_10-Environment Variables-editpath.png" aria-hidden="true">

6. Delete any existing Java paths and click new then enter the bin path that we found in step 2. Click "OK" once you finish doing this.
<img src="https://lh3.googleusercontent.com/Mxb-1Nt84jfDJ4SdSqpOFVVhG1LrNKk1cLnGIW2wveXL-HnEvRm6SoeLF3txqPWBEdWiqMyVFRyymnpGFVGP=w1920-h902" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_52_30-Edit environment variable.png" aria-hidden="true">

7. Add a new variable named JAVA_HOME to your system variables with the same path we found in step 2.
<img src="https://lh5.googleusercontent.com/jGJYjYhfFfdvz-yHNPTY3s0FcJcgLX1e-SVq2zX6DmRVkBkFAwK-zo98wqhCp5-VFH3d5nbDuOInHY3RILQI=w1920-h902">
<img src="https://lh3.googleusercontent.com/09PMw9x6DWoErnJlCR1LNYhYE1eGA-dqQBpK0BYFFdRVSnulgTCTISBEJ0L3pjcc7_EP-nfIByVdF7-XmBkU=w1920-h902">
Now your console commands should be working test them out as well as "java -version" command.

## Part II VSCode and Java, the trials of direction.

1. Open up vs code and go to your settings
<img src="https://lh4.googleusercontent.com/epYt1XT6IyQnWGriFW3SfUEejge5H_cH1jEVrEcdDQEk4Y5ZUujLIqN2CIfGQ9aTK89kg2OuQ-dtwezci_j4=w1920-h902" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_49_33-Inbox - CaseyOutlook ‎- Mail.png" aria-hidden="true">

2. Type in java home and open up the settings.json
<img src="https://lh4.googleusercontent.com/epYt1XT6IyQnWGriFW3SfUEejge5H_cH1jEVrEcdDQEk4Y5ZUujLIqN2CIfGQ9aTK89kg2OuQ-dtwezci_j4=w1920-h902" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_49_33-Inbox - CaseyOutlook ‎- Mail.png" aria-hidden="true">

3. Find your JDK folder path
<img src="https://lh6.googleusercontent.com/aEB5ICdTrbyzt3CW45CPM_AZn5c-9pccFvVaGH6fzxjsEF-HIMe5W4xrgZNZWF090lqFJEZm9v6esOdlA2O4=w1920-h902" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_48_40-jdk1.8.0_201.png" aria-hidden="true">

4. Edit the settings.json to have Visual studio point to java home
<img src="https://lh5.googleusercontent.com/mv-ym-Mx-uWq6R6wRwmYNdqaYGFqutNRWhx3xu0Q8v3UVxa2mT3QL_31Ads5x_MX8HZEwUuFqHa9_FxA1ZJn=w1920-h902-rw" class="ndfHFb-c4YZDc-HiaYvf-RJLb9c" alt="Displaying 2019-02-23 11_50_42-settings.json - 21-regionalized-content - Visual Studio Code.png" aria-hidden="true">

