[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=MathieuSoysal_Java-Maven-Project-Template&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=MathieuSoysal_Java-Maven-library-template)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=MathieuSoysal_Java-Maven-library-template&metric=coverage)](https://sonarcloud.io/summary/new_code?id=MathieuSoysal_Java-Maven-library-template)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=MathieuSoysal_Java-Maven-library-template&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=MathieuSoysal_Java-Maven-library-template)
![GitHub Actions](https://github.com/MathieuSoysal/Java-Maven-library-template/workflows/Java%20CI%20with%20Maven/badge.svg)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md) 

# <img src="https://cdn.iconscout.com/icon/free/png-512/java-43-569305.png" width="100"> Java Maven Library Template [![GitHub](https://img.shields.io/badge/license-Apache%202.0%20License-green)](LICENSE)

Template to easily create a Maven Java library and publish it automatically on GitHub Package and Maven Central, publishing is automatised via the releases on repo.

## Use template

To use this template, you just have to click on "Use this template" on the main page of this repository, or you can copy/paste this repository.

## Requirements
- [ ] [Create acount on Sonatype](https://issues.sonatype.org/secure/Signup!default.jspa)
- [ ] [Create JIRA ticket on Sonatype to aprouve your groupId (io.github.YOUR-GITHUB-USERNAME)](https://issues.sonatype.org/secure/CreateIssue.jspa?issuetype=21&pid=10134)
- [ ] [Generate a gpg key and distributing public key to a keyserver](https://central.sonatype.org/publish/requirements/gpg/)

## Template configuration :

- [ ] **Fix pom.xml**
  - *To guide you, a FIXME tag has been added to all lines to be edited.*
- [ ] **Config SonarCloud**
  - To config SonarCloud to your project you need to go on https://sonacloud.io
  - Replace the file at /.github/workflows/sonar.yml with your own yaml file at https://sonacloud.io and if your Java project is not on Java 11, edit this yaml file.
- [ ] **Create your GitHub secrets on your repository**
  - *NEXUS_USERNAME* with your username used on Sonatype
  - *NEXUS_PASSWORD* with your password used on SOnatype
  - *GPG_PRIVATE_KEY* with the private key of your generated pgp key
  - *GPG_PASSPHRASE* with the passphrase of your gpg key

## Badges

Don't forget to add your own SonarCloud badges to your readme 😉
 - to get your maven-central badge : https://shields.io/category/platform-support
