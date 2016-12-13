###Vad är ett källkodhantering###
systemet hjälper användaren att hantera dess filer och spara dem i olika versioner så att man kan effektivt spåra de förändringar man gör i filerna och sedan gå tillbaka o kolla i "historiken" vad man har ändrat.
detta ger även möjligheten att folk kan arbeta tillsammans utan några risker att man skriver över någon annans arbete. det vill säga om man ska göra en hemsida och man är ungefär 4 personer och 2st arbetar i css koden samtidigt, vanligt vis så skulle man kopiera bådas o lägga in i ett nytt css, men då skulle det poppa upp många fel, men med källkodshantering så kan båda arbeta samtidigt och spara utan att det uppstår sådan risker.

###Vad är Git och vilken typ av system är det?###
git skapades 2005 för att hanera källkod till linux, skapades av Linus Torvald.
Git är ett distrubuerade versionshanteringssystem. det är uppbyggt på de sättet så att de passar arbetsmetodiken i stora öpnna källkodsprojekt. det är därför det finns program för att man ska skicka och ta emot ändringar i en form av "patcher" genom din e-post. de loggar även vem som arbetar under vilken tid utan att behöva administrera register över den utvecklare.

###Hur installerar man Git###
[https://git-for-windows.github.io/](https://git-for-windows.github.io/) börja med att installera detta.
 efter att du har installerat detta, så får du 3 olika git, öppna upp "git bash" och skriv in följande två saker, 
 $ git config --global user.name "Alex Wannesian" 
 $ git config --global user.email "nkpit14axwa@realgymnasiet.se"
 
 ibland kan de vara så att "$" skrivs av sig själv så att du ej behöver skriva det.
 
 
 ###Vanligaste kommandon###
 Git init  = Detta skapar repo i nuvarande katalog
 Git status = se nuvarande status
 Git add file.txt (-all/*) = "stage a file" lägg till fil som ska commitas
 Git commit -m "medelande" = commita de "stageade" filerna
 Git branch [namn]
 Git checkout [gren-namn]
 Git Merge [gren-namn] = stå i den grenen du vill ska mergas till