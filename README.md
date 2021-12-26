[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=MathieuSoysal_Java-Maven-library-template&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=MathieuSoysal_Java-Maven-library-template)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=MathieuSoysal_Java-Maven-library-template&metric=coverage)](https://sonarcloud.io/summary/new_code?id=MathieuSoysal_Java-Maven-library-template)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=MathieuSoysal_Java-Maven-library-template&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=MathieuSoysal_Java-Maven-library-template)
![GitHub Actions](https://github.com/MathieuSoysal/Java-Maven-library-template/workflows/Java%20CI%20with%20Maven/badge.svg)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md) 
[![Javadoc](https://img.shields.io/badge/JavaDoc-Online-green)](https://mathieusoysal.github.io/Java-Maven-library-template/javadoc/)


# <img src="https://cdn.iconscout.com/icon/free/png-512/java-43-569305.png" width="100"> Java Maven Library Template [![GitHub](https://img.shields.io/badge/license-Apache%202.0%20License-green)](LICENSE)

Template to easily create a Java Maven library and publish it automatically on GitHub Package and Maven Central, the publication is automated via the repo versions.

## Use template

To use this template, you just need to click on "Use this template" on the main page of this repository, or you can copy/paste this repository.

## Requirements
- [ ] [Create an account on Sonatype](https://issues.sonatype.org/secure/Signup!default.jspa)
- [ ] [Create a JIRA ticket on Sonatype to approve your groupId (io.github.YOUR-GITHUB-USERNAME)](https://issues.sonatype.org/secure/CreateIssue.jspa?issuetype=21&pid=10134)
- [ ] [Generate a gpg key and distribute the public key to a keyserver](https://central.sonatype.org/publish/requirements/gpg/)

## Template configurations :

- [ ] **Fix pom.xml**
  - *To guide you, a FIXME tag has been added to all lines to be edited.*
- [ ] **Config SonarCloud**
  - To configure SonarCloud for your project you must go to https://sonacloud.io
  - Replace the file at /.github/workflows/sonar.yml with your own yaml file at https://sonacloud.io and if your Java project is not on Java 11 edit that yaml file.
- [ ] **Create your GitHub secrets on your repository**
  - *NEXUS_USERNAME* with your username used on Sonatype
  - *NEXUS_PASSWORD* with your password used on SOnatype
  - *GPG_PRIVATE_KEY* with the private key of your generated pgp key
  - *GPG_PASSPHRASE* with the passphrase of your gpg key
- [ ] **Activate the JavaDoc GitHub page**
  - *To enable the JavaDoc GitHub Page, you need to enable the GitHub page in your repository settings for the javadoc branch.*

## Badges

Don't forget to add your own SonarCloud badges to your readme 😉
 - to get your maven-central badge : https://shields.io/category/platform-support
 - to get your JavaDoc Badge : 
```Markdown
  [![Javadoc](https://img.shields.io/badge/JavaDoc-Online-green)](https://<github-username>.github.io/<github-repo>/javadoc/)
```
On the link of JavaDoc badge, replace  `<github-username>` by your GitHub username, `<github-repo>` by the name of your GitHub repository.
