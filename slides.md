---
theme: default
colorSchema: 'light'
aspectRatio: '16/10'
fonts:
  sans: 'Nunito Sans'
drawings: 
  persist: false
  syncAll: false
download: true
---

# Rethinking (and challenging) the Ranks of Visual Channels

Reading Group • Friday, March 18, 2022

<!-- https://sli.dev/builtin/layouts.html -->
<!-- https://sli.dev/custom/directory-structure.html -->
<!-- https://sli.dev/custom/#frontmatter-configures -->
<!-- https://fonts.google.com/specimen/Nunito+Sans -->
<!-- https://sli.dev/custom/fonts.html -->
<!-- https://github.com/slidevjs/themes/blob/%40slidev/theme-default%40v0.21.2/packages/theme-default/package.json#L22 -->
<!-- https://sli.dev/guide/animations.html#click-animations -->
<!-- https://github.com/slidevjs/slidev/blob/v0.28.10/packages/client/builtin/Tweet.vue -->
<!-- https://sli.dev/guide/drawing.html#persist-drawings -->
<!-- https://github.com/antfu/talks/blob/master/2021-04-29/src/slides.md?plain=1 -->
<!-- https://github.com/antfu/drauu -->
<!-- https://www.compart.com/en/unicode/block/U+A700 -->
<!-- ꜐ -->
<!-- ꜐ ꜍ -->
<!-- https://sli.dev/guide/animations.html#v-clicks -->
<!-- https://sli.dev/guide/navigation.html -->

---
layout: image-left
image: /cleveland84_page2.png
---

# Cleveland & McGill's Ranking (1984)

↑ "Better"

<v-clicks>

1. Position (common scale) → Scatterplot

2. Position (non-aligned scales) → Multiple scatterplots

3. Length → Bar chart (🧂) or Gantt chart

4. Angle → Pie chart

5. Area → Bubble chart

6. Color luminance → Heatmap

</v-clicks>

---

# Cleveland & McGill's Ranking (1984)

###### Definition

Ranking of the most perceptually precise visual channels estimated from two-value ratio judgment tasks for Data Visualization

"What percentage is the smaller value compared to the larger?"

<v-click>

###### Assumption

This ranking should hold for different tasks and numbers of marks

</v-click>

<v-click>

###### Questions

- Does this ranking hold for other contexts?
- Can we use this ranking as guidelines for Data Visualization?

</v-click>

---
layout: center
---

# Rankings

Cleveland & McGill's Ranking

![Cleveland and McGill's ranking](/cleveland_ranking.png)

---
layout: center
---

# Rankings

Cleveland & McGill's Ranking vs. Probabilistic Rankings

![Cleveland and McGill's ranking vs. probabilistic rankings](/cleveland_new_rankings.png)

---
layout: image-right
image: /2107.11367_page1.png
---

# Rethinking the Ranks of Visual Channels

###### Paper

- Caitlyn M. McColeman, Fumeng Yang, Steven Franconeri, Timothy F. Brady
- Visual Thinking Lab @ Northwestern University et al.
- Featured at IEEE VIS 2021

<v-click>

###### Contributions

1. Two experiments asking users to reproduce values
2. Data analysis via Bayesian hierarchical modeling
3. Probabilistic rankings for three metrics

</v-click>

<v-click>

**And more questions**

</v-click>

---
layout: center
---

<Tweet id="1451954409794150403" />

---
layout: center
---

<div grid="~ cols-2 gap-2">

<Tweet id="1501933645262569474" />
<Tweet id="1501938190118100998" />

</div>

---
layout: cover
---

# Thanks!

Some chart types/visual encodings are more "precise", based on asking people to judge a ratio between two values. The authors asked people to reproduce up to 8 values. Cleveland & McGill's ranking did not hold. The rankings are distinct for a different task, metrics, and numbers of marks.
