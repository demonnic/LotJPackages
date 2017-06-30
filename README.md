# LotJPackages
## AutoResearcher:  
Will read your skills from PRACTICE and research them all up for you. To install, put the following into your mudlet input bar and hit enter:
```
lua local a="https://github.com/demonnic/LotJPackages/raw/master/AutoResearch/LotjAutoresearcher.xml"function d(b,c)if not c:find("AutoResearcher",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/YATCO.xml"or"/YATCO.zip"),a)
```
