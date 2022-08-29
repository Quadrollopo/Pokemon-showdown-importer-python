# Pokemon-showdown-importer
Create a string for importing the team on pokemon showdown from your save. Working only on gen 4 (for now)

## Usage
`python main.py <path/to/file_name.sav>` where file_name.sav is the sav file from your game. 
You can also leave blank, in that case the program will search for a `Pokemon.sav` file in the same directory as `main.py`  
The output is something like:  
```Zubyte (Golbat) @ Quick Claw
Level: 33
Ability: Inner-focus
Nature: Jolly
EVs: 31 HP / 29 Atk / 20 Def / 63 SpA / 9 SpD / 53 Spe
IVs: 1 HP / 9 Atk / 29 Def / 0 SpA / 1 SpD / 11 Spe
-Mean Look
-Poison Fang
-Fly
-Bite

Jojo (Prinplup) @ Sea Incense
Level: 33
Ability: Torrent
Nature: Quirky
EVs: 27 HP / 25 Atk / 29 Def / 42 SpA / 11 SpD / 60 Spe
IVs: 5 HP / 31 Atk / 0 Def / 17 SpA / 28 SpD / 27 Spe
-Cut
-Brine
-Surf
-Metal Claw
```
You can copy the output and paste in the import/export section in teambuilder on pokemon showdown
