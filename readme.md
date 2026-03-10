## Voorbeeld git & gitHub & tags
In dit voorbeeld gaan we het werken van tags laten zien. 
Hieronder het stappenplan:
- Project aanmaken op gitHub
- Project koppelen aan lokale omgeving
- Eerst commit/push uitvoeren

### Wat staat er dan in de basis:
- dit md-bestand
- index.php met eenvoudige koptekst
- zet tag: Basic
```
  </> Code
  git tag Basic
  git push --tags
```
#### Stap 1
- uitbreiding index.php met meer tekst
- tag: Stap_1
#### Stap 2
- uitbreiding index.php met footer.php en header.php
- tag: Stap_2
#### Stap 3
- Extra uitbreiding in index.php
- tag: Stap_3

### Bijzonderheden
Let op dat bij elke stap een tag wordt aangemaakt. 
*Commando: *
```
git tag Stap_1
git push --tags
```
