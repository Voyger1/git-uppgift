# Git-uppgift – Individuell examination

## Fråga 1: Versionshantering och vanliga filer

Versionshantering betyder att man kan spara olika versioner av ett projekt och se vad som har ändrats med tiden. När jag trycker på spara i VS Code sparas ändringarna i filen på datorn, men det skapas ingen ny version i Gits historik. När jag gör en commit sparas en checkpoint av projektet som jag kan gå tillbaka och titta på senare.

Varje commit visar hur projektet såg ut innan andra commits gjordes. Om jag öppnar min första commit på GitHub kan jag fortfarande se de tre `TODO` som fanns från början, även om jag har ändrat koden sen dess. Det visar att Git behåller de gamla versionerna i historiken i stället för att skriva över dom när jag gör nya commits.

## Fråga 2: Arbetsytan, staging och commits

Jag använder `git status` för att se vilka filer som har ändrats. Med `git add` väljer jag vilka ändringar jag vill ta med i nästa commit, och med `git commit` sparar jag dem i Gits historik.

Jag tänker på arbetsytan som ett papper på skrivbordet där jag skriver och ändrar saker. Staging är som ett kuvert där jag lägger de ändringar jag vill spara, och commit är som en låda där jag arkiverar dem. Om jag ändrar en fil men försöker göra en commit utan att först köra `git add`, kan Git säga `no changes added to commit`. Det beror på att jag inte har valt några ändringar till staging ännu.

## Fråga 3: Min dator och GitHub

Mitt lokala repo finns på min dator, medan GitHub är en plats på internet där jag kan lagra och visa upp projektet. Kommandot `git push` skickar mina commits från datorn till GitHub så att den får de senaste ändringarna av projektet.

Jag ser mitt lokala repo som en låda hemma och GitHub som en glasmonter där jag visar upp mitt arbete. De är två olika platser, så ändringar på datorn hamnar inte automatiskt på GitHub. Om jag ändrar koden men glömmer att köra `git add` och `git commit` finns det ingen ny commit att skicka. Därför kan `git push` svara `Everything up-to-date`, eftersom det inte finns någon ny commit att skicka till GitHub.
