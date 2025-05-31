# Assumptions, Conventions, and Hard Facts

When talking about rooms, the name of the room will appear in Title Case.

West wing and east wing refer to the very left and right columns, respectively.

### Positions & Coordinates

When talking about room coordinates, we'll index from 1 and [1, 1] will be the lower-left-hand spot. We'll denote coordinate pairs with square brackets. Ranks = y axis.

### Facts

You are Simon P. Jones.

There are 8 envelopes with 8 individual authors. One letter is missing.

The day starts at 0800. Day 1 is Friday, November 6th 1993.

1 hour in game = 7.5 minutes in real-time. Allowing the clock to run past 0800 does not automatically end your day.

Blue memos = true, Red memos = false (unless written by hand).

Green memos found in Hartley's room are always false. Green memos otherwise are usually true (although may be conditional on other clues).

> _NOTE:_ This does not imply the _opposite_ of a red memo's statement, just that it is _not true._

Garages can only be drafted in the west wing. The Garage allows access to the West Grounds if the breaker box power is turned on.

The basic terminal password is `swansong`.

Terminal locations:
- Security
- Laboratory
- Shelter
- Office (email only accessible from here)
- Blackbridge Grotto (special admin terminal)

Known safe locations: [see the separate doc.](./dates-combinations-safes.md)

Antechamber Lever locations:
- SOUTH: Greenhouse (requires broken lever item)
- WEST: Secret Garden
- EAST: Great Hall (door to the right as you're looking at the two chairs, this might change day to day)
- NORTH (to Room 46): Basement
- > "One back up lever for each Antechamber door has been installed in separate locations for redundancy."

- Secondary: south lever in weight room (may be behind suspicious brick wall)
- Secondary: east lever also in secret garden (break brick wall, arrows away from secret window)

There is a hamster in the Bunk Room.

Known red room downside quirks:
- Lavatory: contains nothing, if you have the sheltered condition then guaranteed to have three items
- Gymnasium: costs 2 steps to enter (3 total), downside can be removed by disabling power to this room at the Utility Closet breaker box
- Dark room: loses power upon entering, downside can be removed by restoring power to this room at the Utility Closet breaker box

Box game invariants:
- at LEAST one box label is true
- at LEAST one box label is false
- ONLY one box is not empty

### Room drafting limitations:

West wing ONLY
- Garage
- West Wing Hall
- Her Ladyship's Chamber (from south-facing doors)

East Wing ONLY
- East Wing Hall
- Master Bedroom

The following rooms can only be drafted in the East **AND** West Wings:
- Terrace
- Patio
- Veranda
- Morning Room
- Greenhouse
- Secret Garden (must use the Secret Garden Key to unlock a locked door)

Other Special Cases
- Conservatory (only draftable in a corner)
- Bookshop (only draftable from Library)

**Soil Survey:**

These values affect amount of fruit spread from gardens and amount of flowers that can bloom in a Greenhouse.

For the Greenhouse, the number corresponds to the number of gems that will be available.

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
