# 5_15_hacknight

## Coding Challenge

Provide users the ability to narrow down search results or product listing by choosing from a set of product attributes (faceted navigation).
In order for us to successfully provide product attributes in a cost effective manner we will need to extract it from the description. 

Provided in the zip file are description for three shoes for which we want to extract 4 attributes : 
Heel_Style, Toe_Style, Material, Features.

Your application should read in these three files and print the features. Your output should look like below

```
shoe1: 
Heel_Style : Stiletto
Toe_Style : Peep Toe
Material : Manmade

shoe2:
Heel_Style : Block Heel
Toe_Style : Open Toe
Material : Suede 
Features : Padding

shoe3:
Heel_Style : Cone Heel
Toe_Style : Open Toe
Material : Suede
Features : Padding
```

### Extra Credit:

For each of the shoe also list out the Heel_Height based on the following criteria

Heel 1”-2” = Low Heel
Heel 2”-3” = Mid Heel
Heel 3”-4” = High Heel



### Source Files

#### `shoe1.txt`

```
Details
Sizing: True to size.

- Peep toe
- Back zip closure
- Caged construction
- Stiletto heel
- Approx. 4" heel
- Imported
Materials
Synthetic upper, PU sole
```

#### `shoe2.txt`

```
Sizing: True to size. M=standard width 

- Open toe
- Faux suede fabric construction 
- Ankle cuff with elastic inset
- Back zip closure with tassel pull
- Lightly padded footbed
- Block heel 
- Approx. 1.5" heel 
- Imported
Materials
Fabric upper, synthetic sole
```

#### `shoe3.txt`

```
- Open toe
- Studded detail
- Slip-on
- Lightly padded footbed
- Cone heel
- Approx. 3" heel
- Imported
Materials
Faux suede upper, manmade sole
```
