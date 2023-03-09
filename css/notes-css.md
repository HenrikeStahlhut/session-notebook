# Session notes CSS

## 07/03/2023

### Reihenfolge im CSS

- universal selector < tag selector < class selector < id selector < inline css
  - überschreiben jeweils das kleinere, inline CSS ist am 'stärksten'
- anstatt universal für alles eher body nehmen

### Box Sizing

- box-sizing: border-box --> ganze Box hat angegebene Größe
- box-sizing: content-box --> nur Content Box hat die angegebene Größe, dann kommt nochmal padding und margin dazu, also ist Element sehr viel Größer
- universal selector auf border-box stellen
