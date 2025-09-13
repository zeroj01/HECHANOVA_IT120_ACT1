

JACK3@DESKTOP-PKE19CC MINGW64 ~
$ cd desktop

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop
$ mkdir Hechanova_IT120_act1

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop
$ cd Hechanova_IT120_act1

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1
$ git init
Initialized empty Git repository in C:/Users/JACK3/Desktop/Hechanova_IT120_act1/
.git/

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "FirstName: Jason" > Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Middle Name: Piencenaves>> Profile.txt
>
> echo "LastName: Hechanova>> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Middle Name: Piencenaves>> Profile.txt
> echo "Middle Name: Piencenaves">> Profile.txt
> echo "Middle Name: Piencenaves">> Profile.txt
> echo "Middle Name: Piencenaves">> Profile.txt
> echo "Middle Name: Piencenaves>> Profile.txt
echo "Middle Name: Piencenaves">> Profile.txt
echo "Middle Name: Piencenaves">> Profile.txt
echo "Middle Name: Piencenaves">> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Middle Name: Piencenaves">> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Gender: Male" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Age: 22" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Contacts: 09709227782">> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Elementary School: Magallanes Central Elementary School" > Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Year Graduated: 2014-2015" >> Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "High School: Magallanes National High School" >> Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Year Graduated: 2019-2020" >> Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "Language: Bisaya,Tagalog and English" > Background.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "" > Readme.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "import os" > Test.py

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ echo "print('Hello, World')" >> Test.py

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ git add .
warning: in the working copy of 'Background.txt', LF will be replaced by CRLF th
e next time Git touches it
warning: in the working copy of 'Education.txt', LF will be replaced by CRLF the
 next time Git touches it
warning: in the working copy of 'Profile.txt', LF will be replaced by CRLF the n
ext time Git touches it
warning: in the working copy of 'Readme.txt', LF will be replaced by CRLF the ne
xt time Git touches it
warning: in the working copy of 'Test.py', LF will be replaced by CRLF the next
time Git touches it

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ git commit -m "Initial commit with main contents"
[master (root-commit) 306f3a9] Initial commit with main contents
 5 files changed, 24 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ git checkout -b Hechanova_B1
Switched to a new branch 'Hechanova_B1'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ echo "Birth of Place: Cabadbaran Hospital" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ echo "Religion: Roman Catholic" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ echo "Father’s Name: Hector Hechanova" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ echo "Occupation: Company Worker" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ echo "Mother’s Name: Rizz Hechanova" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ echo "Occupation: House Wife" >> Profile.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ git add Profile.txt
warning: in the working copy of 'Profile.txt', LF will be replaced by CRLF the n
ext time Git touches it

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ git commit -m "Added extra details in Profile.txt"
[Hechanova_B1 b4a84b9] Added extra details in Profile.txt
 1 file changed, 6 insertions(+)

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ git checkout main
error: pathspec 'main' did not match any file(s) known to git

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B1)
$ git checkout master
Switched to branch 'master'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ git checkout -b Hechanova_B2
Switched to a new branch 'Hechanova_B2'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B2)
$ echo "College: Caraga State University Cabadbaran Campus" >> Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B2)
$ echo "Program: BSInfoTech" >> Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B2)
$ echo "Year Level: Third Year" >> Education.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B2)
$ git add Education.txt
warning: in the working copy of 'Education.txt', LF will be replaced by CRLF the
 next time Git touches it

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B2)
$ git commit -m "Added extra details in Education.txt"
[Hechanova_B2 99fb70a] Added extra details in Education.txt
 1 file changed, 3 insertions(+)

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B2)
$ git checkout master
Switched to branch 'master'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ git checkout -b Hechanova_B3
Switched to a new branch 'Hechanova_B3'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B3)
$ echo "Person to be Contact: 09509263605/Mother" >> Background.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B3)
$ echo "Address: Magallanes ADN" >> Background.txt

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B3)
$ git rm Test.py
rm 'Test.py'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B3)
$ git add Background.txt
warning: in the working copy of 'Background.txt', LF will be replaced by CRLF th
e next time Git touches it

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B3)
$ git commit -m "Updated Background.txt and removed Test.py"
[Hechanova_B3 b778bc8] Updated Background.txt and removed Test.py
 2 files changed, 2 insertions(+), 2 deletions(-)
 delete mode 100644 Test.py

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B3)
$ git checkout master
Switched to branch 'master'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (master)
$ git checkout -b Hechanova_B4
Switched to a new branch 'Hechanova_B4'

JACK3@DESKTOP-PKE19CC MINGW64 ~/desktop/Hechanova_IT120_act1 (Hechanova_B4)
$ notepad Readme.txt
