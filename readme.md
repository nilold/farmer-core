# Macintosh

### Intalattion
- Download gtest source
  ```bash
  git clone https://github.com/google/googletest.git external/include/gtest
  ```

### TODOs General
 - CI is failing because of build system configuration

### TODOs develop
 - Tile should inheriit from Substract
 - Create a field class which has a tile matrix
 - Field will control tiles lifecycle and spread
 - Considerations:
   - What does a field really represent in the game?
   - Tiles from different fields can contamine each other?
 - Add DB: SQLite
