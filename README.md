# Star Wars Universe Data

This repository contains data on the different types of planets, factions, and characters in the Star Wars universe. The data is organized into three classes: Planet, Faction, and Character.

## Planet Class

The Planet class represents the various types of planets in the Star Wars universe. Planets are classified based on their distance from the center of the galaxy, and the following categories are distinguished:

- CorePlanet: These are the planets closest to the center of the galaxy and represent the main political and economic centers.
- InnerRimPlanet:
  - Planets located between CorePlanet and MidRimPlanet.
  - Highly populated and developed, with a mix of advanced and traditional technology.
  - Important cultural centers and often play a significant role in galactic politics.
- MidRimPlanet:
  - Planets located between the inner and outer edges.
  - Often less developed and less populated than Inner Rim planets.
  - Significant role in the galactic economy and politics.
  - Often the site of conflicts between different factions.
- OuterRimPlanet:
  - Planets located farthest from the center of the galaxy, on the edge of the Star Wars universe.
  - Often less developed and less populated than other regions.
  - Host criminal elements or independent settlements.

## Faction Class

The Faction class represents the various organizations in the Star Wars universe. These organizations are differentiated by their nature of activity and other characteristics. There are three subclasses:

- MilitaryFaction: This class represents organizations that have a military presence.
  - Army: Represents professional or mercenary armies controlled by different political organizations such as The Galatic Republic or The Galactic Empire.
  - Order: Includes groups of individuals who share a specific set of beliefs, values, and practices. There are several different orders in the Star Wars universe, each with its own unique characteristics and purposes, such as The Jedi Order and The Sith Order.
- PoliticalFaction: This class refers to political organizations with administrative roles. It includes totalitarian (Authoritarian) or democratic (Democratic) regimes.
- ReligiousFaction: Includes religious organizations. These have as their primary purpose the practice of a belief. The difference between this class and the Order class is that these religious organizations do not have a military activity.

## Character Class

The Character class represents the various characters in Star Wars. This class has the following structure:

- Human: Represents characters who are humans.
- Alien: Represents characters who are extraterrestrials. This is subdivided into the different species of extraterrestrials.
- Droid: Represents characters who are androids or of a mechanical nature.

# How to use
To use the ontology, you need to have Protege installed on your system. Once you have installed Protege, you can load the ontology and run queries using the defined properties and relationships. With these queries, you can explore the classes and their relationships to gain a better understanding of the Star Wars universe.