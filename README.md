# LotJPackages
## AutoResearcher:  
Will read your skills from PRACTICE and research them all up for you. To install, put the following into your mudlet input bar and hit enter:
```
lua local a="https://raw.githubusercontent.com/demonnic/LotJPackages/master/AutoResearch/LotjAutoresearcher.xml"function d(b,c)if not c:find("Autoresearch",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/Autoresearch.xml"or"/Autoresearch.zip"),a)
```

### Usage (aliases)
to start autoresearching: `autoresearch`

to pause autoresearching: `pauseresearch`

to stop  autoresearching: `stopresearch`

to resume researching   : `resumeresearch`

to see what skills are left: `skillsLeft`

### Warnings
This is totally automated. Don't walk away from this without setting your botting flag or pausing it.

