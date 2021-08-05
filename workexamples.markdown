---
layout: page
title: Work Examples
permalink: /examples/
---

Welcome to my work examples.  In this page, you will find several videos of recent
research and example works that I commonly perform.  Please enjoy!

<h1>Detection and Distributions of Fronts and CO2 Gradients in Models</h1>

<h2>SP-CESM</h2>

Below is an example of Frontal Detection and CO2 gradient estimation along fronts using methods
adapted from Hewson 1997.  This encompasses 1 month of hourly data generated from the SP-CESM.  This model uses super-parameterization, which is a fancy term that essentially means to remove all standard convective/sub-grid scale (SGS) parameterizations and replace them with a 2-D curtain of cloud resolving models.  I adapted the code to handle tracer transport through the CRMs.

<iframe width="560" height="315" src="https://www.youtube.com/embed/KBFaTbXvTj0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Below is a simple means to view the vertical distribution of the CO2 gradients along fronts within the SP-CESM.  These are "violin" plots.  These are nice because at each model level we can summarize the kernel density in color (i.e., probability) and see the underlying gradient distribution (i.e., the box-and-whiskers).   The easiest thing to take away from this is that CO2 gradients in SP-CESM extend throughout the troposphere along fronts.  Some, especially those near the surface, are as strong as those found in observational records.  Lastly, they get weaker with height and more of the density is focused toward similar values, which is expected.  Comparisons with other models will occur soon.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ui5Z0DlbVGY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h2>Identical Weather SP-CESM</h2>
Below is an example of Frontal Detection and CO2 gradient estimation along fronts using methods
adapted from Hewson 1997.  This encompasses 1 month of hourly data generated from the SP-CESM using the identical weather set-up.  This means all weather is generated through the CRMs as in SP-CESM, but the tracer transport is handled through the standard bulk convective/SGS parameterizations.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pgnQqEou4rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Below is a simple means to view the vertical distribution of the CO2 gradients along fronts within the SP-CESM.  The easiest thing to take away from this is that CO2 gradients in IW-CESM extend throughout the troposphere along fronts as with the other simulations.  They get weaker with height and more of the density is focused toward similar values, which is expected.  Comparisons with other models will occur soon.

<iframe width="560" height="315" src="https://www.youtube.com/embed/CJCngoi5d1U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h2>SP-CESM and IW-CESM difference</h2>
Same notation as the previous violin plots (This is SP - IW, or <0 indicates SP > IW).  Note while the difference SP and IW do have plenty in common (large bulges near zero in the probability distribution), SP has substantially more distribution of higher CO2 gradients as noted by the often larger negative tails in the distributions.

<iframe width="560" height="315" src="https://www.youtube.com/embed/yWuxygCog4Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h2>Standard CESM</h2>
Below is an example of Frontal Detection and CO2 gradient estimation along fronts using methods
adapted from Hewson 1997.  This encompasses 1 month of hourly data generated from the CESM2.0.  This model used all standard packages and parameterizations.  Nothing fancy.

<iframe width="560" height="315" src="https://www.youtube.com/embed/bojTLqOKiqs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<h1>Example of Superparameterized Transport of CO2 within CESM</h1>
<iframe width="560" height="315" src="https://www.youtube.com/embed/6RX_Zbc9lC0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h1>Fortran</h1>
<h1>IDL</h1>
<h1>PYTHON</h1>
<h1>NCL</h1>
