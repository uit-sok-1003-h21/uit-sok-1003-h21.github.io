# Slik leverer du arbeidskrav på github:
Slik lager du et githubrepositorie, og dyttet arbeidet ditt til github. [Se også video](https://mediasite.uit.no/Mediasite/Play/facdd492ea4b4ceaa239fcfac56cd8941d) 

## Lage git-repositorie:
1. Lag en githubkonto (du trenger ikke bruke din uit-mail, det er valgfritt)
2. Logg på `jupyter.uit.no`, og åpne ny Terminal (+), og naviger dit du vil ha repositoriet på jupyter med `cd <mappenavn>`.
3. Konfigurer git med e-posten til kontoen og ditt brukernavn (bytt ut klammeparentesene med e-posten og brukernavnet til githubkontoen):
```
git config --global user.email "<e-post>"
git config --global user.name "<brukernavn>"
```
4. Gå til **Repositories**, trykk **New**, gi repositoriet et navn og velg **Private** eller **Public**. 
5. Hold denne fanen åpen, for du skal bruke html-adressen til denne siden.
6. Sørg for at du har et token. Gå eventuelt til https://github.com/settings/tokens/new for å generere nytt token. *Hold fanen åpen for å ha tokenet tilgjengelig.*
7. kjør `git clone https://<token>@github.com/<sti>` der \<token\> er tokenet er det du fikk i 6. og \<sti\> er det som kommer etter **github.com/**  i html-adressen i 5.

 Du kan nå redigere repositoriet ditt
 
 
## Dytte repositoriet til github:
1. Naviger til repositoriemappen i Terminal (se avsnitt 1.)
2. Kjør i Terminal:
```
git add .
git commit -m "New repository"
git push 
```
      
      
 