



Haa, waan ku hadli karaa Af-Soomaali. 😊

Maxaad iga rabtaa inaan kaa caawiyo maanta? Waxaad i weydiin kartaa su'aalo ku saabsan waxbarasho, tiknoolajiyad, caafimaad guud, safar, shaqo, ama arrin kasta oo kale.


Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   submissions/SADAKH-A/assignment_1/research.md

Farriintaas waxay ka timid Git, waxayna kuu sheegaysaa in faylkan la beddelay laakiin aan weli lagu darin commit-ka:

modified: submissions/SADAKH-A/assignment_1/research.md
Haddii aad rabto inaad ku darto isbeddelka commit-ka:

git add submissions/SADAKH-A/assignment_1/research.md
git commit -m "Update research.md"
Haddii aad rabto inaad aragto waxa isbeddelay:

git diff submissions/SADAKH-A/assignment_1/research.md
Haddii aad rabto inaad iska tuurto isbeddelka oo aad ku noqoto nuqulkii ugu dambeeyay ee commit-ka:

git restore submissions/SADAKH-A/assignment_1/research.md
Sidoo kale haddii aad rabto inaad aragto dhammaan xaaladda repository-ga:

git status
Haddii aad i soo dirto natiijada git status, waxaan kuu sheegi karaa tallaabada xigta ee saxda ah.


Haddii aad ula jeeddo background-ka VS Code, waxaa jira laba siyaabood:

1. Bedel Theme-ka (ugu fudud)
Theme-ku wuxuu beddelaa background-ka editor-ka.

Ctrl + K kadib Ctrl + T

Dooro theme sida:

Dark+

Monokai

Tokyo Night

Dracula

One Dark Pro

2. Gacanta ku beddel Background Color
Fur Settings (JSON):

Ctrl + Shift + P → Preferences: Open Settings (JSON)

Ku dar:

"workbench.colorCustomizations": {
    "editor.background": "#1e1e1e"
}
Tusaalooyin midabo:

"editor.background": "#000000"   // Black
"editor.background": "#282C34"   // One Dark
"editor.background": "#1A1B26"   // Tokyo Night
3. Sawir Background ah
VS Code si rasmi ah uma taageerto sawir background ah, laakiin waxaad rakibi kartaa extensions sida:

Background

Custom CSS and JS Loader

Kuwaas waxay kuu oggolaanayaan inaad sawir ka dhigato background-ka editor-ka.

Ma rabtaa:

Midab background ah?

Mise sawir (image) background ah?


wxa un pahnaa extesions in kusoo kordhiyo

Haddii aad rabto extensions qurxiya VS Code oo ka dhigaya muuqaalka iyo isticmaalka mid fiican, kuwan ayaa aad loo isticmaalaa:

🎨 Themes (Midabyo & Background muuqaal fiican)
One Dark Pro

Tokyo Night

Dracula Official

Material Theme

📁 Icons (Astaamo qurux badan)
Material Icon Theme

vscode-icons

💻 Coding-ka
Prettier – si otomaatig ah u hagaajiya code-ka.

Error Lens – khaladaadka si cad ayuu u muujiyaa.

GitLens – Git awood badan.

Live Server – web pages si toos ah u fur.

🤖 AI
GitHub Copilot

Continue

Haddii aad tahay Data Science / Machine Learning
Python Extension

Jupyter

Pylance

Isku darka ugu fiican ee aan kugula talin lahaa:

Material Theme ama Tokyo Night

Material Icon Theme

Prettier

Error Lens

GitLens

Python + Pylance + Jupyter

VS Code-kaagu ma wuxuu u badan yahay Web Development mise Data Science/Machine Learning? Waxaan markaas kuu soo xuli karaa extensions-ka ugu habboon.


wxaa raba extension qoralka hadii bilawdo dhamystira

Haa, waxaad u baahan tahay extension-ka code autocomplete ama AI code completion.

Kuwa ugu fiican waa:

1. GitHub Copilot ⭐
Markaad bilowdo qorista, si otomaatig ah ayuu kuu dhammeystiraa code-ka.

Wuxuu qori karaa functions, classes, iyo xitaa faylal dhan.

Taageeraa Python, JavaScript, Java, C++, iwm.

2. Continue
Bilaash badan marka loo eego Copilot.

Waxay ku xirmi kartaa AI models kala duwan.

Waxay kaa caawisaa dhammeystirka iyo sharaxaadda code-ka.

3. Codeium (Windsurf Plugin)
Bilaash ah isticmaalka shaqsiga.

Waxay bixisaa autocomplete degdeg ah.

Aad bay ugu fiican tahay Python iyo Web Development.

Python-ka gaar ahaan
Hubi inaad sidoo kale rakibto:

Python Extension

Pylance

Pylance wuxuu ku siinayaa autocomplete caadi ah, tusaale:

import pandas as pd

pd.rea
wuxuu kuu soo jeedinayaa:

