# Projectile Curve Visualizer In Unreal

A plugin for rendering projectile paths in Unreal Engine.

## Description
Demo: https://youtu.be/eSuS6wh88DU

Setup: https://youtu.be/IBss09hBqu4

This visualizer was implemented using pure blueprints, responsible for the visual part of projectile curve. The actual projectile Actor template is also provided.

Demo maps include:
1. Third-person projectile: Player can aim and throw projectiles.
2. Third-person puzzle: Projectiles can be used as a bridge(has collision) like some magic.
3. Top-down tower defense(paper ball fight): Target location is already known, throwers will launch projectiles exactly to that point. Certain heuristic(thrower can predict the possible target location at real-time) is implemented for both moving thrower and moving target, which makes it more difficult to dodge.

## Technical details

Features:
* Lightweight
* Customizable
* Mobile friendly

\
Supported versions: UE 4.25.4 or newer

\
Supported Platforms:
* Windows
* macOS
* Linux
* Android
* iOS

\
Number of Blueprints: 2

Number of Materials: 4

Number of Textures: 5

Input: Keyboard, Mouse

Network Replicated: No

Supported Development Platforms: Windows, macOS, Linux

Windows: Yes

Mac: Yes

\
Documentation: https://docs.google.com/document/d/1SsKAIxYNEgQCIWwuFkt8w6nHjrQPHeUohhYoygwLtJg/edit?usp=share_link