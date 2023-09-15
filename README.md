# daz-recipes
Contributing recipes back to the hive mind - https://dazwallace.wordpress.com 

# Multi-Architecture recipes
Some recipes support pulling down mutliple Architectures that a vender supplies. These will typically have two extra input keys:
- ARCHITECTURE: Typically used to specify which Architecture to pull down. Details of the specific values for each title are in the comments of each recipe that uses this key
- PKG_ARCH: Used the give a nice consistant name to the outputted packag, expeically helpful if this will differe from what's added to the ARCHITECTURE key
## How are these used?
1. Create an override of the parent recipe
2. Duplicate this override
3. Change the name and Identifier to indicate that it's for an Intel title
4. Change the Input keys as needed
5. Change the name and Identifier of the second overrride to indicate that it's for an Apple Silicon (AKA ARM) title
4. Change the Input keys as needed