pd.read_csv()
Haddii aad rabto kan ugu awoodda badan, rakib GitHub Copilot. Haddii aad rabto bilaash, rakib Codeium.


   new file:   submissions/SADAKH-A/assignment_1/research.md

PS C:\Users\ibra cade\Desktop\sadaq\ds-ml-bootcamp>   waxa rabaa file sidadas cml  in ku darsado maxaa samyna

Haddii aad rabto inaad fayl cusub ku darto Git, oo uu kuu muuqdo sidan:

new file: submissions/SADAKH-A/assignment_1/research.md
waxaad sameysay tallaabada saxda ah ee git add.

Hadda waxaa kuu haray:

git commit -m "feat: add assignment_1 research"
Laakiin adiga hore waxaa kuu soo baxay:

Author identity unknown
Marka hore dejiso magacaaga iyo email-kaaga:

git config --global user.name "Sadak Abdalla"
git config --global user.email "emailkaaga@gmail.com"
Kadib:

git commit -m "feat: add assignment_1 research"
Markuu commit-ku guuleysto, u dir GitHub:

git push origin main
Ama haddii branch-kaagu yahay master:

git push origin master
Haddii aad rabto inaad abuurto fayl kale oo cusub sida research.md, waxaad ku samayn kartaa VS Code:

Right-click folder-ka assignment_1

New File

Qor magaca faylka, tusaale:

notes.md
Kadib:

git add .
git commit -m "add notes file"
git push
Ii soo dir natiijada amarkan:

git config --global --list
ama khaladka commit-ka oo dhan, markaas waxaan kuu sheegi doonaa tallaabada xigta.


Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ibra cade@DESKTOP-TFAR79H.(none)') waxaa soo baxay

Taasi waa dhibaatada. Git ma yaqaan magacaaga iyo email-kaaga, sidaas darteed commit ma sameyn karo.

Ku qor labadan amar terminal-ka (email-kaaga GitHub isticmaal haddii aad leedahay):

git config --global user.name "Sadak Abdalla"
git config --global user.email "emailkaaga@gmail.com"
Tusaale:

git config --global user.name "Sadak Abdalla"
git config --global user.email "sadakabdalla123@gmail.com"
Kadib hubi:

git config --global --list
Waa inuu ku tusaa wax la mid ah:

user.name=Sadak Abdalla
user.email=sadakabdalla123@gmail.com
Markaas dib u samee commit-ka:

git commit -m "feat: assignment_1"
Haddii aad garan weydo email-ka GitHub-kaaga:

Gal GitHub.

Guji profile-kaaga → Settings.

Emails.

Isticmaal email-ka halkaas ku qoran.

Ama ii soo dir email-ka aad GitHub ku gashay (ha soo dirin password), waxaan kuu sheegi doonaa amarka saxda ah.


PS C:\Users\ibra cade\Desktop\sadaq\ds-ml-bootcamp> git config --global user.name "Sadak Abdalla"
>> git config --global user.email "sadakabdalla512@gmail.com          >> git config --global --list
>>  wax jawab ah kama hayo

