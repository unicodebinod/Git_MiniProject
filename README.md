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

# ******************************************************************************************
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
#git bash öffnen --> befehl ausführen
binod@Binod MINGW64 ~$ git config --global user.name          //username
                       unicodebinod

binod@Binod MINGW64 ~$ git config --global user.email        //user email
                      binodaryal@outlook.de

binod@Binod MINGW64 ~$ git clone https://github.com/DonXec/Git_MiniProjeke.git     
Cloning into 'Git-Miniprojekt-G4'...

binod@Binod MINGW64 ~ $ pwd
                     /c/Users/binod

binod@Binod MINGW64 ~ls  -al         //list the datei in Folder Binod 
                      
 Documents/
 Downloads/
 Druckumgebung@
'Eigene Dateien'@
 Favorites/
 Git_MiniProjekt/
 
binod@Binod MINGW64 ~$ cd Git_MiniProjekt/        //change Directory To  Git_MiniProjekt

binod@Binod MINGW64 ~/Git_MiniProjekt (main) ls   //show the datei in GMP

binod@Binod MINGW64 ~/Git_MiniProjekt (main) $ git pull          
//git pull again inorder to get changes made from andere Teilnehmer in the current project                                         

********************************************************************
# now create neue branch binod ---inorder to work on the project individaully 
********************************************************************
//creat an new branch binod
binod@Binod MINGW64 ~/Git-Miniprojekt-G4 (main)$ git branch binod        

//enter into the branch binod-----switched to branch 'binod'
binod@Binod MINGW64 ~/Git-Miniprojekt-G4 (main) $ git checkout binod       

 //list all the branches 
binod@Binod MINGW64 ~/Git_MiniProjekt (binod)$ git branch         
* binod              //* denotes =current branch binod 
  main

binod@Binod MINGW64 ~/Git-Miniprojekt-G4 (binod)$ ls
README.md  abdu.html  andreas.html  binod.html  index.html   

# nachdem beatbeiten in own branch 
git add binod.html       git commit -m "binod.html commit
git merge binod
git push -u -f origin <curentbranch>

In Gitgub: 
   Compare and pull ----create pull request---merge pul
   Delete branch
   
In Visual Studio Code:
    git checkoutmain
	git branch -d <branchname>
	git branch


