# C-Cubed - an Open Source Chicken Coop Controller

Although C-Cubed is (or will be, at any rate) an electronic chicken coop controller for small chicken coops, it's really more than that.  It's a curriculum on *how* to build it.  Not just how to assemble it, but how to go from "I don't know how to code, and I don't know anything about electronics" to "I created a controller for my chicken coop that works and survives year-round in an actual chicken coop".  We will try to segment out the process to allow you to jump in at any level depending on your knowledge and experience, so even seasoned, experienced makers can still get something from it (even if it's just schematics and a board layout).

We are just starting this project, and it's being driven by people with day jobs and full-time school, so if you're here at the outset, don't expect to see a completed project in a couple weeks.  This is going to take time.  If you have ideas, file Issue.  If you have code (when we get that far), submit a [PR](doc/glossary.md#P).

Foremost, though, remember our two goals: 

1. Learn 
2. Have Fun

## Help Wanted

- **Designer:**  While we will be building all of this hardware and software, it would be nice if everything was also pleasing to the eye. If you'd like to contribute, we'd love the help.
- **Copy Writer:** Documentation is difficult and takes lots of time to be right, up-to-date and accessible to all.  We (ok, I) hate writing documentation.  If you like it, we'd love the assist.
- **Tester:** A general truth is those who write code are terrible at testing their own code.  They tend to test in the same thought pattern that created the code, and therefore "bad" code paths get missed.  If you want to help test, let us know!
- **Users:** In order to make the project and content better, feedback on anything is appreciated.

## General Requirements

These are very fluid right now as we will start to ideate on what this controller will (and will not) do.  But broadly speaking, these are the features we'll be targeting

### Version 1 (v1)

- Monitor temperature outside the coop
- Monitor temperature inside the coop
- Monitor humidity inside the coop
- Control a heater inside the coop based on temperature to keep the birds warm
- Control a heater inside the coop to prevent water freezing
- Control an exhaust fan for ventilation/cooling
- Control a door

Controlling of external devices will be done with [relays](doc/glossary.md#R) controlling standard outlets, allowing users to just plug in commercially available thngs like heaters and fans.

### Version 2 (v2)

- Provide a [display](doc/glossary.md#D) or remote app to allow changing [set points](doc/glossary.md#S)
- Collect and store [telemetry](doc/glossary.md#T) data
- Provide remote access to that data
- Add a camera

## Epics

An "epic" is simply a large chunk of work that needs to be done.  Think of it as a group of tasks that need to be done to complete a feature.

### Layout the basic controller hardware
### Write the basic controller software
### Design a [PCB](doc/glossary.md#P)
### Design an enclosure
### Assemble and Debug

## Tools

We will attempt to support multiple platforms, but since the core team has their own preferences, many of the tools and choices will be based on those.  The broad look at the tools we use is below.  For details of exact components, etc. take a look at the Bill of Materials

- Microsoft Visual Studio 2022
- C# Development Language
- Wilderness Labs Meadow [Microcontroller](doc/glossary.md#M)
- Fusion 360
- Lulzbot TAZ6 3D Printer

## Bill of Materials

[TBD]