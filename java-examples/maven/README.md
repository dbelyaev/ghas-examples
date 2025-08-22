# Java Maven Example

* :mag_right: **CodeQL scan configuration:** See [/.github/workflows/codeql-java-maven.yml](/.github/workflows/codeql-java-maven.yml)  
* :package: **Dependabot configuration:** See the "Java Maven" section in [/.github/dependabot.yml](/.github/dependabot.yml)

Java and Maven are both supported "out of the box" by GHAS and one can normally just use the default CodeQL setup and get the desired results.
The above CodeQL workflow is provided to show how a advanced configuration would look like.

As Maven uses `pom.xml` (aka "**P**roject **O**bject **M**odel" file) which serves as manifest for Maven project, Dependabot will be able to detect the dependencies and both create security alerts and manage automatic dependency updates.
