+++
author = "Robson Cassiano"
title = "Managing JDK Installation on Linux with SDKMAN"
date = "2018-02-23"
description = "Managing JDK Installation on Linux with SDKMAN"
tags = ["java", "linux"]
+++

![SDKMAN](https://sdkman.io/assets//img/logo.png)

If you're a software developer working with Java in a Linux environment, SDKMAN is an essential tool that will simplify the process of installing and managing Java Development Kit (JDK) versions. In this article, we will explore the benefits of SDKMAN and provide basic instructions to install and configure it on your system.

## Why Use SDKMAN?

SDKMAN is a software management tool that makes it easy to install and use various JDK versions, as well as other related tools like Groovy, Kotlin, and Gradle. Here are some of the key benefits of using SDKMAN:

- **Simplicity**: SDKMAN simplifies the installation of various JDK versions with a single command. This is particularly useful if you work on different projects that require different Java versions.

- **Ease of Use**: SDKMAN has a user-friendly and easy-to-use interface. You don't need to worry about environment variables or complex settings.

- **Updates and Rollbacks**: With SDKMAN, you can easily update to the latest JDK versions or roll back to previous ones if needed.

- **Other Tools**: In addition to JDK, SDKMAN supports various other development tools, allowing you to install and manage them with the same ease.

## Installing SDKMAN

Installing SDKMAN is straightforward. Follow the steps below to set it up on your Linux system:
(It's necessary to have **zip** and **unzip** installed on your Linux Distribution)

1. Open a terminal and run the following command to download and install SDKMAN:

```shell
curl -s "https://get.sdkman.io" | bash
```
After this step, restart your linux terminal.

## Installing JDK with SDKMAN
Now that SDKMAN is installed, you can use the sdk command to install and manage various JDK versions. For example, to install the latest version of OpenJDK, run the following command:

```shell
sdk install java
```
To install a specific version of JDK, you can provide the version number, like this:

```shell
sdk install java 21-amzn
```

After installation, you can switch between JDK versions using the use command:

```shell
sdk use java 21-amzn
```
## Conclusion

SDKMAN is a powerful tool to simplify the management of different JDK versions in the Linux environment. With its user-friendly interface and simple commands, it allows software developers to save time and effort in setting up the development environment.

For more information and resources, visit the official SDKMAN website.

In this article, we've highlighted the benefits of SDKMAN and provided basic instructions for installing and configuring it. Now, you can start using SDKMAN to streamline your Java development workflow on Linux.

