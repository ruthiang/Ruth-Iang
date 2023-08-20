# Does income affect prevalence for anemia among women of reproductive age?
## UMBC Masters in Data Science Project
## Ruth Iang

## Introduction:
Anemia is a condition where the body's blood cells are depleted and the demand to meet oxygen cells is reduced. This affects approximately 1.76 billion people around the world, which means it is a big public health problem that must be resolved. In addition, it can lead to detrimental birth consequences along with defective cognitive performance in infants and young kids. The prevalence of anemia differs based on geographic region, but the highest prevalence is known to be among women of reproductive age(WRA). In this article, we are going to look at the relationship between income class, and anemia among women of reproductive age since geographic region often has to do with GDP and socio-economic class. We will also be looking at proximal (social class, contraception use, and access to healthcare), and an intermediate factor (educational attainment) that leads to anemia in women of reproductive age.

 ## Approach:
 ### **Source of data & graphs**: THE WORLD DEVELOPMENT EXPLORER
### **Countries/Class Compared**: Comparing different income level from 200 countries around the world
### **Timeline**: 2014 - 2019
### **Topics & Indicators**:
Economy and Growth:
 - GDP per capita (current international $)- This is gross domestic product(GDP) converted to international dollars using purchasing power parity rates. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes minus any subsidiaries not included in the value of products. It is calculated without making deductions for depreciated fabricated assets or for the depletion and degradation of natural resources. Data are in 2011 international dollars.

Health :
 - Prevalence of anemia among women of reproductive age (% of women ages 15-49). This refers to the combined prevalence of pregnant women with hemoglobin levels below 12g/dL and non-pregnant women with hemoglobin levels below 11 g/dL.
 - Condom use, population ages 15-24, female (% of females ages 15-24)- This is a percentage of how many females age 15-24 use condoms during sexual activity.
 - Problems in accessing health care (any of the specified problems) (% of women): Q1 (lowest) - This refers to the percentage of women who have problems accessing health care for the following reasons: knowing where to go for treatment, getting permission to go for treatment, money for treatment, distance to health facility, transportation, not wanting to go alone, and concern for not having female provider.

Education:
 - Educational attainment, at least Bachelor's or equivalent, population 25+, female (%) (cumulative)- the percentage of female population ages 25 and over that attained or completed Bachelor's degree or equivalent.

## The Relationship between Socio-economic Class and Prevalence of Anemia among Women of Reproductive Age
- As we can see on the time series plot below, those that fall in the high income class have the lowest prevalence of anemia in WRA, and those that fall in the low income class have the highest prevalence of anemia for WRA. We can also see that the percentage of people getting anemia is increasing throughout the years.

![Line Data](https://github.com/ruthiang/Ruth_data690/blob/main/charts/newplot%20(4).png)

![Bar Chart](https://github.com/ruthiang/Ruth_data690/blob/main/charts/newplot.png)

- Based on the bar graph above, those that fall in the low income class have the highest percentage for having anemia, followed by lower middle income, upper income, not classified, and high income. This just shows that poorer women at the age of procreating are more likely to have anemia, and those with more money are less likely to develop it.

![Scatter](https://github.com/ruthiang/Ruth_data690/blob/main/charts/newplot%20(1).png)
- The scatter plot shows us that there is a negative correlation between the prevalence of anemia among women of reproductive age and GDP per capita. It shows us the more money a country has, the less chances there are of having anemia.

![OLS Regression](https://github.com/ruthiang/Ruth_data690/blob/main/charts/Screen%20Shot%202022-03-12%20at%2012.15.55%20PM-1.png)
- The r-squared or coefficient of determination is 0.359, which means 35.9% of the variation in anemia is explained by changes in the GDP of a country.

## Association between Contraception Use and Anemia among Women at the Age of Conceiving
- Based on the bubble chart below, there seems to a negative correlation between the use of contraceptives, and prevalence of anemia among women in reproductive age. The usage of condoms is the lowest for low income females, but the chances of getting anemia are also the highest for them. This could be due to the fact that condoms are harder to purchase due to lack of availability, and money issues in poorer classes and countries.

![Condom Use](https://github.com/ruthiang/Ruth_data690/blob/main/charts/newplot%20(3).png)

## Relationship between Problems in Accessing Health Care and Presence of Anemia
- There are not enough data for incomes above lower middle class even when we use all the quartiles, but as we look at the bubble chart, we can see that those in the lower middle income have less problems accessing healthcare and have less occurrence of anemia than those from low income.

![Health Bubble](https://github.com/ruthiang/Ruth_data690/blob/main/charts/newplot%20(10).png)

## Association between Educational Attainment and Frequency of Anemia among Women of Reproductive Age

- Based on the bubble chart below, there is a strong negative correlation between educational attainment and frequency of anemia in women of reproductive age. Educational attainment factors cover women above 25 years that have at least a Bachelor's degree or equivalent. These relationships show us that educated women are more likely to be health conscious and take care of their health, resulting in better health. Now, we don't know if there is a causal relationship, but there is an association for sure.

![Educational attainment](https://github.com/ruthiang/Ruth_data690/blob/main/charts/newplot%20(9).png)

## Conclusion:

As we look at the charts and graphs, we can see trends between prevalence of anemia in women of reproductive age and the indicators: GDP/social class, contraception use, access to healthcare, and educational attainment. Although it is hard to conclude a causal relationship between any of them, there are some relationships we found. We found that:

- GDP/social class and prevalence of getting anemia in women of reproductive age have a strong association. Those from lower classes are more likely to have anemia than those from richer families.
- Regarding contraceptive use, women from lower income families are less likely to use condoms than those from higher income families.
- There is a strong relationship between educational attainment and prevalence of anemia among women of reproductive age.

Based on the results that we got from the graphs and charts, we can say GDP and social class affects proximal factors of getting anemia. This means poorer people are less likely to be able to afford condoms, have access to healthcare, and obtain secondary education, all due to a lack of money.
