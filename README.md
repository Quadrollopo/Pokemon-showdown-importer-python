# Pokemon-showdown-importer
Create a string for importing the team on pokemon showdown from your save. Working only on gen 4 (for now)

## Usage
`python main.py <path/to/file_name.sav>` where file_name.sav is the sav file from your game. 
You can also leave blank, in that case the program will search for a `Pokemon.sav` file in the same directory as `main.py`  
The output is something like:  
```Jojo (Piplup)
Level: 10
IVs: 31 HP / 18 Atk / 15 Def / 18 SpA / 15 SpD / 19 Spe
Ability: Torrent
- Pound
- Growl
- Bubble

Dax (Shinx)
Level: 4
IVs: 17 HP / 10 Atk / 8 Def / 8 SpA / 9 SpD / 8 Spe
Ability: Intimidate
- Tackle
```
You can copy the output and paste in the import/export section in teambuilder on pokemon showdown
