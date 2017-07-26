AEM Quick Tricks
========

I will use this repo to add any relevant information regarding AEM for Esri.com

## How to start AEM from the terminal

`$ sudo java -jar -Xms1024m -Xmx2048m -XX:MaxPermSize=1024m aem-author-4502.jar `

## How to run a clean start from the terminal

`$ sudo mvn clean install -P autoInstallPackage `

## Full install command

`$ sudo mvn clean install -P autoInstallAssets -P autoInstallContent -P autoDeploy -P autoInstallPackage `

# Git commands

## Git hard Reset

`$ reset --hard origin/master `

## Git find branch differences

`$ git diff <branch-to-compare> `

## Git see log with time stamp

`$ git log --graph --abbrev-commit --decorate --format=format:"%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)" --all`

## Git see configurations

`$ git config -l `