---
title: Deriving ecological indices from LiDAR data
author: JillLehn
date: '2022-01-05'
slug: []
categories:
  - Assessments
tags:
  - Tasks
subtitle: ''
description: ''
image: img/forest.jpg
toc: yes
output:
  blogdown::html_page:
    keep_md: yes
weight: 100
---




## Assessment: LiDAR based Forest Indices

The task of this Assessment is as follows: 

- Read the ressources related to forest and identify those which you will use for attempting the task.
- Decide which algorithms and indices are adequate to answer the research question
- Apply and document this findings with on base of the scripts of the this unit experiences

The research question we are concerned with is as follows: 

Is it possible to derive a suitable set of predictor variables from LiDAR data to obtain a reliable prediction of the microclimate parameters temperature and humidity?


## Read the ressources related to forest and identify those which you will use for attempting the task and decide which algorithms and indces are adequate to answer the research question.

I think the paper of del Río et al. (2016) provides a good review of different measures, indices and methods to characterize the structure of mixed stands, which is a very important factor for the determination of the microclimate. Table 1 on page 26 to 28 shows a lot of indices for characterizing stand structure at stand level in mixed-species stands. These indices are not especially for LiDAR data, but I think some of them could be derived from LiDAR data. 

The stand structure is one of the most important components, which influences the microclimate parameters. So, the stand density can be used to determine the stand structure and numerous measures are used to determine the stand density. A common way and the easiest to describe stand density is the basal area (BA)(del Rio et al. 2016).
The leaf area index (LAI)is also a stand density variable and can be useful to predict the microclimate. Also the stand density index (SDI), which is a common measure for stand density, can be useful to predict the microclimate. The SDI indicates the tree number for a reference quadratic mean diameter (del Rio et al. 2016).
The horizontal spatial pattern is an important attribute of stand structure and  could be also useful to predict the microclimate, because it directly influences many ecological processes in forest ecosystems, including the microclimate parameters. One important measure of the horizontal spatial pattern is the Clark and Evans aggregation index (R). But also the vertical stand structure is an important parameter for the determination of the forest microclimate. To determine the vertical stand structure the tree hight is an important size variable and can be used to descirbe the vertical structure of a stand.Another measure to describe the vertical stand structure is the foliage height diversity (FHD). The FHD based on the proportion of leaf area within various height intervals above ground (del Río et al.2016).

Hashimoto et al. (2004) also used the indices for determine the vertical and horizontal diversity of forest structure. The indices should be estimated from airbone laser scanning data. I think these indices can also be estimated from LiDAR data. As already mentioned above they also use the foliage height diversity (FHD), calculated by five layers (FHD5) and four layers (FHD4). The more equal the proportion of vegetation coverage at every height, the higher the FHD (Hashimoto et al.2004).With the FHD it is maybe possible to predict the microclimate parameters of each vertical storey. 
They also mentioned the crown patchness (CP), which is an index considered both the vertical and horizontal diversity of foliage distribution (Hashimoto et al. 2004).

Another paper of Greiser et al.(2018) deals with microclimate studies in a managed boreal forest landscape. They quantified the influence of vegetation features and physiography on understory temperatures. The study shows that during the warm season, where the microclimate variability is largest, the both indices canopy cover and basal area were the most important microclimate drivers for especially the minimum and maximum temperatures. The physiographic drivers, especially elevation, dominated maximum temperatures during autumn and early winter (Greiser et al. 2018).So it can also be useful to use a digital elevation model (DEM) to predict the microclimate parameters in a forest, especially as mentioned above in the seasons when deciduous trees have no leaves.


## Results

Describe your results with respect to the choosen Approach and with respect to the leading question 

## Discussion
Take your research question and your results and discuss the results with respect to your approach

## References

-del Río, M., Pretzsch, H., Alberdi, I., Bielak, K., Bravo, F., Brunner, A., Condés, S., Ducey, M.J., Fonseca, T., von Lüpke, N., Pach, M., Peric, S., Perot, T., Souidi, Z., Spathelf, P., Sterba, H., Tijardovic, M., Tomé, M., Vallet, P. & Bravo-Oviedo, A. (2016): Characterization of the structure, dynamics, and productivity of mixed-species stands: review and perspectives. Eur. J. Forest Res. 135, 23-49.

-Greiser, C., Meineri, E., Luoto, M., Ehrlén, J. & K. Hylander (2018): Monthly microclimate models in a managed boreal forest landscape. In Agricultural and Forest Meteorology 250 - 251 (2018) 147 - 158. doi:10.1016/j.agrformet.2017.12.252.

-Hashimoto, H., Imanishi, J., Hagiwara, A., Morimoto, Y., & K. Kitada (2004): Estimating forest structure indices for evaluation of forest bird habitats by an airbone laser scanner.In M. Thies, B. Koch, H. Spiecker, & H. Weinacker (Eds.), Laser scanners for forest and landscape assessment: Proceedings of the ISPRS Working Group VIII/2, Freiburg, 3-6 October 2004, 254-258.



