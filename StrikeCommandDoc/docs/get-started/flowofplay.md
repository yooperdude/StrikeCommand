# Flow of Play

Strike Command has two areas of play. The first is multi-domain, the second is simulation. The multi-domain section is where you perform negotiations, scouting, dealing with customers or rivals, and planning for the mission itself. The simulation is where the game moves into the battle space and you watch your plans unfold live in a military grade combat simulator.



## Multi-Domain :simple-multisim:

This is the traditional RPG time. Anything that doesn't occur as part of the mission, happens here. All activities in this space are to prepare for the simulation mission. 

### Skill Checks

If you need to determine success, or failure, during the Multi-Domain time, you perform a skill check. Skills come from your background, certain things can be done without any background or experience such as a negotiation. Other things require experience, such as hacking an air defense system. 

Take two different colored six sided dice. Define one as the HIGH, and the other as LOW. 


**Result = Skill - Difficulty + High - Low**


The result, if zero, will be no success or failure. Maybe you gained no knowledge, or couldn't pick a lock, or the negotiations stalled.

+1 or -1 - Modest success or failure with a hook. Yes, you gained some knowledge on a +1, but not everything. Or you failed to pick the lock, but you weren't detected.

+2 or -2: - Success or Failure. You managed to hack the computer and got what you expected. Or, you failed to hack the computer and alerted the enemy to your presence.

+3 or -3 - Critical success or Critical Failure. Not only did you enter into negotiations and get what you wanted, but it revealed critical information about enemy air defenses. Or, you failed to negotiate and the enemy PMC's now know exactly what your plans are.

There are some examples below in the Actions area.

### Initial Steps

``` mermaid
graph LR
  A[Create Characters] --> B[Create Corporation];
  B --> C[Procurement];
  C --> D[Pick Theater Location];
  D --> E[Pick Mission];
  E --> F[Plan Mission];
  F --> G[GM Builds Mission];
  G --> H[Run Simulation];
  H ----> E;
```

:material-exclamation-thick: You can remain in a Theater of Operations until you wish to move to greener pastures.

:material-exclamation-thick: The Black Market is available in between missions and in between theaters. 

:material-exclamation-thick: Procurement and Procurement Upgrades *only occur initially and in between theaters.*

### Actions

In between picking a mission and planning the mission is preparation. You need to understand the threat, understand the target, and decide how best to execute the mission. Just tossing airplanes into the sky and YOLO'ing it is not the best option. Unforeseen obstacles, SAM sites, or defenses could ruin your day.

!!! Example

    A PMC Group called Maverick's Mutts have a contract to destroy a train travelling between Tallinn and St. Petersburg. They know another PMC is going to be screening the flight and a Russian SAM battalion is operating somewhere near the border. 
    
    Jakob, an Ex-CIA Operative, wants to call in a favor and get a satellite photo. The MC decides he has a +1 due to his relations with the CIA and it's a fairly easy request so he gets a +1 to the difficulty. He defines his first dice as the high, and the second dice as the low.
    
    :material-dice-3-outline: - :material-dice-2: + **1 Skill** + **1 Difficulty** = **3 Critical Success**
    
    Jakob not only gets his satellite map, but an analysts points out a SAM site.


!!! Example
    The Mutts now try to hack the SAM site. Winona, ex Air Force cyber security, is familiar with defending against these attacks but is unfamiliar with the best way to actually hack it. The group notices some power lines on the aerial map. So the MC offers instead that she can attempt to hack the power station near by as an easier option. 

    :material-dice-1-outline: - :material-dice-2: + **2 Skill** + **-2 Difficulty** = **1 Modest Failure**

    Winona is unable to shut down the power station, but the cyber attack has gone unnoticed.

### Planning

The best mission plans are laid out before hand and are flexible enough to allow the MC to plan out the flow. Once the planes have taken off they are on mission profile and **may not be micro-managed.** There are exceptions such as moving flight paths to avoid previously unknown serious threats, RTB'ing (return to base), or when something odd occurs in the simulation.

You are in a command post or a control tower staring at a digital map as the mission unfolds.

![Example Mission Plan](images/missionexample.png)

## Simulation :map: