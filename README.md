# Aufgabe 1: Gruppenfindung
•	Bilden Sie mit 3 – 5 anderen Teilnehmern eine Gruppe.
•	Bestimmen Sie einen Gruppenmitglied als Gründer eines Repositorys
•	Der Gründer lädt alle Gruppenmitglieder und Tutoren ein

# Aufgabe 2: git 
Das der Fokus beim Arbeiten mit git liegt, müsst ihr folgende Szenarien kreieren:
	Jeder Teilnehmer …
•	muss 10 commits haben
•	muss einen Branch erstellen
•	muss einen merge pull request durchführen
•	muss einen merge conflict lösen

 # Git_MiniProjekt
Gruppenmitglieder :	Binod Aryal
					Andreas Pieczyk
					Abdurrahman Yildirim
					Lukas Nachtigal

# ********************************************************************************************************
Ziel : 			Erstellen einer Website mit 3 oder mehr links zu den Teilnehmern und ein 
				kleines Portfolio

Ergänzung :		auf jedem seiner Seite nochmal eine verlinkung zu den anderen teilnehmern sein. 

Verlinkungen:	abdul.html  andreas.html	lukas.html

Zeit :			Frietag 21.10.2022 18:00 Uhr


# Abgabe 
# Git-Miniprojekt(GMP)     Tag1:19.10.2022     Binod Aryal
In git hub.com --->neu Repository (Git_MiniProjekt) erstellt 
settings --->Collaborators --->Add people (mitarbeiter hinfügen : username,full name or email)
***********************************************************************************************
Benutzer : Binod 
#github.com --->Notification bell icon --->einladung akzeptieen. 
#oder in email:view invitation 
#nach der comfiramtion in email --->auf linke seite auf Git logo (katze) sehen wir die geklonte documents.

*********************************************************************************************
Git commands:
$ git config --global user.name        
                       unicodebinod
$ git config --global user.email       
                      binodaryal@outlook.de
$ git clone https://github.com/DonXec/Git_MiniProjeke.git     
$ pwd
/c/Users/binod
$ ls  -al         //list the datei in Folder Binod 
 Documents/
 Downloads/
 Druckumgebung@
'Eigene Dateien'@
 Favorites/
 Git_MiniProjekt/
 
 $ cd Git_MiniProjekt/       
ls  

//git pull again inorder to get changes made from andere Teilnehmer in the current project 
$ git pull          
                                        

********************************************************************
# now create neue branch binod ---inorder to work on the project individaully 
********************************************************************
$ git branch binod     //creat an new branch binod  
$ git checkout binod   //switched to branch 'binod'    
$ git branch           //list all the branches 
* binod              //* denotes =current branch binod 
  main
$ls
README.md  abdu.html  andreas.html  binod.html  index.html   
***************************************************************************
# now work on visual studio code 
nachdem Dateien Bearbeitung--form own branch in 
git status 
git add .      
git commit -m "made some changes in the Project"

 //Switch back to the main branch:,
 git checkout main

//Merge the changes from the "my-feature-branch" branch into the main branch:
git merge binod      

git push origin main
  
//now delete the featue branch binod  !!to delete the feature branch --u 001habe to be in the main branch,0
git branch -d binod  
git branch -D binod  //delete after merge 

****************************************************************
conflict ---to resolve the conflict through vim editor 
********************************************************
git pull origin main   
git status

text bearbeiten in vim 

git  add .
git commit -m " commeantar"
git push origin binod





