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

---

:::: {.columns}
::: {.column width='50%'}
### Machine 1: Interaction (P*T)
**ANOVA Analysis (PartResistance):**

- **p-value (Interaction):** 0.8862
- **Significant Interaction?:** No

**Observations:**
This analysis determines if the effect of pressure on resistance varies across different temperature levels. The USL is set at 10.

Using dataset `X008..3.`
:::

::: {.column width='50%'}
<iframe data-src='media/plots/m1_res_pt_inter.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
