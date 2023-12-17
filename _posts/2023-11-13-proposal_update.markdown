---                                                                             
layout: post                                                                    
title:  "Updated project proposal: Real-Time Mesh Compression"
date:   2023-11-13 22:51:18 -0800                                               
categories: update, proposal                                                              
---                                                                             

## Motivation
Polygon meshes are common in multimedia applications such as computer animation, video game graphics, virtual reality, and 3D printing. As polygon meshes increase in size and become more widespread, the world of polygon mesh compression becomes increasingly relevant.

Why compress meshes? Like most files, meshes are often transmitted over the Internet. Compressed meshes are easier to exchange, and take up less space on disk, at the cost of increased mesh load times and possible compression artifacts. Real-time compression for meshes benefits rendering for multimedia with a low tolerance for delay. Thanks to compression, more complex geometry can be rendered, and load times for large meshes can be decreased.

## Goal
Explore current polygon mesh compression algorithms and current approaches to real-time mesh compression. Summarize common challenges that arise when implementing real-time compression of meshes and implement a compression algorithm. Discuss if the implemented algorithm is applicable to real-time mesh compression.

## Previous Research
# What has been done?

| Connectivity compression (of mesh structure) |
| Geometry compression (of vertex coordinates) |
| Progressive mesh compression (more levels of detail over time) |
| Random accessible compression (for large meshes) |
| Real-time compression (eg. [Nanite](https://docs.unrealengine.com/5.0/en-US/nanite-virtualized-geometry-in-unreal-engine/)) |

# Why are they not sufficient?
As mesh compression continues to evolve, complex meshes continue to encounter limits in storage, rendering, and transmission. To address these challenges, better compression formats must be developed.

## Deliverables

# - Research and development logs (project website)
# - Project proposal
# - Midterm update
# - Project demo (partial algorithm implementation)
# - Project report

## Timeline

| Week | Deliverables |
|------|--------------|
| W6 | Oct 9: Project proposal (1 page, double spaced, single column) |
| W7 | Refine deliverables and timeline | 
| W7-8 | Researching DASH and WebM, search for additional topics |
| W10 | Nov 9: Midterm update |
| W11 | Nov 13: Updated project proposal |
| W14 | Dec 4: Project demo |
| W14 | Create the final project report |
| W15 | Dec 11: Project report (10 pages, double spaced, single column) |

## References
[1] A. Maglo, G. Lavoué, F. Dupont, and C. Hudelot, “3D Mesh Compression: Survey, Comparisons, and Emerging Trends,” ACM computing surveys, vol. 47, no. 3, pp. 1–41, 2015, doi: 10.1145/2693443.

[2] “Nanite virtualized geometry,” in Unreal Engine \| Unreal Engine 5.0 Documentation, <https://docs.unrealengine.com/5.0/en-US/nanite-virtualized-geometry-in-unreal-engine/> (accessed Nov. 13, 2023).
