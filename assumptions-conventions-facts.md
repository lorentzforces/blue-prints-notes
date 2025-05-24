# Assumptions, Conventions, and Hard Facts

When talking about rooms, the name of the room will appear in Title Case.

West wing and east wing refer to the very left and right columns, respectively.

### Positions & Coordinates

When talking about room coordinates, we'll index from 1 and [1, 1] will be the lower-left-hand spot. We'll denote coordinate pairs with square brackets. Ranks = y axis.

### Facts

Blue memos = true, Red memos = false (unless written by hand).

> _NOTE:_ This does not imply the _opposite_ of a red memo's statement, just that it is _not true._

Garages can only be drafted in the west wing.

Known safe locations:
- Boudoir (opened, contains gem)
- Study (locked, combination)
- Office (locked, combination)
- Drawing Room (locked, combination)
- Shelter (time-lock)

There is a hamster in the Bunk Room.

Known red room downside quirks:
- Lavatory: contains nothing, if you have the sheltered condition then guaranteed to have three items
- Gymnasium: costs 2 steps to enter (total), downside can be removed by disabling power to this room at the Utility Closet breaker box
- Dark room: loses power upon entering, downside can be removed by restoring power to this room at the Utility Closet breaker box

Box game invariants:
- at LEAST one box label is true
- at LEAST one box label is false
- ONLY one box is not empty
