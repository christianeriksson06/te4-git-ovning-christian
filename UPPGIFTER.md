# Uppgifter - Git Basics Exercise

## Uppgift 1: Personlig presentation
1. Skapa en fil som heter `presentation.md`
2. Skriv en kort presentation av dig själv (namn, ålder, intressen, mål med kursen)
3. Använd Markdown-formattering (rubriker, listor, etc.)
4. Gör en commit med meddelandet: "Lägg till personlig presentation"

## Uppgift 2: Favorit programmering
1. Skapa en fil som heter `favorit-kod.js`
2. Skriv ett enkelt JavaScript-program som skriver ut ditt namn
3. Lägg till kommentarer som förklarar vad koden gör
4. Gör en commit med meddelandet: "Lägg till mitt första JavaScript-program"

## Uppgift 3: Lärande reflektion
1. Öppna filen `reflektion.md` (som redan finns)
2. Besvara frågorna i filen
3. Gör en commit med meddelandet: "Lägg till reflektion om Git-lärande"

## Uppgift 4: Experimentera
1. Gör en ändring i någon av dina filer
2. Använd `git status` för att se vad som har ändrats
3. Använd `git diff` för att se exakt vilka ändringar du gjort
4. Gör en commit med ett beskrivande meddelande
5. Kör `git log` för att se historiken av dina commits


## Uppgift 5: Skapa och koppla GitHub-repo, pusha till GitHub

### Steg 1: Skapa ett nytt repository på GitHub
1. Gå till [github.com](https://github.com) och logga in
2. Klicka på "New" eller "Create repository"
3. Ge ditt repository ett namn (t.ex. `te4-git-övning-dittnamn`)
4. Välj "Private" eller "Public" enligt instruktion
5. Skapa repository utan README, .gitignore eller licens (du har redan filer lokalt)

### Steg 2: Koppla ditt lokala projekt till GitHub
1. Öppna terminalen i din projektmapp
2. Kör följande kommando (byt ut URL till din egen):
	```bash
	git remote add origin https://github.com/ditt-användarnamn/te4-git-övning-dittnamn.git
	git branch -M main
	git push -u origin main
	```
3. Om du får frågor om inloggning, logga in med ditt GitHub-konto

### Steg 3: Kontrollera att allt är uppladdat
1. Gå till ditt repository på GitHub
2. Kontrollera att dina filer syns där
3. Kopiera länken till ditt repository


## Yppgift 6
Läs på om `.gitignore` filer hos git-scm.com och skapa en som ignorerar:
- `Thumbs.db` (Windows)
- `node_modules/`

## Inlämning
När du är klar:
1. Se till att allt är pushat till GitHub
2. Kopiera länken till ditt repository
3. Skicka länken till mig som DM i Discord

## Felsökning
Om något går fel:
- Läs felmeddelandet noga
- Använd `git status` för att se vad som händer
- Fråga i discordkanalen "help-me" om hjälp
- Google på felmeddelandet
- Använd Claude och fråga om felmeddelandet

**Kom ihåg:** Det är okej att göra fel - det är så man lär sig! 🎓
