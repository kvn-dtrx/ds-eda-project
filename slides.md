---
marp: true
theme: uncover
class: invert
math: mathjax
size: 4:3
---

#### An Analysis of the House Sales Prices in King County

for

##### Miss Amy Williams

## 🏠 👑 🏠

<span style="font-size: 14px; color: hotpink">

**Kevin Dietrich**
2025-03-17

</span>

---

# Getting Familiar with the Data Set ...

---

#### HYPOTHESIS #1

### The more bathrooms, the more bedrooms.

Is it true???

---

###### ??? The more bathrooms, the more bedrooms. ???

#### <span style="color: hotpink">YES!</span>

![Scatterplot Bathrooms vs. Bedrooms width:500px height:400px](./plots/bathrooms-vs-bedrooms.png)

###### [Correlation $\approx$ 0.5]

---

#### HYPOTHESIS #2

### The presence of a waterfront affects the prize.

Is it true???

---

###### ??? The presence of a waterfront affects the prize. ???

#### <span style="color: hotpink">YES!</span>

![Scatterplot Bathrooms vs. Bedrooms width:600px height:375px](./plots/price-on-waterfront.png)

---

#### HYPOTHESIS #3

### The latitude and the longitude of a house location do not affect each other.

Is it true???

---

###### ??? The latitude and the longitude of a house location do not affect each other. ???

#### Probably <span style="color: hotpink">YES!</span>

![Scatterplot Latitude vs. Longitude width:500px height:375px](./plots/lat-vs-long.png)

###### [Correlation $\approx$ -0.1]

--- 

### Our Client

> Amy Williams, Seller, Mafiosa, sells several central houses (top 10%) over time, needs average outskirt houses over time to hide from the FBI.

> NO!!!

--- 

### Our Client

> ~~Amy Williams, Seller, Mafiosa, sells several central houses (top 10%) over time, needs average outskirt houses over time to hide from the FBI.~~


> NO!!!

---

Corrected Description

### ⇒ How to define ...

- (top 10%) **centrality**?
- **exceptionality** (on the outskirts)?
- "**privacy**" (on the outskirts)?

---

### How to define ...

- (top 10%) <span style="color: hotpink">**centrality**?</span>
- **exceptionality** (on the outskirts)?
- "**privacy**" (on the outskirts)?

---

### (Top 10%) Centrality?

<span style="font-size: 20px;">

Take the number of neighbours in a vicinity of fixed size!

</span>

![Scatterplot Latitude vs. Longitude width:500px height:400px](./plots/centrality-plot.png)

###### ⇒ Sell "green" and buy "red" houses!

---

### How to define ...

- (top 10%) **centrality**?
- <span style="color: hotpink">**exceptionality** (on the outskirts)?</span>
- "**privacy**" (on the outskirts)?

---

### Exceptionality?

<span style="font-size: 20px;">

A house is more exceptional the more it differs from its immediate neighbours in terms of living space and lot size!

</span>

![Scatterplot Exceptionality width:600px height:400px](./plots/exceptionality-plot.png)

###### ⇒ Avoid regions indicated by cursor!

---

### How to define ...

- (top 10%) **centrality**?
- **exceptionality** (on the outskirts)?
- <span style="color: hotpink">**"privacy"** (on the outskirts)?</span>

---

### Privacy

<span style="font-size: 20px;">

Take the presence of a basement!

</span>

![Scatterplot Privacy width:600px height:400px](./plots/privacy-plot.png)

###### ⇒ Avoid regions indicated by cursor!

---

# <span style="color:hotpink">... The End.</span>
