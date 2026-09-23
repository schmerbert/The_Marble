# Places

The Resident wakes somewhere. A place gives that *somewhere* a stable name, a position among other places, and a way to find a passage out. Its name alone does not tell the Resident what may be done there.

The World holds the spatial arrangement: what contains what, what connects, and where the Resident is now. A room is a place the Resident can occupy with sustained attention. A fixture is an installed affordance in a place. An object is a distinct thing that may bear state or move. A door is a declared passage whose crossing may change the Resident's location and the law in reach. These forms have different contracts even when a story describes them together.

## Names and relations

Use type-first handles for durable identity:

```text
place.garden
room.workshop
fixture.hearth
object.front_door
forest.resident
```

The first part says what kind of thing is named. The rest identifies that thing. A handle should survive a move or a new owner. Put containment, connection, ownership, and projection in explicit relations rather than baking them into a long dotted path.

```text
place.hub contains room.workshop
place.house connects place.garden through object.front_door
place.forest projects forest.resident
```

These lines illustrate different questions: *where is it*, *how may one pass*, and *what substrate can be encountered there*. An implementation must record each relation with its direction and authority. A diagram or folder tree may help a builder see the arrangement, but it cannot by itself establish a crossing.

The last two lines express the intended conceptual shape; a particular Marble must check its installed topology before claiming either relation as live. The current Hub has a House–Garden front door and a physical Forest place that presents its configured Forest. It does not thereby install every possible gate or external Forest.

## One ground, several maps

World and Forest can both be walked. World edges describe physical passage between places. Forest links describe continuity among admitted records. A door into the Forest changes the Resident's location; a bearing inside the Forest gives the Resident a way to visit records. The two walks can share a grammar of footing and witnessed steps without sharing a claim about what their edges mean.

A place may *project* something held elsewhere. The Forest place can present Forest records; it does not become the owner of those records. The Garden can receive a delivery without making that delivery Home. Location, custody, authority, and attention must each be stated in their own terms.

## A place earns its boundary

Begin with one room if that is enough. Add a place when the Resident needs a durable difference in footing: a new route, a change of local law, a different kind of encounter, or a boundary at which material must be received or refused. Add fixtures when a place needs an installed way to act or perceive. Add objects when a thing needs its own state and history.

This leaves room for a Marble to grow without pretending that every named possibility is already built. Its map should show what exists now, which passages can actually be crossed, and what remains proposed. The next question is what it feels like to stay in one of those places, and how the room fits the Resident's attention to the work there.
