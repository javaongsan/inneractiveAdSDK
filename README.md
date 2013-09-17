inneractiveAdSDK
================

Adding Nokia inneractiveAdSDK to Andriod Studio



  1. Put the jar into the libs folder, create lib folder if folder is missing.
  2. In Andriod Studio, right click it and hit 'Add as library'
  3. In the build.gradle file add the following so that your dependencies closure has (note there are two build.gradle files at least, dont use the root one use the one in your project scope).:
    dependencies {compile fileTree(dir: 'libs', include: '*.jar')}
  4. Do a clean build, navigated in a terminal to the root folder and typed ./gradlew clean.
  5. In Andriod Studio, Do a rebuild.
