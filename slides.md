---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Sample slides
#### PlaceHolderName
#### Universiti Malaysia Perlis
#### [placeholder@email.com](mailto:placeholder@email.com)

<!-- __AUDIO_INTRO_DO_NOT_TOUCH__ -->

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### Machine 1: Pressure Impact
**ANOVA Analysis (PartResistance):**

- **p-value (Pressure):** 0.0000e+00
- **Is Pressure Significant?:** Yes

**Observations:**
We assess how pressure changes affect the product's resistance relative to the USL of 10. Lower resistance is preferred.

Using dataset `X008..3.`
:::

::: {.column width='50%'}
<iframe data-src='media/plots/m1_res_p_usl.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### Machine 1: Temperature Significance
**ANOVA Analysis (PartResistance):**

- **Pr(>F) for Temperature:** 0.4964
- **Is Temperature Significant?:** No

**Observations:**
We assess if varying the temperature significantly alters product resistance. Lower resistance is better, with the Upper Specification Limit (USL) set at 10.

Using dataset `X008..3.`
:::

::: {.column width='50%'}
<iframe data-src='media/plots/m1_res_t_usl.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
