---
title: Pathfinding
date: 2024-04-30
layout: post
---

Simplex noise generated map with dark green representing trees (passable but more expensive) and light green being open grass.  There are also some rocks in there (gray) which are very expensive to pass through.

The pathfinding searches the neighborhood of each move for cost (with linear falloff) so that it prefers open spaces. When adding roads and paths to procedrually generated maps this may feel more natural as humans would tend to the open space rather than hugging each individual corner.

![image](https://github.com/ridleywinters/ridleywinters.github.io/assets/65878718/af68dc4f-eabf-4d09-ae2b-991e40107c35)
