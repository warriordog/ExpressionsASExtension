# Expressions Extension for ActivityStreams and ActivityPub

## Goals

The Expressions extension aims to model **non-verbal expressions** and **emotional states** under the ActivityStreams type model.
These *expressions* of sound or emotion are intended to enhance or exist alongside the traditional text formats used by most ActivityPub implementations.

## Rationale

### Inclusivity
While ActivityStreams's existing types and extensions are very effective at supporting text communication, they can be somewhat lacking in other domains.
Two of those are non-verbal and side-band communication, as preferred by many neurodivergent people.
For example, some autistic individuals are uncomfortable communicating with neutral text and prefer a method that more clearly conveys emotion and tone.
Plural people may additionally desire a method to identify which headmate was responsible for a particular post or interaction.
These are both problems that the Expressions extension aims to solve.

### Personalization
In addition to making online communication more accessible, this project aims to bring a bit of lighthearted fun to ActivityPub and the Fediverse.
The existing activities and extensions are very effective at communicating text and media, but they result in a very sterilized and impersonal protocol.
Non-text interactions can bring a more personal touch to communication over ActivityPub.


## Example
![Screenshot of a fediverse post, reading: "That thread may have been a joke, but I unironically love the idea of animal (and other) noises as an Activity type. Imagine a secondary feed, running parallel with the main timeline, that was just silly status updates and non-post interaction. You could throw in related features like feelings, pokes, etc. Limit it to your mutuals and it becomes a little private feed of your friend's interactions. It could be so fun! Practical? no. Useful? not really. Fun? absolutely! " Following that is an example, showing an IRC-style feed of status updates. From oldest to newest, they are: At 6:38, FoxPerson posted something (link). At 6:38, FoxPerson is feeling excited. (neofox_excited emoji). At 6:39, FoxPerson yipped at CatGirl. At 7:10, CatGirl boosted a post by FoxPerson. At 7:10, CatGirl meowed.](docs/original_example.png)

## Prior work / references

* Misskey's "post from other account" feature
* Facebook's "feeling / activity" feature
