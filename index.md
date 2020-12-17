# Influence of housing on education, health & happiness

Have you ever wondered where you would be now if you had grown up in a different environment? Would you be healthy? More successful in your studies? Happier?

>*How do your living conditions affect your life?*

This is the question we asked ourselves after reading how Mexico managed to improve children's health and their mother's happiness by replacing dirt floors with cement, in a program called [_Piso Firme_] (https://www.aeaweb.org/articles?id=10.1257/pol.1.1.75).[1]

Indeed, achieving such results with only a bit more than 150$ of cement per household seemed rather encouraging, but this led us to wonder:

*__<div align="center"> What impact has the housing environment on education, health & happiness? </div>__*

### What, where, who, when ?

To try and answer that vast question we decided to focus on three main research axes.

* Which life outcome (education, health or happiness) is most affected by which housing conditions?

* What is the effect of precarious housing on health (both physical and mental) and school involvement for children?

* Are there differences in the effects of precarity between different age groups ? If so, for which outcomes ?

To conduct this study, we opted for a subset of the data from the [National Survey of America's Family] (https://www.icpsr.umich.edu/web/ICPSR/studies/4582) of 2002, to see the perspective from the other side of the frontier, in a similar timeframe as _Piso Firme_ (the program started in 2000). We combined data from children aged 6 to 17 and their respective households.

This dataset recenses a large number of households throughout the USA, providing insight on their demographics and health indicators of the inhabitants.

**_PLOT DES CHOSES POUR PRESENTER LE DATA?_**

## General influence of living conditions on education, health and mental health

First, let's have a look at which housing conditions impacts which life outcome the most.

### How ?

To find the relationship between housing conditions and education, health and mental health, we perform linear regressions. Living conditions are defined as a number of various indicators such as housing (own or rent, overcrowding), family situation (structure, relationship with parents, parents mental health), income, extrascolar activities and personal caracteristics (sex and age).

### 1. Education

Our indicator for education is measured on a school engagement scale, higher score meaning greater engagement in school (for example, a child that always does his homework willingly, is interested in learning and does well in school). 

Let's look at some of the features that seemed to influence involvment in school the most.

**_PLOT SPECED, UACT, UAGG_**

a) As we could expect, children receiving special education services show less engagement in school than children who don't.
b) Children that are taking part in more activities outside of school, like sports, lessons or any kind of clubs, seem to be more involved (so go get that gym membership that you've been talking about for months!).
It is also interesting to note that girls are definitely more engaged in school than boys.
c) The effect of family structure also seems to play a role. The `family structure index` recenses 4 types of familial living arrangement, respectively living with no parents, living with single parent, living in a step-family and living with two biological or adoptive parents.Even though the first three cases do not show any particular relationship with education, it seems that children living with both parents are more involved in school work. 

**_PLOT UAGE, UAGG_**

d) This plot shows a compelling story. From a general point of view, it seems that highly engaged children are younger than less engaged ones. An explanation could be that as children grow older, their parents will likely supervise their school work less. However, we can see that the mean age of the most engaged children (15+ scores) is higher, meaning, perhaps, that some of the more involved students show high engagement for their entire education, regardless of age. 
e) Lastly, let's talk about the `aggravation score`. This is an indicator of the aggravation of the relationship with the parents, higher scores indicating worse relationship. Unsurprisingly, school engagement linearly increases with better parental relationship.


