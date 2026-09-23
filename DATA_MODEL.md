# Datamodel

## Course
- id
- name
- location
- favorite

## TeeSet
- id
- courseId
- name
- color
- gender/category (optioneel)

## Hole
- id
- courseId
- number
- par

## HoleTee
- holeId
- teeSetId
- lengthMeters

## Round
- id
- courseId
- teeSetId
- date
- holesPlayed
- startingHandicap
- completed

## RoundHole
- id
- roundId
- holeId
- status

## Shot
- id
- roundHoleId
- sequence
- clubId
- shotCategory
- startLie
- result
- direction
- distanceMeters
- endLie
- ballFlight
- wind
- penaltyStrokes
- note
- createdAt

## Club
- id
- name
- type
- loft
- active

## DerivedHoleStats
Niet als brondata gebruiken; berekenen uit shots:
- score
- fir
- gir
- putts
- scrambling
- upAndDown
- bunkerSave
- penalties
