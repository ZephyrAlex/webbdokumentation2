##Tutorial##


Först o främst bör du veta vad npm är, de kan du läsa om här -> https://en.wikipedia.org/wiki/Npm_(software).

efter att du har läst och förstått de kan du börja ladda ner nodejs från deras sida -> https://nodejs.org/en/

efter att du har laddat ner kan du göra 2 mappar vart som helst på din dator, där ena kan bli kallad för node och den andra för babel   ![alt tag](https://gyazo.com/4b6e7dbe97d398d104744a7fbd40e505.png)


efter att ha skapat båda mapparna och installerat node och lagt in de i node mappen går du in på Babel mappen.
när du är inne i babel mappen ska du gå upp till adressen och skriva in cmd ![alt tag](https://gyazo.com/25b1b2f7a374f2499e0a67731bf84802.png)

efter att ha skrivit in det och tryck enter så ska du få upp command systemet och de ska se ut så här ![alt tag](https://gyazo.com/0fc69a829e8f4eab80674a9413d54e0c.png)

skriv in npm -v för att se om du har fått npm inlagd i din dator. om du inte har fått de så kommer det komma upp error meddelande.

nåväl när du har det hela så ska du börja med att skriva npm init som command och låta den ladda filerna, efter det ska du skriva in npm install --save-dev babel-cli babel preset-latest efter att du har fixat allt detta ska du skappa två mappar i babel mappen där de två mappparna kallas för "src" och "lib" ![alt tag](https://gyazo.com/50e8d33b337e9d7bf9f10bb6d27120ba.png)

när du är klar så har du en package.json fil som du ska gå in på. där ska du lägga till så att din text ser ut så här
![alt tag](https://gyazo.com/72ad1fdb4617f2e699521b72fcf8022f.png)

i src mappen ska du göra en js fil som kallas för Test, och i de ska du skriva in [1, 2, 3].map(n => n + 1);
![alt tag](https://gyazo.com/4b4eb34aaf1630c0c9447cfdc931b138.png)

nåväl när du har skrivit det går du tillbaka till cmd, och skriver npm run build.
har du gjort de rätt så ska du få i din lib mapp en Test.js fil där du får svaret till de du skrivit i src mappen.
![alt tag](https://gyazo.com/0a64da64bc5f25e1ac3d80c30686c2cc.png)