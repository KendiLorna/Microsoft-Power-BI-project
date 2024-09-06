## **COMMUNICATING FINDINGS**
## **INTRODUCTION**
This is a project done at ALX Africa as part of my learning.
Maji Ndogo is a fictional African country facing a water crisis due to persistent corrupt regimes. The country has a new president keen on reversing past governments' damage and restoring Maji Ndogo to its former glory. On the assumption of office, the president ordered a survey of the water sources to assign resources and prioritize areas that were inadequately served.
Maji Ndogo has a population of 28 million people living in the five provinces of Maji Ndogo namely Sokoto, Amanzi, Akatsi, Hawassa, and Kilimani, which have a total of 31 urban and rural towns. There are five water sources in the country: wells, rivers, taps in homes, shared taps, and broken taps in homes.

## USER STORY

From the survey conducted, the president of Maji Ndogo wants to see the results represented in visuals on a national level and provincial level for the consumption of development partners, provincial leaders, and herself.
The results of the survey should show the improvements to be made to water sources in the country as well as the budget.

## OBJECTIVE
### National level
1. What are the key points of the survey results and the overall status of water access in Maji Ndogo? 
2. How many people are affected by water access challenges in Maji Ndogo and what are the challenges? 
3. How much money will be needed to complete the upgrades, and where does that need to be spent?
4. The data should be broken down at a national and provincial level.

### Provincial level
1. Total budget per province. 
2. The number of improvements to be made, whether in rural or urban areas. 
3. The relevant statistics for towns in each province. 
4. The count of improvements in the province per type.
5. Summary of improvements and costs.

## DATA SOURCE
md_water_services Excel workbook from ALX Africa.
There are 8 tables in the workbook.

## STAGES
1. Importing data into Microsoft Power BI.
2. Transforming data to remove anomalies.
3. Calculating measures and calculated columns using DAX.eg the total budget, percentage population with access to basic water services, percentage of improvements to be made, aggregated improvements, and cost per person.
4. Creating a visual dashboard for the national level and using buttons and bookmarks to navigate between views. There is an improvement bookmark, province bookmark, and the default page bookmark.
5. Created a visual dashboard for each province on different pages and used drill-through from the national level page to navigate to each page.

## TOOLS
- Data cleaning and visualization - Microsoft Power BI

## INSIGHTS

[Power BI Interactive dashboard on Maji Ndogo](https://youtu.be/wadujn5HCMo)

1. Only 34% of the Maji Ndogo population have access to basic water services. The water sources are classified according to the United Nations requirements.A water source is classified as basic if it is improved(safely managed and free from contamination) and collection time does not exceed 30 minutes for a round trip.

2. 64% of the water sources in Maji Ndogo need improvement and will impact 18 million people when completed.

3. It will cost the government 147 million USD to complete the repairs.

![Improvements page ](https://github.com/user-attachments/assets/2f478c32-3241-4e03-be45-32f486dc6f96)

4. Kilimani has the highest number of improvements to be made at 6,700 and also the highest population in Maji Ndogo at approximately 6.5 million residents.

![Kilimani report](https://github.com/user-attachments/assets/dbc2a808-e166-45b8-94dc-210ad917707e)

5. Sokoto is allocated the highest budget of 40 million USD because it has a high number of wells to be drilled and this is the most expensive improvement. The budget for wells in Sokoto is approximately 20 million USD with most wells being drilled in rural Sokoto.

![Sokoto report](https://github.com/user-attachments/assets/8ef4e31c-6b97-41eb-be3c-e83447639b82)

6. Shared taps are the most common source of water in Maji Ndogo and will therefore benefit a larger population with a budget of 43 million USD allocated for the installation of new taps. Kilimani will have the most number of taps installed with 12 million USD of its 39 million budget going to taps.

![Default page visuals](https://github.com/user-attachments/assets/dc662c56-7cba-455e-81a2-33fc00bfe51d)

7. Installing RO(Reverse Osmosis) filters to purify chemically contaminated wells has the highest count of improvements in Maji Ndogo taking up approximately 40 million USD of the improvement budget. Chemically contaminated wells are prevalent in Akatsi, so 12 million USD of that budget will be allocated.

![Improvements page ](https://github.com/user-attachments/assets/85c78e30-b133-4984-b44f-dac42c831c30)

8. On the national level, there is a province bookmark detailing the budget, population, and the number of improvements to be made.

![Provinces page](https://github.com/user-attachments/assets/1d06e798-b8a9-405b-b0a0-4fa52fd63adf)

9. On each provincial page there is a breakdown of the total budget and what each improvement is allocated, the towns in the province, their population, and the allocated budget as well as the type of improvements to be made.

![Akatsi report](https://github.com/user-attachments/assets/4f456668-f3b6-4584-93c5-e7301a572805)

![Amanzi report](https://github.com/user-attachments/assets/5ab6b368-c203-4d8d-a06c-34dea49d057d)

![Hawassa report](https://github.com/user-attachments/assets/ec584c75-0998-4369-bf22-2749bde82fa1)

## RECOMMENDATION

Vetting of contractors should be done to ensure only companies with a good track record are hired within the budget.
The improvements should be monitored and costs observed over time to ensure they are on track and budget and to report on challenges encountered.

## LIMITATIONS

The budget might be exceeded due to fluctuations in the exchange rates or increased inflation.
The project completion period may vary due to contractors and logistical issues.


