# Expressions Extension Prototype
This is a WIP mockup of what the Expressions type model could look like.
It is *not* fully built out and will likely change dramatically as the actual specification is designed.

## Expressions (moods and vocalizations)
```text
Express : Activity (actor is conveying something to an audience)
    Object -> Object | Link (what is being expressed)
    Target -> Object | Link (who is it expressed to)

Mood : Object (a feeling or emotion)
Vocalization : Object (a non-verbal sound)
```

Notes:
* Need to add properties to Mood / Vocalization

## Identities
```text
WithIdentity : Activity (extension, indicates that the activity was performed by / with a specific identity)
    AsIdentity -> Identity (identity that performed the activity)

Identity : Object (a specific identity or persona associated with an actor)
    PartOf -> Actor (actor that this identity belongs to)
```

Notes:
* Need to add properties to Identity
* Can't use Profile because "describes" can't be a link

