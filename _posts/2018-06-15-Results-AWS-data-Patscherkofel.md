---
layout: post
title:  "WIP: Impact of artificial snow on the albedo - Results of the AWS data on Patscherkofel"
date:   2018-06-15 12:00:00
author: Zora Schirmeister, Lilian Schuster
---

**Peer-review:** *not peer-reviewed yet!*

[Code used to generate these plots](https://github.com/transparency-lecture/transparency-lecture.github.io/blob/master/_docs/code/patscherkofel_prefinalversion_lowmemory.ipynb)

Two automatic weather stations (AWS) were mounted in the skiing area of Patscherkofel on 23rd of
March 2018 to investigate whether artificial snow has an impact on the change of reflectivity of
shortwave radiation and consequently an impact on the energy budget. For this purpose two CNR4 Net
Radiometer were installed, which measure the incoming and outgoing longwave and shortwave radiation.
First, both were placed in natural finish terrain on snow next to a ski slope. On the 6th of April 2018
one station was moved on the ski slope. The measurement period was from 23rd of March until the 9th
of May. It has to be mentioned that there was a huge amount of natural snow in this winter and we do
not know how much artificial snow actually was produced, so it is hard to quantify how strong the
effect actually is.

## Quality check of the Data and Methods

Due to some battery problems the examination of the data starts with the 28th of March. In figure 1
the incoming and outgoing shortwave radiation of both stations are plotted. The shortwave radiation
follows the typical daily course we would expect. For every time step the albedo was calculated by
dividing the outgoing by the incoming shortwave radiation. Some albedo values were higher than 1 which
is physically impossible. The source of error are disturbances of the upper sensor, which was sometimes
covered by a snow. Moreover the lower sensor receives more shortwave radiation in the morning when
the sun has a low elevation angle and radiates directly in it. These values are excluded. As these
instant albedo calculations for each data point are very sensitive to measurement errors, e.g. extreme
peak by a single measurement, it is better to analyse the daily albedo. For the following it was
calculated by summing the outgoing and incoming radiation over each day and dividing these two
quantities through each other.

[![image unavailable](/img/posts/results_AWS/SW_final.png)](/img/posts/results_AWS/SW_final.png)

## Results

Figure 2 shows the daily albedo of both stations for the measurement period. As we can see the albedo
exceeds 0.7 until the 1st of April, then metamorphosis changes the properties of the snow and the albedo
decreases to values between 0.55 and 0.7 for a period of 15 days. The variations in this time span can be
explained by the change between new snowfall (4th, 8th and 12th of April), which leads to higher albedos,
and warm temperatures that induces transformation processes to the snow.  When melting occurs a layer of
water covers the snow, which has a lower albedo than snow. (Mote, 2008) Afterwards, from 16th of April on,
the albedo decreases continuously until the snow is completely melted. A period of hot days in
comparison to the days before started. The albedo reaches values below 0.2, which belong to snow-free
surfaces (according to the analysis of the Neustift data described in (LINK to Neustift article #####)). The photos of the
dismounting show a muddy surface for Patscherkofel 1 and pasture for Patscherkofel 2.

[![image unavailable](/img/posts/results_AWS/albedo_final.png)](/img/posts/results_AWS/albedo_final.png)

[![image unavailable](/img/posts/results_AWS/dismounting.jpg)](/img/posts/results_AWS/dismounting.jpg)

Until the 5th of April the albedo of both stations is nearly identical. With the relocation of Patscherkofel 2
on 6th of April they start to differ. This could be explained by the expected differences of the snow
properties (artificial snow vs. natural snow), which is supported by the fact that both station show the
same albedo at the 9th of April after a large snowfall. This day can be seen as a reset where both stations
start again under the same conditions. They begin to differ directly after it. Different properties could be
the snow grain size or transmittance. Mote (2008) describes that a larger grain size leads to a higher
albedo. Since we did not measure these quantities, we cannot evaluate their influence.  However also possible
technical problems have to be considered, which could occur due to the relocation, as well as differences
between the sites. The station that is located on the ski slope reaches its minimum albedo two days later than
the other one. There are a few aspects to be taken into account. The snow on the ski slope should be denser
due to the skiers that compress it, and in addition due to the heavy snowcats that distribute extra artificial
snow on it. So the decrease of the snow height by melting is expected to be slower compared to the natural
site since more energy per square meter is needed to melt the same height of the snow. There
were also a few skiers in the area of natural snow, but their impact is considered to be little. Further the
albedo is lower on Patscherkofel 1 (natural site), therefore more energy is absorbed by the snow, which is
used to melt it faster. Unfortunately the stations were installed on different types of grounds. The station
on the ski slope was placed on a pasture whereas the other one stood very close to a small stream, where the
ground was wet and muddy. The darker muddy ground of Patscherkofel 1 has a lower albedo (0.1) than green
pasture on Patscherkofel 2 (0.2). Brock et al. (2000) explains that the underlying albedo influences the
snow albedo when the snow height is below 0.5 cm w.e. . Therefore the melting at Patscherkofel 1 should be
faster since its underlying albedo is lower. We cannot prove this assumption, because we do not know the
development of the snow heights. Moreover it has to be thought about the fact that with the flowing of
the river a melt process from underneath the station could have taken place. We are not
able to know the degree of the influence on the overall melting process. But this could be another reason for
Patscherkofel 1 being snow-free 2 days earlier.

The transition zone between snow covered and snow-free ground is easy to identify in our case, since there
did not occur snowfall events after the complete melting of the snow. This process was fast and without
interruptions.

## Conclusion

With our measurement we detected a difference in the behavior of natural and artificial snow. On the one hand
the ski slope’s snow showed a slightly higher albedo until the continuous melting period started on 16th of
April (between 1 % to 11 %). On the other hand the site of natural snow was faster snow-free, but this
difference is only two days. Probably, this is due to the lower albedo value at the beginning of the
continuous melting period.

The main problem is, that we do not know the mixing ratio of natural and artificial snow on the ski slopes,
and therefore we cannot determine the exact influence of artificial snow on the energy budget. A winter with
less snow would be easier for the analysis. Further the differences of the snow properties are not clear,
besides the density that should be higher on the ski slope as explained before. But according to Brock et
al. (2000) the density should not have a significant impact on the albedo. In addition, the measurements
are only point measurements. It has to be considered that there are differences in the sites, which are
due to amount and number of snowfall, aspect, cloudiness and shadowing.

In further work it would be important to use also sites where the artificial snow stays significantly longer
than the natural. At least the snow height of both stations and a density profile at the relocation date
should have been measured. Then it could be determined whether the delay in the melt process is due to
the albedo, the density or the different snow heights.

## References

Brock, B. W., Willis, I. C., & Sharp, M. J. (2000). Measurement and parameterization of albedo variations at
Haut Glacier d’Arolla, Switzerland. *Journal of Glaciology, 46(155)*, 675-688.

Mote, T. L. (2008). On the role of snow cover in depressing air temperature.
*Journal of Applied Meteorology and Climatology, 47(7)*, 2008-2022.
