Items not on list:
Alchemical bomb
bomb

```dataview
TABLE WITHOUT ID
file.link as "Weapons", level as "Level", tags[1] as "Rarity"
FROM "Character building stuff/Character Building/Equipment" AND #Common OR #Uncommon 
WHERE contains(noteType, "weapons") 
SORT level asc
```



