# Assumptions, Conventions, and Hard Facts

When talking about rooms, the name of the room will appear in Title Case.

West wing and east wing refer to the very left and right columns, respectively.

### Positions & Coordinates

When talking about room coordinates, we'll index from 1 and [1, 1] will be the lower-left-hand spot. We'll denote coordinate pairs with square brackets. Ranks = y axis.

### Facts

You are Simon P. Jones.

There are 8 envelopes with 8 individual authors. One letter is missing.

The day starts at 0800. Day 1 is Friday, November 6th 1993.

Blue memos = true, Red memos = false (unless written by hand).

Green memos found in Hartley's room are always false.

> _NOTE:_ This does not imply the _opposite_ of a red memo's statement, just that it is _not true._

Garages can only be drafted in the west wing. The Garage allows access to the West Grounds if the breaker box power is turned on.

The basic terminal password is `swansong`.

Terminal locations:
- Security
- Laboratory
- Shelter
- Office (email only accessible from here)
- Blackbridge Grotto (special admin terminal)

Known safe locations:
- Boudoir (opened with 1225, contains gem and letter #4)
- Study (locked, combination)
- Office (locked, combination)
- Drawing Room (locked, combination)
- Shelter (time-lock, contains gem and letter #7)
- Apple Orchard (opened with 1128, technically a gate, technically still counts)

There is a hamster in the Bunk Room.

Known red room downside quirks:
- Lavatory: contains nothing, if you have the sheltered condition then guaranteed to have three items
- Gymnasium: costs 2 steps to enter (3 total), downside can be removed by disabling power to this room at the Utility Closet breaker box
- Dark room: loses power upon entering, downside can be removed by restoring power to this room at the Utility Closet breaker box

Box game invariants:
- at LEAST one box label is true
- at LEAST one box label is false
- ONLY one box is not empty

The following rooms can only be drafted in the East & West Wings:
- Terrace
- Patio
- Veranda
- Morning Room
- Greenhouse
- Secret Garden

**Soil Survey:**

These values affect amount of fruit spread from gardens and amount of flowers that can bloom in a Greenhouse.

1=poor, 2=good, 3=rich, X=barren

```
9  1   3

8  2   2

7  2   3

6  2   1

5  1   2

4  1   3

3  3   2

2  X   2

1  1   1

   1   5
```
