# DnDoku, a web-based D&D game
---
Inspired by PokeDoku, this project aims to create a version based on creatures from Dungeons and Dragons Fifth Edition using sources like the Monster Manual, with a variable matrix using arbitrary values like:
- Challenge Rating
- Number of Hit Dice
- Alignment
- Published Source
- Creature Type
- Creature Environment
- Ability Scores
- Spellcasting Level
- Size

---
### Pre-development Requirements
- 12 distinct traits for randomized matrix
- API access or scraper for DnDBeyond
- Sourcing media for creature representations

### Frontend Requirements
- Must be render 3x3 grid
  - Each row header is a trait
  - Each column header is a trait
- Each cell will be a creature. 
  - Click a cell and type a monster name in it
  - receive a stream of monster names from the backend
- All calls to the backend must be made with grpc

### Backend Requirements
- Must implement grpc controllers
- Must keep contracts repo up to date with proto files
- Must store information about user interaction. 
- Must store information about the creatures
- Must generate a puzzle daily

### PathDoku??
- Paizo Community Use Policy more amenable to IP usage for project than WotC.