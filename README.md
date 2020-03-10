# Predictive Maintenance: Utilizing CRISP-DM

![Design Blocks](https://images.unsplash.com/photo-1488229297570-58520851e868?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=3298&q=80)

# Capstone 1 Springboard
### Predictive Maintenance Utilizing CRISP-DM & Supervised Machine Learning
### Phase I. Business Understanding.

### Background

Now that the hype surrounding Data Science has slightly diminished, we can affirm that this is not a drill but rather an exhilarating reality. Governments, large organizations, and start-ups alike have already seen and understood the value this discipline brings to the table and are fervently competing for talent and dominance in this space. As of 2019, we are finding ourselves at a new precipice in entering the Fourth Industrial Revolution: The Real-Time Enterprise! Just like the intersections of the past: First in 1784, Water and steam; Second in 1870, First conveyor belt; and the Third in 1969, Electronics and information technology, this pause will bring with it both challenges and new opportunities. Data stewards in the discipline have realized associative costs for data storage has expounded this issue while driving talent gaps. As their respective organizations continue to ingest voluminous amounts of data, they must become more tactical with the data they are creating and using to sustain or improve Return on Investment (ROI). 
More so, the approach of advancing insight through analyses of mountains of data must clear and consistent so that results are both reproducible and can be made autonomous. One method in doing this is by utilizing the Cross-Industry Standard Process for Data Mining (CRISP-DM). This logical method enables data stewards and stakeholders to clearly understand what, when, where, why, and how they are mining data through six easy to follow phases:

>	1. Business understanding
>	2. Data understanding
>	3. Data prep
>	4. Modeling & Application Development
>	5. Evaluation
>	6. Model Deployment.

![crisp-dm-phases](Data/crisp-dm-phases.png)

__Contraints, limitations, and assumptions__

> • _Constraint 1:_ The success of the model will depend on how good the prediction of material failure is based on historical observations in the curated data. For instance after analyzing several observations of data after X period of months pertaining to consistent machine utilization hours the model's predictions will be based on future and consistent occurences similar to the recorded and analyzed observations in the past. 

> • _Limitations 1:_ In order to predict the likelihood of a future material failure for a machine after X period of running hours, we would need to know how many hours the machine is expected to run in the future: which we do not know "accurately" today. 

> • _Assumptions 1:_ The classification model will be able to communicated probablities at various run levels to address this limitation. 


### Business Case

The following project will demonstrate how to utilize CRISP-DM from a practical standpoint; the next analog will use it on simulated manufacturing data predicting maintenance failures for a theoretical client's manufacturing operation. Predictive maintenance is an area that has a clear use-case for data-mining and analytics and primarily due to the breakthroughs of applied machine learning. With the continuous advancements in the Real-time enterprise fueled through the: Internet of Things (IoT), Telemetry, Low-Cost Digital Storage, and increasing Computing Power amongst others, the capabilities of transforming voluminous data into insight in this space does not appear to be slowing. The growth in Artificial Intelligence (AI) amongst increasing levels of Automation seen in manufacturing allows firms to be more resilient in connecting fixed-assets while improving productivity through data-driven decisions and insights not possible before. As the use of automation continues to augment and takeover manufacturing, the reduced response time required in dealing with maintenance issues will outpace the speed at which humans can intervene, requiring sophisticated and automated optimization decisions, especially about maintenance schedules. Executives and managers in both the public and private sectors to cope with this transition must speed up training initiatives to groom new tech talent to utilize tools to assist them in managing this transition through a structured method, or else the cost of doing business will outweigh the profits of its outputs.

___Set objectives:___
> • In this case, the client has furnished controlled sensor data on one machine, collected over four years. The device has sensors that archive telemetry readings over time. Based on the data provided the client wanted us to predict if, when and what machines would fail in the next seven days so that the company could optimize labor work schedules to support the maintenance operations. The findings from this analysis will be applied globally throughout the organization's maintenance program.

___Who might care:___
> • Maintenance Managers, Operations Managers, Capital Expenditure planners, and manufacturing organizations such as the Department of Defense, Exon Mobile Corporation, General Motors, Ford Motors, Apple, and Boeing, and the Department of Defense, etc. can use such a model to predict the likelihood of equipment failures to allocate resources better. They can then proactively inform their maintainers and or customers well in advance of potential disruptions in their respective operations. Understanding the probability of material failures will help sustain customer service or level of service efforts. From the customer's point of view, it would be very convenient in knowing if a supply, production, or any other disruption may occur so that they can in turn, proactively mitigate risk. On the manufacturer's hand, such a predictive model would enhance the product base and performance of the organization's operations. Moreover, there is a possibility of developing an app or other front-end communication effort in which customers and or internal users can consult with to understand the likelihood of issues well in advance.

___Cost and benefits:___
> • Every maintenance hour reduced in human labor will save the company and average of 75.69 dollars which includes fringe benefits. The company's current budget for maintenance includes a staff of 70 maintainers overseeing 10 machines (700 machines total) each week working 40 hours a week at an operating expense of 211,932.00 a week. Due to high attrition and steep learning curves the firm would like to augment the operations team with a data scientist at a cost of 125.00 an hour fully burdened to help optimize and allocate maintenance labor hours by predicting which machines will require maintenance. The operations team has refitted each of the 700 machines with telemetry sensors.