Waxaan arkaa dhibaatada. Waxaad u muuqataa inaad xiritaanka laba-geesoodka (") illoowday, markaa PowerShell wuxuu galay qaab sugitaan ah (>>).

Waxaad qortay wax la mid ah:

git config --global user.email "sadakabdalla512@gmail.com
Waxaa ka maqan " dhammaadka email-ka.

Samee sidan:
Marka hore riix:

Ctrl + C
si aad uga baxdo >>.

Kadib si gooni-gooni ah u qor:

git config --global user.name "Sadak Abdalla"
Kadib:

git config --global user.email "sadakabdalla512@gmail.com"
Kadib hubi:

git config --global --list
Waa inuu kuu soo saaraa wax la mid ah:

user.name=Sadak Abdalla
user.email=sadakabdalla512@gmail.com
Markaas samee:

git commit -m "feat: assignment_1"
Ii soo dir waxa kuu soo baxa markaad qorto:

git config --global --list
ama haddii >> wali kuu muuqdo.


🎉 Waa guul!

Farriintan:

To https://github.com/SADAKH-A/ds-ml-bootcamp.git
   e091ad5..4107b06  main -> main
waxay ka dhigan tahay:

✅ Commit-kaaga waa la sameeyay.

✅ GitHub ayaa lagu push gareeyay.

✅ Faylka research.md hadda wuxuu ku jiraa repository-gaaga GitHub.

✅ Assignment-ka waa la gudbiyay dhinaca Git.

Haddii aad rabto inaad hubiso, gal repository-gaaga GitHub oo eeg:

submissions/
└── SADAKH-A/
    └── assignment_1/
Waxaad halkaas ka arki doontaa faylka aad dirtay.

Haddii hadafkaagu yahay in research.md loo beddelo README.md, samee:

Rename garee faylka gudaha VS Code.

Kadib:

git add .
git commit -m "rename research.md to README.md"
git push
Laakiin haddii assignment-ku uu si gaar ah u dalbanayay research.md, ha beddelin magaca ilaa aad hubiso shuruudaha assignment-ka.

Hambalyo, push-kii ugu horreeyay si sax ah ayuu ku dhammaaday! 🚀👏


submissions/
└── SADAKH-A/
    └── assignment_1/
        ├── README.md file kas in ku daraa rabaaa

Haa, haddii aad rabto inaad ku darto fayl cusub oo la yiraahdo README.md gudaha:

submissions/
└── SADAKH-A/
    └── assignment_1/
samee sidan:

VS Code
Fur folder-ka assignment_1.

Right-click → New File.

Qor magaca:

README.md
Ku qor waxyaabaha aad rabto gudaha faylka, kadib Save.

Markaas Git ku dar:

git add submissions/SADAKH-A/assignment_1/README.md
git commit -m "add README.md"
git push
Qaabka folder-kaagu wuxuu noqon doonaa:

submissions/
└── SADAKH-A/
    └── assignment_1/
        ├── research.md
        └── README.md
Haddii aad rabto inaad beddesho research.md oo aad ka dhigto README.md (hal fayl oo keliya), markaa rename garee. Haddii aad rabto labadaba inay jiraan, samee New File oo la yiraahdo README.md.

Ma rabtaa:

research.md + README.md (labaduba ha jiraan), mise

research.md → README.md (magaca ha is beddelo)?


fatal: pathspec 'submissions/SADAKH-A/assignment_1/README.md' did not match any files

Haa, haddii aad rabto inuu noqdo sidan:

submissions/
└── SADAKH-A/
    └── assignment_1/
        ├── research.md
        ├── notes.md
        └── README.md
marka hore waa inaad abuurtaa faylka README.md.

VS Code
Fur folder-ka assignment_1.

Right-click → New File.

Qor magaca:

README.md
Save garee.

Kadib terminal-ka qor:

git add submissions/SADAKH-A/assignment_1/README.md
git commit -m "add README.md"
git push
Ama si fudud:

git add .
git commit -m "add README.md"
git push
Haddii README.md aad hore u abuurtay laakiin Git uusan arkin, qor:

git status
oo ii soo dir natiijada. Waxaan markaas kuu sheegi doonaa tallaabada saxda ah.


submissions/SADAKH-A/README.md : The term 
'submissions/SADAKH-A/README.md' is not recognized as the name of a 
cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the 
path is correct and try again.
At line:1 char:1
+ submissions/SADAKH-A/README.md
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (submissions/SADAKH-A/ 
   README.md:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

Waxaad qalad u qortay magaca faylka sida amar (command).

Waxaad qortay:

submissions/SADAKH-A/README.md
PowerShell wuxuu u maleeyay inaad rabto inaad socodsiiso amar la yiraahdo submissions/SADAKH-A/README.md, sidaas darteed ayuu khaladka bixiyay.

Si aad u abuurto README.md:

Habka ugu fudud (VS Code)
Folder-ka SADAKH-A ama assignment_1 fur.

Right-click → New File.

Magaca geli:

README.md
Riix Enter.

Ama PowerShell:

Haddii aad rabto README.md gudaha SADAKH-A:

New-Item -Path "submissions/SADAKH-A/README.md" -ItemType File
Haddii aad rabto README.md gudaha assignment_1:

New-Item -Path "submissions/SADAKH-A/assignment_1/README.md" -ItemType File
Kadib hubi:

git status
Oo ii soo dir natiijada git status si aan u xaqiijiyo in README.md la abuuray meesha aad rabto.


Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   submissions/SADAKH-A/README.md

Waa sax! 🎉

Farriintan:

Changes to be committed:
  new file: submissions/SADAKH-A/README.md
waxay ka dhigan tahay:

✅ README.md waa la abuuray.

✅ Git waa la siiyay (git add waa la sameeyay).

⏳ Waxa haray oo keliya commit iyo push.

Qor:

git commit -m "add README.md"
Kadib:

git push origin main
Markaas faylka README.md wuxuu ka muuqan doonaa GitHub-kaaga gudaha:

submissions/
└── SADAKH-A/
    ├── README.md
    └── assignment_1/
        ├── research.md
        └── notes.md
Haddii aad rabto in README.md uu ku jiro assignment_1 halkii uu ka ahaan lahaa SADAKH-A, ii sheeg. Hadda wuxuu ku yaal:

submissions/SADAKH-A/README.md
ee ma aha:

submissions/SADAKH-A/assignment_1/README.md

qoral enlglish o REAM.md aa ku qorto dignin ii samay copy right cml

Waxaad ku qori kartaa README.md qoraal digniin/copyright ah sida kan:

README
Copyright Notice
© 2026 Sadak Abdalla. All Rights Reserved.

This repository and its contents are provided for educational and learning purposes only.

Unauthorized copying, distribution, modification, or use of the materials contained in this repository without permission from the author is prohibited.

If you would like to use any part of this work, please contact the author for permission.

Created by: Sadak Abdalla
