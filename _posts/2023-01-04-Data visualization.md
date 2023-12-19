---
title: 4 - Data Visualization
author: Kartik Pradeepan
category: Jekyll
layout: post
---

Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and projections, data visualization provides an accessible way to see and understand trends, outliers, and patterns in data. In storytelling, this translates to a narrative that is driven by facts and figures, presented in a way that is both comprehensive and engaging.


## Choosing a visualization type
The purpose of data visualization is to emphasize observations that would not otherwise jump out when looking at a list of values to enable people to quickly and easily grasp your data.

**What is your data trying to communicate?**
Are you trying to convey differences between the distribution of two groups? Change over time? Correlation between between two variables? A pattern? Individual or group differences?

**What kind of data do you have?** Numerical? Categorical? Continuous? Discrete?

**Who is the audience?** Experts in your field? Outsiders to the field? Lay audience?


## Elements of charts

### Layout (panels, subplots, facets)

### Aspect ratio

### Lines

### Points

### Colours

### Axes

### Symbols

### Legends

### Orientation

### Font

### Saving your plot
    

# Examples
## Creating raster plots
![img](../../../_posts/img/raster.png)
<details>
<summary>Python</summary>
{% highlight python %}
plt.figure(figsize=(10,5))
plt.rcParams.update({'font.size': 12})
plt.rc('axes', linewidth=1)
plt.eventplot(raster, color='black', linelengths=0.5, linewidths=0.75, alpha=0.35);
plt.xlim(150, 200)
plt.ylabel("Channels")
plt.xlabel("Time (s)")
{% endhighlight %}
</details>