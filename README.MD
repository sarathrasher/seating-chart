# Seating Chart Algorithm

This is a WIP repository built to take the guesswork of creating a wedding seating chart.


The goal of this program is to generate assigned table groupings of individuals in your party based on a variety of factors, like age, affiliation, and personal qualities. 

## Project Board
https://github.com/smuntean/seating-chart/projects

## Inputs
1. Guest list array, which contains a list of guest objects. The guest objects accept the following fields:
```javascript
  {
    name: "", // Name of guest
    guest: "", // Person guest is coming with
    age: Int32, // Age, in integer form
    affiliation: "", // Group the guest is most closely associated with
    forbidden_pairings: [], // Array of guest name's the guest cannot sit next to
    qualities: []
  }
```
2. Floorplan Object, which contains the following fields:
```javascript
  {
    total_tables: Int32, // total number of tables available
    ideal_guest_amount: Int32, // ideal number of guests to fit at a single table
    max_guest_amount: Int32 // maximum number of guests who can fit at a table
  }
```

