# AoikWinWhich-Xtend
[AoikWinWhich](https://github.com/AoiKuiyuyou/AoikWinWhich) written in Xtend.

Xtend: 2.7

## Contents
- [How to install](#how-to-install)
- [How to use](#how-to-use)

## How to install
Clone the repo to local.

## How to use
Xtend's compiler is integrated with Eclipse.

Download Xtend-integrated Eclipse from [here](http://www.eclipse.org/xtend/download.html).

Unzip the downloaded file.

Run Eclipse in it.

Create a Java project. Copy files in AoikWinWhich-Xtend's src dir to the Java
 project's src dir.

The program entry file is [src/aoikwinwhich/AoikWinWhich.xtend](/src/aoikwinwhich/AoikWinWhich.xtend).

Use Eclipse to compile and run.

Use Java to run (after compiled in Eclipse).
```
SET ECLIPSE_DIR=<put your value here>
SET ECLIPSE_PROJECT_DIR=<put your value here>
SET CLASSPATH=%ECLIPSE_PROJECT_DIR%\bin
SET CLASSPATH=%CLASSPATH%;%ECLIPSE_DIR%\plugins\org.eclipse.xtext.xbase.lib_2.7.0.v201409021032.jar
SET CLASSPATH=%CLASSPATH%;%ECLIPSE_DIR%\plugins\com.google.guava_15.0.0.v201403281430.jar

java -cp "%CLASSPATH%" aoikwinwhich.AoikWinWhich
```
- **ECLIPSE_DIR** is where the Xtend-integrated Eclipse is located.
- **ECLIPSE_PROJECT_DIR** is where the Eclipse project you have created is located.
- **%ECLIPSE_PROJECT_DIR%\bin** is where the result **.class** files after compilation are located.
- The two jar files are Xtend's dependency libs.

See [here](https://github.com/AoiKuiyuyou/AoikWinWhich#how-to-use) for more usage and [AoikWinWhich](https://github.com/AoiKuiyuyou/AoikWinWhich) for more info.
