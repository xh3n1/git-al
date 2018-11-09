# git 🇦🇱

## Çfarë është git?
Git është një Sistem i Kontrollit të Versioneve i decentralizuar, i cili është Open Source dhe lejon zhvilluesit, dizajnerat etj të ruajnë dhe gjurmojnë çdo ndryshim të kodit, skedarëve etj në një mënyrë kronologjike dhe të mundëson të rikthehesh në faza të mëparshme. Ky sistem u mundëson përdoruesve të saj të punojnë në ekipe të mëdha, në projekte komplekse, në një mënyrë të organizuar dhe duke minimizuar konfliktet ndërmjet ndryshimeve të bëra nga përdorues të ndryshëm.


## Komandat e Git ndonjëherë harrohen 😏 , por disa nga komandat më të përdorura janë: 🤘

**Tregoji Git-it kush je 😈!** Konfiguro emrin dhe emailin e autorit që do të përdoret për commit-et tuaja.
Për të konfiguruar emailin tuaj globalisht në git.
 <pre> git config --global user.email "myrtajxheni@gmail.com"</pre>  
 Për të konfiguruar emrin tuaj globalisht në git.
<pre> git config --global user.name "name" </pre>
*Shënim: Nëse dëshironi që për një repository të caktuar të përdorni një emër/email tjetër nga ai global, atëherë shkoni në direktorinë ku doni dhe përdorni të njëjtën komandë por pa --global.*

Për inicializimin e një repository.
 <pre> git init </pre> 
Për të shtuar files (skedarët).
 <pre>git add </pre> 
Për të bërë "commit" ndryshimet me  mesazhin e caktuar. 
 <pre> git commit -m "commit message" </pre> 
Për të parë statusin, cilat file kanë ndryshuar, cilat janë shtuar dhe gati për commit.
 <pre>git status</pre> 
Për të parë historikun e commits. Cdo commit ka një numër unik , autorin etj.
 <pre>git log </pre>
Për të vendosur url-në e vendodhjes së repository remote (ne server) 
<pre>git remote add origin "repository url"</pre> 
Për të dërguar ndryshimet në remote. 
<pre>git push  origin branchname</pre>  
Për të marrë ndryshimet nga remote lokalisht.
<pre>git pull</pre> 
 Për të krijuar një branch të ri.
<pre>git branch branchname</pre> 
Liston të gjitha branch-et
<pre>git branch</pre>  
 Fshin një branch të caktuar.
<pre>git branch -d branchname</pre> 
Për të ndryshuar branch-in ku po punoni.
 <pre>git checkout branchname</pre>  
 Për të krijuar një branch të ri si dhe të kaloni në këtë branch të sapo krijuar.
<pre>git checkout -b branchname</pre>  
 Për të klonuar një repository- zëvendëso url-në me url-në e repository që doni të klononi. Nese përdorni SSH atëherë URL është në këtë formë: /git@github.com:xh3n1/git-al.git
 <pre>git clone https://github.com/xh3n1/git-al</pre>
 Ndryshon URL-në e një remote repository.  
<pre>git remote set-url </pre>

## Mungon ndonjë komandë? Kam bërë ndonjë gabim? 😮
Krijo një Pull Request! Sigurisht që përmirësimet si dhe sugjerimet tuaja janë mëse të mirëpritura. 😃😃😃

![git-logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)
 
