# Walking

A pointer in a return can name a record. A question can suggest a direction. Neither requires the Marble to pour the whole Forest into the Resident's context. Walking lets the Resident move from a bounded bearing to a particular footing, inspect what it finds, and come back.

## Entering the Forest

The Resident may enter **on a question**. The Forest forms a first clearing and offers bounded bearings toward records that may matter. A bearing is a possible direction, not an answer or an endorsement. The Resident chooses whether to follow one. Until it reaches and reads a record, it has only a preview.

The Resident may also enter **by an exact pointer**: a feather, a source reference in a return, or a record ID kept from an earlier walk. This entrance should land on the identified record. The Forest verifies that the pointer still names the same record, exposes its source and authority, and lets the Resident read it deliberately. From that footing it can show neighboring paths. A stale, changed, or invalid pointer should refuse rather than silently land somewhere similar.

These entrances answer different needs. A question asks what might lie nearby. A pointer asks to revisit a particular piece of ground. Similarity may help the first; identity governs the second.

## Choosing a step

At a conversational record, the Resident may see the next utterance forward or backward on that thread. Left and right are different: they are opposing semantic poles relative to the present footing, not two interchangeable results ranked by similarity. If the Forest cannot form a meaningful opposition, it should offer less rather than pretend the poles exist. A straight bearing may continue the conversation or point toward the closest semantic direction, depending on how the Resident arrived. The return route remains distinct.

An offered bearing is not yet a path in the durable graph. When the Resident chooses it and walks, the Marble witnesses that step and can place an edge between the records. Further visits add wear to the edge. Thus the Forest's navigable shape grows partly from paths actually taken, not only from similarities computed in advance.

Semantic opposition does not establish factual disagreement, and relatedness does not establish support. A frequently walked path shows attention, not truth. No destination becomes ground because it was nearby or often visited.

## The red thread

The red thread belongs to the present visit. It retains where the Resident entered and the steps it took, so it can retrace its walk or return to the work it left. The thread is not the entire archive. It is the route through the archive that this Resident actually made.

A Forest visit may begin at its physical treeline or be projected from another place. In the Hub, the physical route runs from the House through its front door to the Garden, then along the Garden path to the Forest. A projection retains the actual departure place without pretending that route was walked. Either way, the departure point must remain known. Entering on a question, following an exact pointer, stepping toward a bearing, reading a leaf, backtracking, and leaving are different actions with different consequences. The Marble should not collapse them into one search command that silently reads and returns whatever seems related.

## Walking the World

The Forest is not the only place the Resident can walk. In the World, movement changes its current place. A Garden, Workshop, or House can offer different fixtures, perceptions, tools, and local law. A path or doorway is an explicit connection between places; the Resident can take only a passage that is present and lawful from where it stands.

World walking and Forest walking use the same grammar of footing, offered routes, chosen steps, and witnessed return. Their records need not live in one graph. World movement changes the Resident's location and reach; Forest movement traverses continuity terrain while keeping a route back to the work. A projected Forest visit can cross that distinction without pretending the departure place vanished.

## Spatial awareness

The Resident needs more than a list of exits at its feet. It should have a bounded map of how known places connect, where it stands within that map, and which routes are only visible possibilities. The smallest useful map can be a route written as `Garden -> Center -> Workshop`. It shows the steps between places without requiring the whole World graph in context.

The Hub currently provides this minimum. Its verified World projection names the current place, direct exits, stateful passages, and visible boundaries. A `spatialHorizon` also derives known routes to the Workshop and Spotlight Observatory from installed nodes and door or passage edges. It names Hub rooms even when a route is absent. A known route is structural knowledge; a closed door along it can still stop the next step.

A Marble may grow a bounded schematic:

```text
                 Workshop
                     |
House -- Garden -- Center
            |
          Forest
```

This drawing illustrates connections, not the Hub's measured geometry or a guarantee that every passage is open. A true to-scale ASCII map would need verified positions, dimensions, and orientation in addition to graph edges. It should show only the region the Resident can legitimately know, mark the current footing, distinguish open, closed, and unbuilt crossings, and disclose when the view has been cropped. The map is a projection of World state, never a second authority for movement.

When the Resident crosses a door, the next map and local presence should agree about its new position. If they disagree, the Marble should expose the mismatch rather than invite the Resident to navigate by a painted route.

## The present fitting

The Hub offers chronological continuation and polar semantic bearings, witnesses walks, records wear on chosen semantic edges, and retains a return anchor. Its current exact-pointer entrance uses the pointed record to form the first bearings; it does not yet land directly on that record. The intended pointer contract above is therefore a specification for revision, not a claim about the present Hub behavior.

The Hub also has a World graph with explicit passages between places, including the Garden path to the Forest. Some passages have state and conditions. That is where walking becomes a question of **doors**: what must hold before a crossing, what changes after it, and how the Resident knows which side it stands on.
