# Projekti dokumentatsioon
Johanna Must - Arendaja

## Valitud serveri variant koos põhjendusega
- Render.com
- lihtne
- tasuta
- automaatne deploy
- polnud vaja serverit seadistada

## Serveri info
- Veebiserver: Render Static Site
- Avalik URL: https://veebirakendus.onrender.com

## SSH / CI/CD seadistus
- SSH ei kasutata (render haldab turvaliselt ütleb chatgpt)
- CI/CD: Render automaatne deploy Github pushist
- Github Actions: ei kasutata (chatgpt)

## Probleemid ja lahendused
- Mõned git käsud läksid valesti -> tegin algusest
- Esimene katse läks sassi kuna tegin valed git käsud -> tegin kõik algusest ka repo tegin uue

## Deploy testimise tulemus
- Branch: test
- Pull Request merge'itud main'i
- Deploy automaatselt tehtud
- Veebilehel näha uus tekst: <a>PR test</a>
