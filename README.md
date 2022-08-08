# Would planting trees in desert areas reduce the global temperature?

Our generation is asked to solve one of the most difficult issue ever faced: Global Warming. 
Although most of worldwide governments during last COP26 pledged for zero net emissions[[1]](#1), the activist GretaThunberg claimed that "It is not a secret that COP26 is a failure. 
It should be obvious that we cannot solve the crisis with the same methods that got us into it in the first place" [[2]](#2). 
For this reason, we should consider alternative methods, and planting trees could be one of those.

## Introduction
Since the industrial revolution the world is getting hotter, and today we are already at +1.2°C relative to 1800s. The most optimistic COP26 scenario put us at +1.8°C, but realistically we are on track to +2.7°C [[3]](#3), which would translate in a series of irreversible climate effects, e.g. ice sheets melt, sea level rise and biodiversity lost. If we want to avoid a climate disaster, we need to act bold now.
Greenhouse gases emissions, and in particular Carbon Dioxide(CO2), are the main driving force of temperature increase, which started to rise since the 1850s due to human activities. For this reason in this notebook we use as explanatory the CO2 emission to predict the future increase in temperature. Whereas, there exist several complex climate models, this notebook has been developed for educational purposes. The main goal of this project is to use machine learning to understand different mitigation strategies. We want to understand if planting trees could represent a valuable strategy to sequester enough CO2 to contain global warming.

## What happens if CO2 stops by 2050?
### Scenario 1 | A continuous increase of gas emissions by 2050
In the first scenario, we predict the consequences if no actions are undertake to tackle the global warming issue. Additionally in scenario 1B we will consider the consequences if we plant trees that sequester 42GtC of CO2, while in scenario 1C, we increase this amount up to 107 GtC.

<p align="center"><img src="https://drive.google.com/uc?id=1BpLMNZpPd9CHqlBxLP80ycxvo9D4ntmm"></p>

As we can see from the image above, we are not able to meet the 1.5°C threshold and neither the 2.0°C. For this reason, we should implement not only techniques that sequester CO2, but also decrease the global emissions.

### Scenario 2 | A realistic decrease of gas emissions by 2050
In this scenario, we want to take into account a realistic decrease in emission, from 100% to 69% over the period 2020-2049. At the same time, we will do the same assumption done before, therefore in scenario 2B we will plant trees for a CO2 sequestration of 42 GtC, while in scenario 2C we will seques- trate 107 GtC. To implement the global CO2 reduction, we will use the formula shown below

<p align="center"><img src="https://drive.google.com/uc?id=1QPS0A56cvgQSqXkyovDII_1z2nBkEzCb"></p>

From the image above we can observe that only in scenario 2C, which represents the best case scenario in matter of CO2 sequestration, we are able to meet 2.0° threshold by the 2050.



### Scenario 3 | Zero-carbon by 2050 with/without a trillion trees planted
In scenario 3, we applied a linear function in order to see if the world reach net zero emission by 2050, which is a mission of many countries. As in previous cases, in scenario 3B and 3C, we would take into account of planting trees, which respectively would sequester 42 GtC and 107 GtC of CO2.
<p align="center"><img src="https://drive.google.com/uc?id=1zxSnUYv1INvv8OsdoE6wm2IsOP8vdj9X"></p>
As we can observe, if we reach zero emission by 2050, we are able to achieve the goal to contain temperature below 1.5°C threshold. The same happens in the scenario 3B and 3C, which in both the in cases they present improved situations compared to scenario 3A.

### Scenario 4 | How much do we have to decrease gas emissions to remain under 1.5 degrees
In this scenario, we want to find the minimum decrease of gas emissions required such that the global average temperature remains under 1.5 degrees, with and without trees absorption.

<p align="center"><img src="https://drive.google.com/uc?id=1cZwsaCzV2iH_7p_OPzlpQKsOIKkmPtKP"></p>

From our computations, we obtained that we need to decrease the amount of CO2 to 16%, if we want to achieve the 1.5°C threshold by 2050. The situation is even better in 4B and 4C, where we sequester CO2

## Collaborators
- [Dario Scalabrin](https://www.linkedin.com/in/scalabrindario/)
- [Filippo Giustiniani](https://www.linkedin.com/in/filippo-g-0b5583131/)
- [Lorenzo Vella](https://www.linkedin.com/in/lorenzo-vella-a024721bb/)


## References
<a id="1">[1]</a> What happened at COP26?, Green Peace, Published on 17 November 2021, Accessed on 18 December 2021, https://www.greenpeace.org.uk/news/what-happened-at-cop26/ <br>
<a id="2">[2]</a> 'COP26 is a failure': Greta Thunberg says climate summit has turned into a PR event, CNBC, Published on 5 November 2021, Accessed on 18 December 2021, https://www.cnbc.com/2021/11/05/greta-thunberg-says-cop26-climate-summit-is-a-failure-and-a-pr-event.html <br>
<a id="3">[3]</a> IPCC, 2021: Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press. In Press. <br>
<a id="4">[4]</a> The ancient trade holding back the Sahara Desert, BBC, Published on 25 September 2020, Accessed on 18 December 2021, https://www.bbc.com/future/article/20200924-africa-how-gum-arabic-could-hold-back-the-sarah-desert <br>
<a id="5">[5]</a> Devaranavadgi, S. B., Pradeep, R., Wali, S. Y., & Madiwalar, S. L. (2012). Height-age growth curve modelling for different multipurpose tree species in drylands of north Karnataka. International Journal of Forestry and Crop Improvement, 3(1), 1-7.<br>
<a id="6">[6]</a> Growing Acacia, Herbazest, Published on 18 June 2020, Accessed on 18 December 2021,  https://www.herbazest.com/herb-garden/growing-acacia <br>
<a id="7">[7]</a> Trees help tackle climate change, European Environment Agency, Published on 06 January 2012, Accessed on 18 December 2021, https://www.eea.europa.eu/articles/forests-health-and-climate-change/key-facts/trees-help-tackle-climate-change

## License 
[MIT](https://choosealicense.com/licenses/mit/)

