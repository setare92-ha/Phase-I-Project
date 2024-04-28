# Aviation Crash Data Analysis
<center><img src="./images/Header.png" 
    Width="1000">|
## 1. Overview
A company is expanding to new industries in an attempt to diversify its portfolio. More specifically, they're interested in purchasing airplanes for commercial and private enterprises. This study focuses on using available aviation crash data to identify aircrafts with the lowest safety risk that the company could invest in for starting their business endevaour in this area. 

## 2. Business Understanding
### 2.1. Business Objective
This project analyzes the [aviation accident dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) on Kaggle (Note that the actual data we're using is located [here](https://github.com/learn-co-curriculum/dsc-phase-1-project-v3/tree/master/data)). The findings will be used to make recommendations to stakeholders that may be looking to expand their business through purchasing and operating airplanes for commercial and private enterprises. 

### 2.2. Background Information
Before proceeding any further, we do some research to gain some domain knowledge. Different measures could be considered for assessing the safety of aircrafts. For example, the *number of fatal crashes per every 100,000 flights* seems like a standard measure to consider. The *number of non-fatal incidents that led to injuries* or required the pilot to take extreme measures for landing the aircraft may be considered as a secondary measure [REF](https://assets.performance.gov/APG/files/2023/june/FY2023_June_DOT_Progress_Aviation_Safety.pdf).

Some aspects of safety we can investigate are: 
- **aircraft make and model:** certain models may be more susciptible to incidents due to inherent manufacturing/design flaws.
- **number of engines:** a 4-engine aircraft should be safer compared to a 2-engine one
- **engine type:** Some engine types may be more susciptible to failures than others.  
- **location:** certain regions may have higher number of fatal aviation accidents. Factors like weather, terrain topography and the location being a hub for certain activities may contribute to these statistics. 

## 3. Data Understanding and Analysis

## 4. Conclusion
Based on the analysis done above, the following **recommendations** for the stakeholders can be made: 
1. **California, Florida and Texas** are the top three states in terms of the number of fatal aviation accidents. Most fatal accidents in these states are associated with flights that are conducted for personal (recreational) or instructional purposes. Therefore, if we solely rely on the data available at hand, **it is not recommended to pursue business in these three states for recreational or instructional aircrafts**.  
2. Aircrafts with reciprocating engines are highly involved in fatal aviation accidents. This doesn't necessarily mean that reciprocating engines are the cause of fatal accidents. However, it does indicate a correlation. Therefore, it's not recommended to invest in aicrafts with reciprocating engines.
3. Aircrafts with higher number of engines seem to be safer in general. This is reasonable since having more engines ensures that the aircraft can remain operational in case one fails. Therefore, **it is recommended to be cautious about investing in small single-engine aircrafts.** 
4. **Cessna, Piper and Beech** are associated with the highest number of fatal accidents. However, when both make and model are considered, **Cirrus Design Corp, SR22** is also among aircrafts with the highest number of fatal accidents. **It is, therefore, recommended to avoid using these aircrafts.** 
5. Unlike an initial preconception that there may be more fatal accidents in months with extreme weather, **July and August** turn out to be the months with the highest number of fatal accidents. This observation may have an underlying cause: there are simply more flights taking place in these months. Regardless, **it seems reasonable to recommend that stakeholders expect and plan better for aviation incidents and accidents during these months.** 

## Limitations and Next Steps
The above study is limited in the following ways:
1. The analysis is limited to the United States.
2. In the absence of information on the total number of flights (including those without accidents), we're relying on the absolute number of fatal accidents as a metric for our analysis.

To improve the analysis, next steps include obtaining data on the total number of inbound/outbound flights to/from each state, the total number of flights per make and model as well as the total number of flights done per engine type and engine count in the aircrafts. This will enable us to use a more proper metric (normalized ratio of total number of fatal accidents per total flights done during a certain period of time). It may also be desirable to have data on the profitability of each business pursuit (for example, investing in aircrafts for recreational versus travel or instructional purposes). A category may seem to be associated with lots of fatal accidents. However, it may also be highly profitable such that the business wouldn't lose money overall. 
