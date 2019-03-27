+++
title = "Try Markdown"
subtitle = ""

# Add a summary to display on homepage (optional).
summary = ""

date = 2019-03-26T00:08:10-04:00
draft = true

math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Is this a featured post? (true/false)
featured = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

# Publications
_He, Chong-Chong_ & Keek, Laurens 2015, ArXiv e-prints: 1512.02889 [Anisotropy of X-ray bursts from neutron stars with concave accretion disks](http://adsabs.harvard.edu/abs/2015arXiv151202889H) submitted to ApJ  

# X-ray Bursts from Accreting Neutron Stars
Emission from neutron stars and accretion disks in low-mass X-ray binaries (LMXBs) is not isotropic. Recently, discrepancies between observations and previous models about angular distribution of radiation from LMXBs are found. We develop numerical models to compute the anisotropy factors of radiation from neutron stars with concave accretion disks and, for the first time, give an explanation to the observations.

Because part of the X-ray burst is reflected off the disk, the observed burst flux has two distinguishable components: direct burst flux ($\xi\_i$) ($\xi\_{\rm d}^{-1}$) and reflected burst flux ($\xi\_{\rm r}^{-1}$). This influences measurements of source distance, mass accretion rate, and constraints on the neutron star equation of state. This is of special importance for the interpretation of Type I X-ray bursts.

## Previous Models
Previous studies made predictions of the anisotropy factors for burst flux, assuming a geometrically flat disk (top). In this case, the ratio of the reflected and direct burst flux ($\xi\_{\rm r}^{-1}/\xi\_{\rm d}^{-1}$, or the reflection fraction) peaks at $0.5$ (bottom left). Recently, however, detailed observations showed that the reflection fraction could reach to ~6 (another observation is ~3) at the tail of a superburst (bottom right), which is much higher than what a system with a flat disk can account for.

## Our New Model
We create numerical models to calculate the anisotropy factors for different disk shapes, including concave disks (top). We present the anisotropy factors of the direct and reflected burst flux separately, as well as the anisotropy of the persistent flux (bottom right). Reflection fractions substantially larger than unity are produced in case the inner accretion disk steeply increases in height, such that part of the star is blocked from view (top). Such a geometry could possibly be induced by the X-ray burst if X-ray heating causes the inner disk to puff up. The bottom left figure shows the distribution of radiation on the disk observed from a line-of-sight angle $\theta=58^\circ$ with respect to the rotation axis of the disk. The dark region of the disk is blocked from the line of sight. We can see that the puff-up of the disk blocks half of the disk and most of the star, which causes the reflection fraction to raise to a large value.

## Relativistic Effects
Due to its compactness, a neutron star’s surface gravity is extremely strong, and light bending occurs in its vicinity. In our code we trace the photon paths in the Schwarzschild metric. We investigate the influence of relativistic effects on the distribution of radiation on the disk and find an increase of $\sim 12\%$. Relativistic effects are neglected in other parts of our study because this increase is small compared to the large changes in reflection fraction that we are interested in.

