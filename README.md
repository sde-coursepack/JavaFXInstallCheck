# JavaFX Install Check

## Installation

This implementation of JavaFX requires JDK 21.0.5, you must install JDK 21.0.5 and JavaFX 21.0.5 in order to run it. [See class notes for installation links and guide](https://docs.google.com/document/d/18UjMUfmNpPkgt-KVVFodydJbbrBgFl5hnWi_MmSMB2I/edit?usp=sharing).

**THIS MAY NOT WORK WITH JDK 21.0.4!**

## To Run from Terminal

To run, simply do:

<pre>./gradlew run</pre>

In your terminal

## To Run from IntelliJ

To run HelloWorld.java from IntelliJ, go to modify run configurations and add the following VM Arguments:

```shell
--module-path "[PATH_TO_JAVAFX]" --add-modules javafx.controls,javafx.fxml
```

Replacing `[PATH_TO_JAVAFX]` with the path to the JavaFX **`lib`** folder on your computer (for instance, on my Windows machine, it's `C:\Program Files\JavaFX\javafx-sdk-21.0.5\lib`)

So for instance, on my machine, my VM Arguments are:

```shell
--module-path "C:\Program Files\JavaFX\javafx-sdk-21.0.5\lib" --add-modules javafx.controls,javafx.fxml
```

