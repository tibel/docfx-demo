# This is the **HOMEPAGE**.
Refer to [Markdown](http://daringfireball.net/projects/markdown/) for how to write markdown files.
## Quick Start Notes:
1. Add images to the *images* folder if the file is referencing an image.

## Mermaid diagrams


``` mermaid
graph LR
    A -- text --> B -- text2 --> C
```

``` mermaid
sequenceDiagram
    Alice->John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

## Nomnoml diagrams

``` nomnoml
[Pirate|eyeCount: Int|raid();pillage()|
  [beard]--[parrot]
  [beard]-:>[foul mouth]
]

[<abstract>Marauder]<:--[Pirate]
[Pirate]- 0..7[mischief]
[jollyness]->[Pirate]
[jollyness]->[rum]
[jollyness]->[singing]
[Pirate]-> *[rum|tastiness: Int|swig()]
[Pirate]->[singing]
[singing]<->[rum]

[<start>st]->[<state>plunder]
[plunder]->[<choice>more loot]
[more loot]->[st]
[more loot] no ->[<end>e]

[<actor>Sailor] - [<usecase>shiver me;timbers]
```
