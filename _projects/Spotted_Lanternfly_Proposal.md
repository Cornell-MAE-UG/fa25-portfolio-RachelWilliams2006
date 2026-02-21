---
layout: project
title: MAE 2250 - Open Design Project
description: Class Assignment
image: /assets/images/Spotted lanternfly.jpeg
fontsize: 11pt 
geometry: margin=1in 
papersize: letter 
pagestyle: empty
header-includes: 
    - \pagenumbering{gobble} 
--- 
# Spotted Lanternflies 
**Team:** _Sinicus_ 
**Client(s):** _Cornell CALS Extension / E\&J Gallo Winery / National Grape_

---

## Problem statement

Spotted lanternflies (abbreviated SLFs) feed on the phloem of grapevines, which reduces nitrogen and carbon in the roots and soil and affects the taste and size of future grape harvests. If SLFs are left unchecked, they can decimate a vineyard. In addition to the threat of long term damage, the accepted tolerance of SLFs in grape products is low, with only 1–2 SLFs per kilogram of grapes required to reject a 22 ton batch. There is a large influx of SLFs from late August to October, coinciding with peak harvest time. Many pesticides are not effective at controlling SLF populations during harvest due to long pre harvest intervals (7-30 days). SLFs are highly mobile and repopulate in between application and harvest.

---

## Impact
Solving this problem is beneficial to the grape industry, as preventing SLFs from accessing grapevines decreases the number of throwaway batches while improving the quality of present and future harvests alike. Decreasing the number of SLFs in the vineyard preserves the integrity of the current crop of grapes, improving the profitability of harvest. Furthermore, SLFs feed on grapevine phloem, and while healthy vines can produce quality fruit for 50+ years, this useful life diminishes as SLFs cause vine health to deteriorate. Eliminating lanternflies will preserve the health of the vines, prolonging the useful life of the vines and ensuring profitability on a longer time scale. Reducing the general SLF population will address the contamination problem without adding complexity or delaying the harvesting process. 

Although there are already pesticides that are effective at killing SLFs, finding a way to lure them away from the vines before using pesticides would avoid application directly on the vines and make it possible to use a broad range of pesticides with longer pre harvest intervals. According to the Penn State Extension guidance on SLF management, "on average, 54 percent of the SLF population is within the first 50 feet of the vineyard edge." Therefore, a more targeted approach utilizing the unique behavior of SLFs will avoid the need to spray the entire vineyard with generalized equipment like air blast sprayers. 

---

## Proposed Direction

---

#### Electrical Fence Lure and Pesticide Spraying Mechanism (Solution A)

##### How it would be used:
- Research shows that SLFs are attracted to frequencies of 60hz, a common electric fence frequency (Rohde)
- Part 1: Place a 60hz electric fence (low voltage) around the perimeter of the vineyard
- Part 2: Spray the SLFs on the fence with pesticides

##### Why it’s better than the status quo:
- Would allow the use of a broad range of pesticides with longer pre-harvest intervals

##### End-of-semester proof-of-concept:
- Component 1: Electric fence installation method to raise wire above ground
- Component 2: Pesticide spraying mechanism
- Component 3: Shield to prevent overspray of pesticide onto vine

---

#### Electrical Fence Lure with Lethal Voltage (Solution B)

##### How it would be used:
- Instead of killing the SLFs with pesticide, use a high voltage fence (3,000+V wire) to zap SLFs as they land

##### Why it’s better than the status quo:
- Avoids the use of expensive pesticides altogether

##### End-of-semester proof-of-concept:
- Component 1: Electric fence installation method to raise wire above ground
- Component 2: Safety shield to prevent accidental injuries
- Component 3: Proof of the required voltage to kill a SLF

---

## Key Risks / Unknowns

- **Infrastructure investment**
  - New York State has over 30,000 acres of vineyards
  - Many miles of electric fence and pesticide sprayers (for Solution A) would be required

- **Prevention vs targeted harvest solution**
  - No way to sort SLFs from grapes during harvesting if our solution does not completely eliminate SLFs in the vineyard

- **Ecological disturbance**
  - Other insects, including beneficials, may be attracted to the wire frequency and eliminated along with the SLFs
  - The electrified wire could pose harm to larger animals such as deer, raccoons, foxes, rabbits, and other mammals commonly found in the Northeastern U.S.

- **Interaction between the electrified wire and pesticides**
  - Spraying pesticide on an electric fence may have adverse effects

- **Attraction effectiveness**
  - It will be difficult to determine the effectiveness of the wire in attracting SLFs

- **Attracting SLFs from outside areas**
  - The wire may also attract SLFs from areas outside the vineyard

---
  
## Questions for the client 

1. Have there been previous attempts made to lure and trap SLFs?
2. What specific pesticides are being used for insect control in upstate NY vineyards?
3. Do SLFs stay on the same grapevine after landing or will they jump to different grapevine rows?
4. Have you observed how much voltage is required to kill SLF’s or similar bugs?

---

<div style="display:none;">
</div>

## Figure

---

## References
Harner, Andrew D., Heather L. Leach, Lauren Briggs, and Michela Centinari. 2022. “Prolonged Phloem Feeding by the Spotted Lanternfly, an Invasive Planthopper, Alters Resource Allocation and Inhibits Gas Exchange in Grapevines.” Plant Direct 6 (10). <a href="https://doi.org/10.1002/pld3.452">https://doi.org/10.1002/pld3.452.</a>

Petit, Elsa, Zoe Robinson, Jessica Ellis, Max Resnick, Amber Ali, and Sonia Schloemann. n.d. “2021 New England and New York Grape Production Survey.” Fruit Notes 88: 2023. Accessed February 12, 2026. <a href="http://umassfruitnotes.com/v88n1/FN6.pdf">http://umassfruitnotes.com/v88n1/FN6.pdf</a>.

Rohde, Barukh, Miriam F Cooperband, Isaiah Canlas, and Richard W Mankin. 2022. “Evidence of Receptivity to Vibroacoustic Stimuli in the Spotted Lanternfly Lycorma Delicatula (Hemiptera: Fulgoridae).” Journal of Economic Entomology 115 (6): 2116–20. <a href= "https://doi.org/10.1093/jee/toac167">https://doi.org/10.1093/jee/toac167.</a>
