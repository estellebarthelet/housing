# Influence of housing on education, health & happiness

Have you ever wondered where you would be now if you had grown up in a different environment? Would you be healthy? More successful in your studies? Happier?

>*How do your living conditions affect your life?*

This is the question we asked ourselves after reading how Mexico managed to improve children's health and their mother's happiness by replacing dirt floors with cement, in a program called [_Piso Firme_] (https://www.aeaweb.org/articles?id=10.1257/pol.1.1.75).[1]

Indeed, achieving such results with only a bit more than 150$ of cement per household seemed rather encouraging, but this led us to wonder:

<div align="center"> *__What impact has the housing environment on education, health & happiness?__* </div>

### What, where, who, when ?

To try and answer that vast question we decided to focus on three main research axes.

* Which life outcome (education, health or happiness) is most affected by which housing conditions?

* What is the effect of precarious housing on health (both physical and mental) and school involvement for children?

* Are there differences in the effects of precarity between different age groups ? If so, for which outcomes ?

To conduct this study, we opted for a subset of the data from the [National Survey of America's Family] (https://www.icpsr.umich.edu/web/ICPSR/studies/4582) of 2002, to see the perspective from the other side of the frontier, in a similar timeframe as _Piso Firme_ (the program started in 2000). We combined data from children aged 6 to 17 and their respective households.

This dataset recenses a large number of households throughout the USA, providing insight on their demographics and health indicators of the inhabitants.

**_PLOT DES CHOSES POUR PRESENTER LE DATA?_**

## General influence of living conditions on education, health and mental health

First, let's have a look at which housing conditions impact which life outcome the most.

### How ?

To find the relationship between housing conditions and education, health and mental health, we perform linear regressions. Living conditions are defined as a number of various indicators such as housing (own or rent, overcrowding), family situation (structure, relationship with parents, parents mental health), income, extrascolar activities and personal caracteristics (sex and age).

### Education

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


### Physical health

The indicator for physical health that we used was a scale representing the current health status ranging from 1, excellent, to 5, poor. We will thus refer to it as the `poor health indicator` as higher values refer to worse physical condition.

Here are some of the features with the most influence on health:

**_PLOT UMH2, UACT, USOCPOC_**

a) First, we can observe that higher family income is related to less health issues. However, it would be interesting to study this effect in more details, as it is certainly linked to other factors. For example, poorer family perhaps do not have the insurance coverage needed to resolve their children's health problems if they have any.

b) Here we can see that children that take part in many activities outside of school are in better physical condition. Again, we do not know if doing less activities (sports for instance) leads to poorer health or if it is the poor health that limits activities. 

c) Finally, we show the distribution of parental mental health (higher scores indicating better mental health) in function of children's health status. As children's health deteriorate, so does the mental health of parents. That would make sense, as the health of children is definitely a big concern for parents. 


### Mental health of children

Now let's look whether depressive feelings are linked to the environment in which the children evolve. We use a depression score that ranges from 1 to 3, lower scores indicating better mental health.

Here are shown the conditions that impact chilren well-being the most:

**_PLOT AGE, FAMSTR, AGG, UMH2_**

a) First, let's look at the evolution with age. Sadly, it shows that the mental health of children steadily deteriorates with age. The trend seems to reach a plateau at around 16, which coincides with the end of adolescence. It can be quite a troubling period for many teenagers, which might explain this increasing occurence of depression between age 10 and 16. It would be interesting to see the results to see if depression rate decreases after that (hopefully it does!). 

b) Now, looking at the link with family structure, we observe that as it improves, so does mental health, which seems quite logical.

c) The aggravation is clearly correlated with depression in children. However, it is difficult to establish the link of causality between them - does depression leads to deterioration in relationship with parents or does a bad relationship causes to develop depressive feelings for the child?

d) Lastly, the distribution of parental mental health scores in function of children's well-being shows a positive correlation as well. It is difficult to say whether this is due to a common living condition (bad housing for instance) which influences the mental health of the entire household, or if the well-being of one person impacts the well-being of the other.


### Mental health of parents

Out of curiosity, we decided to look briefly into the influence of living conditions on parents happiness. It turned out that income, relationship with children and having a disabled child seemed to play a role.

**_PLOT USOCPOV, BDISBL, UAGG_**

a) Without surprise, parents mental health deteriorates as the relationship with children worsen. Again, causality is hard to establish.

b) Now, let's look at income and having a disabled child (physically or mentally) at home.Regardless of that last parameter, higher income correlates with happier parents. *Does that mean that money can buy happiness?* Let's not jump to conclusions, there are many variables linked to income that were not taken into account here... However, another interesting thing from this plot is that having a disabled child seems to negatively impact parents mental health (parents with a disabled child are about 10% less happy than parents with healthy children), which could be due to a lot more of responsibilities and time spent to care for this child.


## 






