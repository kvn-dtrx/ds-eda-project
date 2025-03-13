---
title: Hypotheses (Definitions?)
author: kvn-dtrx
---

Recall that our client's description (which is in some places denigrating in her and her lawyer's opinion) was as follows:

<div style="text-align: center;">
  Amy Williams | Seller | Mafiosi, sells several central houses (top 10%) over time, needs average outskirt houses over time to hide from the FBI.
</div>

By detokenising the demands of our client, we see that we have to answer the following questions:

1. What is a good statistical measure for the **"centrality"** of a house?
2. When is a house on the outskirts considered to be **average**?

A house should be located on the outskirts precisely if it has a low "centrality" measure.

# Ad "Centrality"

As a first approximation, we will ignore matters of curvatures and consider earth as (locally) flat. We will treat latitude and longitude as if they were lengths (we are not in Arctic zones).

## Version #1: Distance from the Barycentre

Let $M$ be the barycentre of all house locations. Then, we could say that house $H$ is more central than house $L$ if the distance from $H$ to $M$ is less than the distance from $L$ to $M$. As distance, one could choose the usual Euclidean distance.

## Version #2: Number of Neighbours

Let $A$ be a fixed area like a disk or a rectangle. Then, we say house $H$ is more central than house $L$ if the area $A$ centred around $H$ contains more houses than the area $A$ centred around $L$.

# Ad "Averageness"

**TODO** Fill the gaps.
