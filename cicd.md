# 🍍Android App CI/CD FASTLANE
## 🔯REquired Tools / Accounts
|Tools|Accounts|Optional|
|---|---|---|
|[Fastlane](https://fastlane.tools/) (Windows/ Ubuntu) |[GitHUb]()--Vesion Control |[Admob]()|
|[Android Studio]() |[Play console]()--Json Key for fastlane to authorize get upload| |
| |[Firebase]()--services json file | |

### ✳️STEPS
#### 🔯STUDIO GITHUB Integration
| Github | Android Studio |
|---|---|
|:heavy_check_mark: LOgin Github web :heavy_check_mark: [goto settings->Developer settings->Personnal access Token](https://github.com/settings/tokens) Generate New Token<br/> :heavy_check_mark:enter name<br/> :heavy_check_mark:choose date (normally 30days)<br/> :heavy_check_mark:select REPO, ADMIN.ORG, GIST 3 boxes<br/>:heavy_check_mark:copy that token it will not available next time only option is create another token<br/>|:heavy_check_mark:App menu bar click File-->SEttings-->VersionControl-->Github<br/> :heavy_check_mark: select + sign LOhin With Token<br/> :heavy_check_mark: JUst add the Token Copied <br/>|
#### 🔯From Studio To GitHUb
|Android Studio| GItHub|
|---|---|
|OPen android app<br/>Menu bar-->VCS-->SHARE project on github-->OPTIONAL ✅if private ☑️share<br/>Enter commit message ➡️click add<br/> 😸Bottom will show sucessfuly shared Click that link or open github| :heavy_check_mark: github goto that repo all studio files will be there |
|:heavy_check_mark:Change any file <br/>:heavy_check_mark:click commit in left side bar<br/> ✅add commit message<br/> ✔️commit and PUSH<br/>Push<br/>|just referesh You will see commit message in repo|
|Also you can commit and Push via <br/>Menu-->Git-->Commit<br/>Menu-->Git-->Push<br/>|Just refresh github repo|

#### 🔯From Github To Studio

|GitHUb|Android Studio|
|---|---|
|:heavy_check_mark:edit any file in github save<br/>✅ specify commit message and description<br/>:heavy_check_mark:press commit changes<br/>|✔️Menu-->Git-->Update project <br/>:heavy_check_mark: This will update incoming changes<br/>:heavy_check_mark:also menu-->git-->Pull<br/> :x:menu-->git-->fetch WIll not work<br/>|

#### 🔯Want TO REvert any Commit
|GitHUb|AndroidStudio|
|---|---|
|:heavy_check_mark:click commits<br/>:heavy_check_mark:choose any commit ```<>``` as yoy wish<br/>:heavy_check_mark: THen click git tree enter branch name in Find or create branch Then click<br/>:heavy_check_mark:click git branches <br/>:heavy_check_mark: select 🔄again select 🔄 choose 🔽 to select perticular branch as default<br/>| :heavy_check_mark: Android -->new-->Project From Version control<br/> :heavy_check_mark: choose Github <br/> :heavy_check_mark: select Repo<br/>:heavy_check_mark: as already default branch changed so as per defualt that branch will be loaded|

#### 🔯PULL /MERGE/CHECKOUT
|Android Studio| Github|
|---|---|
|:heavy_check_mark:menu-->VCS-->Share Project on Github<br/>:heavy_check_mark:menu-->GIt-->branches/newbranch create new branch<br/>:heavy_check_mark:whatever change commit and push will goto that new branch<br/>:heavy_check_mark:create as much as branch or keep all changes in one branch<br/>:x:goto menu-->git-->choose branch--> ▶️select checkout:heavy_check_mark:Thiswill make revoke option git to VCS as fresh one<br/>:heavy_check_mark:if imported from VCS then menu-->git-->branches--> ▶️selct checkout will not revoke to vcs<br/> |:heavy_check_mark:github you will see 2 branches <br/>:heavy_check_mark:goto second branch <br/>:heavy_check_mark:create pull request<br/>:heavy_check_mark:merge pull request<br/>:heavy_check_mark:confirm merge<br/>:heavy_check_mark:OPTIONAL you can delete branch in github<br/>:x:it wont delete in local|

#### 🔯Android APP Signing
Whatever METHOD intitial Key Is Required<br/>
Studio-->Build-->Generate Signed Bundle<br/>
KeyStorePath-->CHOOSE-->Create New<br/>
in create new Keystorepath-->Enter/choose Folder Name enter file name its will combine and show path with .jks<br/>
password and confirm pasword Loveisgod0*<br/>
Then keyalias Normally key0 (if you want rename it and keep a record of it)<br/>
Password and Confirm password MUST BE SAME AS ABOVE This is a studio requirement Loveisgod0*<br/>
Enter at Least first parameter of Total 6 parameters in certificate AFTER THAT<br/>
key store password<br/>
key alias<br/>
key password<br/>
Export encrypted key for play app signing THIS IS NEW UPDATE<br/>
save /choose path for encrypted key<br/>
click next<br/>
choose or verify the aab path and select build variant<br/>
click Finish<br/>





