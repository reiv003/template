# Template til skoleprosjekter

## Sett opp prosjektet lokalt

npm install (husk å endre navn på pakken)

## Sette opp git og publiser til GitHub

git init  
(lag initial commit)  
git remote add origin https://brukernavn@github.com/brukernavn/reponavn.git  
(lag repo først på github direkte, eller publiser via vs code. remote må da fjernes og legges til den over med git remote rm origin)  

## Publiser til Netlify

npm run build  
npm run preview  
(genererer dist-mappe)  

Velg deploy fra GitHub på Netlify  

kjør npm run build hver gang en endring er committed for å oppdatere nettsiden.  
