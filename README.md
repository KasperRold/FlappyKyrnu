# FlappyKyrnu
### Made with ♥ by: Kasper Rold, Nicklas Vilster & Patrick Bergmann

Programmet er bygget udelukket på JS (JavaScript)

Kyrnu figuren er bygget ud fra sprites, som skal bevæge sig på mouseClick. 

#### En kort beskrivelse af programmet
Spillet er bygget op omkring den originale version af spillet 'Flappy Bird' vi har blot ændret fuglen til Kyrnu og ændret rørene til at være sikkerhedskameraer, som Kyrnu ikke er glad for. 

```javascript
if (this.velocity >= this._jump) {
  this.frame = 1;
  this.rotation = Math.min(Math.PI/2, this.rotation + 0.3); // GOING UP
} else {
  this.rotation = -0.3; // GOING DOWN
}
```
I koden over vises der hvordan spriten bevæges op og ned. Denne bestemmer også hvordan spriten skal rotere. Her er rotationen sat til -0.3 når spriten falder ned af.






                       ** DISCLAIMER ** 
INTET ER MENT SOM NOGET ONDT OG ER BARE LAVET I MED EN SJOV MENING 
