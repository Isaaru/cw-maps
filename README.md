
![Logo](https://www.clumsysworld.com/wp-content/uploads/2023/10/CWt.png)
# Clumsy's World Maps

The purpose of this project is to create a collection of zone maps with updates and changes specific to Clumsy's World. Additionally, this project will make use of a standardized design and layering format that creates consistency across all maps.

## Structure

### Base Layer (zonename.txt)
The base layer of each map will consistent only of the map itself (zone boundaries, walls, buildings, water, zonelines, trees or other objects that are important to the zone design (growthplane), etc). Additionally, the base layer will consistent of an timestamp in the bottom right corner, placed outside the zone boundaries to track the last updated time.

![Base Layer](https://www.clumsysworld.com/BaseLayer.JPG)

### Layer 1 (zonename_1.txt)
Layer 1 will consist of all zone-specific points of interest. Points of interest include the zoneline names, traps, special doors, clickable objects, groundspawns, special buildings, etc.

![Layer 1](https://www.clumsysworld.com/Layer1.JPG)

### Layer 2 (zonename_2.txt)
Layer 2 will consist of all notable NPCs. These will include Rare Spawns, Raid Targets, Merchants, Soulbinders, etc.

![Layer 2](https://www.clumsysworld.com/Layer2.JPG)

### Layer 3 (zonename_3.txt)
Layer 3 will consist of all seasonal/holiday NPCs and points of interest. Essentially anything that is specific to an event, holiday, seasonal quest, etc should rest within this layer.

![Layer 3](https://www.clumsysworld.com/Layer3.JPG)

## Formatting
### General Color Guidelines
While no specific formatting is necessarily enforced, the following are recommended:

Zone Boundaries/Walls: Black  
Zone Buildings/Structures: Black  
Openable Doors: Yellow  
Bridges/Hidden Pathways: Yellow  
Water: Blue   
Traps: Red  
Interactable Objects: Yellow/Red  
Blocked Doors: Red  
Lava: Red  
NPC Names: Colors that contrast the other map objects in their area so they are legible. (This may change in the future)

### General Sizing Guidelines
Labels should usually be done in Medium Font so they are legible. The overall size used will depend on the map itself and the density of other map objects in the area.

### Special Scenarios
#### Hidden & Underwater Passages / Underground Areas
In numerous zones lightblue/green borders/lines are used to denote underground, underwater or hidden passages. While these colors are not specific, they do provide a nice contrast and are easily separated from other areas on a map.

![Underground & Hidden Passages](https://www.clumsysworld.com/Underground.JPG)

#### Stairs
In numerous zones contrasting lines are used to denote stairs and traditionally done a lighter blue/grey. Stairs should be a contrasting color so they are not confused as walls.

![Stairs](https://www.clumsysworld.com/Stairs.JPG)
## How to Contribute
The Maps hosted here are version controlled to maintain integrity and validate changes. If you would like to contribute please follow these instructions:

### The Pull Request Workflow
When branch protection is active, contributors must follow this process:

1. Create a new branch or a "fork" (a copy of the repository under your own account).
2. Commit changes to your branch/fork (edit the file, and commit the changes).
3. Open a Pull Request (PR) to propose merging your changes into the base repository's main branch.
4. The PR must be reviewed by someone with approval rights. Reviewers can request changes or approve the PR.
5. Once approved the changes are merged into the base branch. 
