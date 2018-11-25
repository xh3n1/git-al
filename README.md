# git 🇦🇱

## Çfarë është git?

Git është një Sistem i Kontrollit të Versioneve i decentralizuar, i cili është Open Source dhe lejon zhvilluesit, dizajnerat etj të ruajnë dhe gjurmojnë çdo ndryshim të kodit, skedarëve etj në një mënyrë kronologjike dhe të mundëson të rikthehesh në faza të mëparshme. Ky sistem u mundëson përdoruesve të saj të punojnë në ekipe të mëdha, në projekte komplekse, në një mënyrë të organizuar dhe duke minimizuar konfliktet ndërmjet ndryshimeve të bëra nga përdorues të ndryshëm.

## Shkarko git

[Sharkoni](https://git-scm.com/downloads) git nga faqja zyrtare.

## Komandat e Git ndonjëherë harrohen 😏 , por disa nga komandat më të përdorura janë: 🤘

**Tregoji Git-it kush je 😈!** Konfiguro emrin dhe emailin e autorit që do të përdoret për commit-et tuaja.

Për të konfiguruar emailin tuaj globalisht në git.

<pre> git config --global user.email "myrtajxheni@gmail.com"</pre>

Për të konfiguruar emrin tuaj globalisht në git.

<pre> git config --global user.name "name" </pre>

_Shënim: Nëse dëshironi që për një repository të caktuar të përdorni një emër/email tjetër nga ai global, atëherë shkoni në direktorinë ku doni dhe përdorni të njëjtën komandë por pa --global._

Për inicializimin e një repository (depo-je).

<pre> git init </pre>

Për të shtuar skedarë te caktuar.

<pre>git add [skedari.prapashtesa] </pre>

_Shembull:_

<pre>git add App.js</pre>

Për të shtuar te gjithe skedarët qe kane ndryshuar ( e rekomanduar ).

<pre>git add .</pre>

Për të bërë "commit" ose kryer ndryshimet me një mesazh/përshkrim te caktuar.

<pre>git commit -m [Pershkrimi]</pre>

_Shembull:_

<pre>git commit -m "Shto App.js" </pre>

Për të parë statusin, cilët skedarë kanë ndryshuar, cilat janë shtuar dhe gati për commit.

<pre>git status</pre>

Për të parë historikun e commits/kryerjeve. Cdo commit/kryerje ka një numër unik , autorin etj.

<pre>git log</pre>

Për të vendosur url-në e vendodhjes së repository/depo-je remote (në server)

<pre>git remote add origin [url-depos]</pre>

_Shembull:_

<pre>git remote add origin https://github.com/xh3n1/git-al.git</pre>

Për të dërguar/aplikuar ndryshimet në repository-in/depon tonë remote.

<pre>git push origin [emri-branchit]</pre>

_Shembull:_

<pre>git push origin master</pre>

Për të marrë ndryshimet nga remote lokalisht.

<pre>git pull</pre>

Për të krijuar një branch të ri.

<pre>git branch [emri-branchit]</pre>

_Shembull:_

<pre>git branch new-feature</pre>

Liston të gjitha branch-et

<pre>git branch</pre>

Për të ndryshuar branch-in ku po punoni.

<pre>git checkout [emri-branchit]</pre>

_Shembull:_

<pre>git checkout new-feature</pre>

Për të krijuar një branch të ri si dhe të kaloni në këtë branch të sapo krijuar.

<pre>git checkout -b [emri-branchit]</pre>

_Shembull:_

<pre>git checkout -b new-feature</pre>

Per te bashkuar nje branch të caktuar me branch-in kryesor master.

- _Ne fillim kalojmë në branch-in kryesor master_
   <pre>git checkout master</pre>
- _Pastaj bashkojmë branch-in tonë me branch-in kryesor_
  <pre>git merge [emri-branchit]</pre>
  _Shembull:_
  <pre>git merge new-feature</pre>

Fshin një branch të caktuar.

<pre>git branch -d [emri-branchit]</pre>

_Shembull:_

<pre>git branch -d new-feature</pre>

Për të klonuar një repository/depo me protokollin https:

<pre>git clone https://[url-depos]</pre>

_Shembull_

<pre>git clone https://github.com/xh3n1/git-al.git</pre>

Për të klonuar një repository/depo me protokollin SSH

<pre>git clone git@[url-depos]</pre>

_Shembull_

<pre>git clone git@github.com:xh3n1/git-al.git</pre>

Ndryshon URL-në e një repository/depoje remote.

<pre>git remote set-url orgin [url-depos] </pre>

_Shembull:_

<pre>git remote set-url orgin https://github.com/xh3n1/git-al.git </pre>

Listo URL-të e një repository/depoje remote.

<pre>git remote -v</pre>

Për të fshirë commit-in e fundit

<pre> git reset --hard HEAD~1 </pre>

## Mungon ndonjë komandë? Kam bërë ndonjë gabim? 😮

Krijo një Pull Request! Sigurisht që përmirësimet si dhe sugjerimet tuaja janë mëse të mirëpritura. 😃😃😃

![git-logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)
