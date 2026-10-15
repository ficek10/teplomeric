# Teploměr

Česká slovní hra: každý den tři tajná slova (lehké, střední, těžké). Čím blíž je tip významem, tím víc stoupne rtuť; při 100 °C teploměr bouchne. Běží celá v prohlížeči, bez serveru.

## Data
- `slova.txt`, `vektory-*.txt`: 62 849 slov a jejich vektory (spojení fastText a ConceptNet Numberbatch, 200 rozměrů)
- `kurace.json`: ručně seřazená horká zóna, souvislosti a vyřazená slova
- `tvary.txt`, `znama.txt`: tvary slov a známá slova (slovník kontroly pravopisu z LibreOffice, GPL)
- `rodiny.json`: slovní rodiny podle Českého etymologického slovníku (J. Rejzek)
- `tajna.js`: tři zásobníky tajných slov podle obtížnosti (360 lehkých, 358 středních, 329 těžkých; den 1 = 15. 10. 2026)
