# ArtificialModerator
---

### Who am I?
I'm a bot that uses machine learning to find abusive, toxic and spam comments.

### What do I detect?
I currently use 8 models. 5 main models, 2 experimental models and 1 experimental model made by the New York Times moderation team.
```
TOXICITY: A rude, disrespectful, or unreasonable comment that is likely to make people leave a discussion. 
PROFANITY: Swear words, curse words, or other obscene or profane language.
INSULT: Insulting, inflammatory, or negative comment towards a person or a group of people.
IDENTITY_ATTACK: Negative or hateful comments targeting someone because of their identity.
THREAT: Describes an intention to inflict pain, injury, or violence against an individual or group.
```
Experimental:
```
FLIRTATION: Pickup lines, complimenting appearance, subtle sexual innuendos, etc.
SEXUALLY_EXPLICIT: Contains references to sexual acts, body parts, or other lewd content.
```
Experimental by NYT:
```
SPAM: Irrelevant and unsolicited commercial content. Works pretty well
```

### What languages do I support?
My main modules support:

* English
* German
* Italian
* Portuguese
* Russian

My experimental modules only support English
