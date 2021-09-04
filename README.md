# Gradle-demo

Steps to build a project with Gradle in Jenkins-

```

1. Configure Gradle plugin for Jenkins.
- Go to Jenkins dashboard. Click on Manage Jenkins and select Manage Plugins, select the Gradle plugin.
- Under Manage Jenkins, Global Tool Configuration add Gradle and save.

2. Create a Gradle project
- Open the terminal. If you don’t have gradle installed, run sudo apt-get install gradle command
- Create a new directory and navigate to it. Run gradle init to create a sample gradle project.
$ mkdir gradle-demo  
$ cd gradle-demo
$ gradle init

3. Go to github.com and create a new repository and push the gradle project to Github.

4. Build a new project with Gradle in Jenkins and view the console output.

```

