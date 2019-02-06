#Contribution guide for Amalgam

##Prequisites
Following tools must be installed to work on this project.
1. Git
2. Java 8
3. NodeJs 10.15.0
3. Scala 2.11.x 
4. Intellij Community/Ultimate

##Creating an issue
We use github issues to create and track tasks, bugs, features, discussions, etc. 
A issue has to have an appropriate title and description.

##Environment setup
1. Fork, clone set the remotes as specified here: https://help.github.com/articles/fork-a-repo/
2. Import this project to Intellij as shown here: https://www.jetbrains.com/help/idea/gradle.html#gradle_import
3. You should fix a issue on a diffrent branch. The commit message should contain the issue id.
   For example if the issue id is **123** then be of the commit message should be of the format **[AMALGAM-1] < Issue Title >**
4. A PR against the issue can be raise as shown here: on a diffrent branch and raise a pr: https://help.github.com/articles/creating-a-pull-request-from-a-fork/

###Building the project
1. In the terminal run the following command in the project root to build the project.

    ``./gradlew clean build``
    
    This will build the artifacts and run the necessary tests.
