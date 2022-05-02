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
# 2-5-2022 20:46
Git Ubuntu Integration<Br/>
Git Already Installed<br/>
Go to `https://github.com/settings/emails` <br/>
Then this ` `  But No result at last<br/>
Just in terminal typed `git push` <br/>
Wow Found 

```
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

      git push --set-upstream origin main
```
So THis is the solution Bad Luck THis too failed<br/>

The actual message is
```
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/fortranmat/hugoprivatelocal.git/'
```


    

