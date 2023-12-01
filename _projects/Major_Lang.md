---
name: Language Family Distribution and Vulnerabilities
tools: [Python, HTML, vega-lite]
image: assets/pngs/indoeurop.png
description: This is a distribution to see how language families are distributed and their vulnerabilities to extinction.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Major language family distribution
## Created by : Aastha and Utsav


### Indo-European
![Indo-European](/assets/pngs/Finals/Indo-European.png)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Indo-European.json" style="width: 100%"></vegachart>

### Afro-Asiatic
![Afro-Asiatic](/assets/pngs/Finals/Afro-Asiatic.png)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Afro-Asiatic.json" style="width: 100%"></vegachart>

### Atlantic-Congo
![Atlantic-Congo](/assets/pngs/Finals/Atlantic-Congo.png)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Atlantic-Congo.json" style="width: 100%"></vegachart>

### Austronesian
![Austronesian](/assets/pngs/Finals/Austronesian.png)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Austronesian.json" style="width: 100%"></vegachart>

### Sino-Tibetan
![Sino-Tibetan](/assets/pngs/Finals/Sino-Tibetan.png)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Sino-Tibetan.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/utsavm2/Language_Visualization/tree/main/Final_Project/Data" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/utsavm2/Language_Visualization/blob/main/Final_Project/Code/Language_viz.ipynb" text="The Analysis" %}
</div>