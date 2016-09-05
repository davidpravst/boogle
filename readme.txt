GIT komande

pwd - kje se trenutno nahajamo (folder)
cd / (greš na root)
Gremo v folder s projektom (cd ime folderja ...)
če pritisneš tabulator naredi autocomplete

Povemo, kdo smo:
git config --global user.name “David Pravst”
git config --global user.email david.pravst@gmail.com

git init (inicializacija)
git add index.html (povemo, kateri file bomo dodali)
git commit -m "Moja prva sprememba" (naredimo commit z izbranimi fajli)
git log (pregled zgodovine commitov)
git add . (doda vse fajle v folderju, tudi podfolderje)
git diff hash1 hash2 (prikaže spremembe)

git remote add origin https://github.com/davidpravst/boogle.git (dodamo lokalni projekt na github - samo prvič)
git push -u origin master

Greš v folder (npr. Desktop) in
git clone https://github.com/ssket/boogle (kloniraš remote projekt na disk)


