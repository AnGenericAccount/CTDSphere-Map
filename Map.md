```mermaid
flowchart LR
    tumblr[r/tumblr] --> groupchat([r/tumblr])
    groupchat --> DoD(Disciples of Diogenes)
    DoD --> subreddit[r/CuratedTumblr]
    DoD --> CTDS(CuratedTumblr)
    subreddit --> CTDS
    DoD --> Iyk(Iyk's Server)
    DoD --> REM(REM)
    DoD --> luck(hehe... good luck)
    CTDS --> luck
    CTDS --> reconstruction(CTDS Reconstruction Team)
    subreddit --> reconstruction
    CTDS --> lab(The Laboratory)
    DoD --> lab
    subgraph Laboratory [The Laboratory]
        lab --> Civilization(Civilization)
        lab --> Storyteller(Storyteller)
    end
    DoD --> Experiment(The Experiment)
    CTDS --> Experiment
    CTDS --> CAH("Sylveon Appreciation Club (CAH)")
    CTDS --> Verbina("Sylvion Appreciation Club (Verbina)")
    CTDS --> tech(tec h)
    CTDS --> techchat([tec h])
    subgraph tec[tec h]
        techchat --> tech
    end
    CTDS --> RP(uwu OC RP :woa:)
    CTDS --> picrew(Picrew Land)
    CTDS --> salmon(Salmon Head II)
    CTDS --> Vmark(Vmark Server)
    Vmark --> concern(:Concern:)
    Vmark --> catposting(catposting)
    Vmark --> sphere("CTDSphere Map")
    style sphere fill:#f44
    CTDS --> sphere
    lab ---> sphere
    CTDS --> gimblor(gimblor)
    CTDS --> fursona([Fursona Design Chat])
    fursona --> gimblor
    gimblor --> bep("Bep (and Toothworm)")
    subgraph Romeposting
        rome(romeposting)
        romesub[r/romeposting]
    end
    CTDS --> rome
    CTDS --> romesub
    CTDS --> DND(CTD DND)
    CTDS --> dawn(Riders of the Dawn)
    CTDS --> blade(Devil's Blade)
    subgraph riders[The Dice Goblins]
        dawn --> blade
        blade --> ungulant(The Ungulant)
        blade --> terminal(Fortuna Terminal)   
    end
    blade -..-> further{{further splinters}}
    style further stroke-dasharray:4 2
    subgraph Key [Map Key]
        direction LR
        sub[Subreddit]
        discord(Discord Server)
        chat([Tumblr Groupchat])
    end
```
