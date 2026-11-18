# Project Title

## Authors

 - Scott Kirkpatrick(https://github.com/ScottK567)
 - Fairooz Farzana (https://github.com/TasniaF)
 - Essey Araya(with optional link to github profiles)

## Project Statement
You are developing a treasure-hunting game where a player explores a map looking for hidden treasures. The map contains many treasures scattered across different locations. The player has a limited searching ability, meaning they can only detect treasures within a certain radius of their current location, and with the player’s coordinates, the locations of all hidden treasures, and the player’s search radius, our program can identify all treasures the player can detect.

Each treasure chest contains an (x,y) coordinate, and the player has an (x,y) coordinate along with a search radius.

Implement a method that takes the player's coordinates, their search radius, and a KD Tree containing the treasures' locations. It must return a list of all the treasure chests located within the search radius of the player.

Euclidean distance formula:
<img width="229" height="40" alt="EuclideanDistance" src="https://github.com/user-attachments/assets/844c57b1-138a-4f8c-b1e7-59b87a6aa8e5" />


Calculate the Euclidean distance between the player and the treasure chest. It is considered in range if it is less than or equal to the search radius.

Requirements:
Return every chest within the player's search radius
Don’t return any outside of the search radius.
If they are located on the boundary, they are considered within the search radius.
If there are zero treasures, return an empty list.
Don’t return duplicate chests.


![sample image](sample-image.png "Sample Image")
 
## Examples

put 2-3 small examples here


### Example 1:

**Input:** `nums = [2,7,11,15]`, `target = 9`

**Output:** `[0,1]`

**Explanation:** Because `nums[0] + nums[1] == 9`, we return `[0, 1]`.

## Constraints

- Constraint 1
- Constraint 2


### Topics

- binary tree
- depth first search

### Level

- Easy

## Code (stub to show parameters, return type, and definitions)

```java
// put your Java stub code here
class Solution {
    public int[] twoSum(int[] nums, int target) {
        // code here

    }
}
```

## Test cases

### Test Case 1

`nums = [2,7,11,15]`

`target = 9`

## Solutions

- Include two (or more) solutions, one in Java and one in another language.
- Each **must** explain in detail how to run it (where it will run as presented.)
- The code must include all needed libraries and be well-documented with commenting.

[Java](javasolution.java)

[Python](pythonsolution.py)

[C++](cppsolution.cpp)

[complexity analysis](complexity.md)

## Video on (add project title here)

To deepen understanding of (add project topic here) see [Add title of Video here](Add full URL to video here)

## References (for all ideas not our own)

- [Reference 1](link to reference 1)
