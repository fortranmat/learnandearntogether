# SOlution To Few Errors
## Android studio Error 16-04-2022 Solution 16-04-2022
Error<br/>
When Running Java in android<br/>
```
FAILURE: Build failed with an exception.

* Where:
Initialization script '/tmp/JavaBasic_main__.gradle' line: 42

* What went wrong:
A problem occurred configuring project ':app'.
> Could not create task ':app:JavaBasic.main()'.
   > SourceSet with name 'test' not found.
```
Solution Ref from [stack](https://stackoverflow.com/questions/57734823/android-studio-refuses-to-run-main)
Actual Works
```
Projects Mode<br/>
.idea<br/>
Open gradle.xml<br/>
Add the following line before </GradleProjectSettings/>
<option name="delegatedBuild" value="false" />
```
