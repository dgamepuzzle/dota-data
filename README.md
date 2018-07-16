# dota-data
json data for dota heroes and items

## GENERAL
Automatically generated by a service, everytime data in the lookups changes.

## Look up data:

### dota API - heroes
- looks up: tag, name, bio
- link: http://www.dota2.com/jsfeed/heropickerdata?v=4144804b4144804&l=english

### dotabuff API - heroes
  - looks up: ability names, hero stats
  - link: https://raw.githubusercontent.com/dotabuff/d2vpkr/master/dota/scripts/npc/npc_heroes.json

### dota API - hero abilities
  - looks up: hero ability descriptions
  - link: http://www.dota2.com/jsfeed/heropediadata?feeds=abilitydata&l=english
  
### dota API - items
  - looks up: item descriptions
  - link: http://www.dota2.com/jsfeed/heropediadata?feeds=itemdata&l=english
 
## NOTES
- Some of the abilities (like Monkey King's Primal Spring do not have descriptions in *dota API - hero abilities*. Will add support for them in the future, via https://raw.githubusercontent.com/dotabuff/d2vpkr/master/dota/resource/dota_english.json .
