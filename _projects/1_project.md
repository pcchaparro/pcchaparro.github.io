---
layout: page
title: Evolutionary ecology of ecosystem resilience
description: Although environmental change triggers both ecological and evolutionary responses, the framework used to assess ecosystem resilience has lacked the evolutionary component thus far. To contribute towards the closure of this gap, I have developed the first generation of models that include evolutionary processes.
img: assets/img/delayed_shift.jpg
importance: 1
category: work
related_publications: true
---

According to traditional ecological theory, when environmental conditions are favorable (i.e. low environmental stress), the ecosystem is in the upper branch (State A in figure 1). If conditions gradually deteriorate, the ecosystem follows the stable equilibrium line until conditions exceed threshold 1. At this point (TP1), the upper stable equilibrium disappears, and thus a slight increment in the magnitude of environmental stress causes the ecosystem to tip to the lower branch (State B). Most efforts to prevent ecosystem regime shifts therefore focus on maintaining environmental stress below a safe magnitude, in this case, below threshold 1 (TP1). If this magnitude is exceeded, to restore the tipped ecosystem, it is not sufficient to reduce environmental stress below threshold 1, but to a much lower level of stress indicated by threshold 2 (TP2). Once the magnitude of environmental stress is below threshold 2, the ecosystem quickly recovers back to State A.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bifurcation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1. An ecosystem is bistable when two different stable equilibrium states (solid lines) occur for the very same set of environmental conditions, separated by an unstable equilibrium state (dashed line).
</div>

### Example of Sub-Heading 1

Jean shorts raw denim Vice normcore, art party High

I, with a diverse group of collaborators, discover that the introduction of trait dynamics mediated by evolution violates this paradigm in different manners:

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
