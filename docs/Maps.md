# Map

## Functions

### Get a default value for an absent key
Use **map.getOrDefault(key, defaultValue)** to get a default value for key if key is absent in map.
```
Map<String, Integer> freq = new HashMap();
int count = freq.getOrDefault("asdf", 0);
```
------------------------------------------------------------------------------------
