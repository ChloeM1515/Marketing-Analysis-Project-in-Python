# Marketing-Analysis-Project-in-Python

## Request
The Marketing Department of a global retail store is running a customer appreciation campaign on the occasion of Christmas and New Year. They need to deploy appropriate marketing program for **each customer group** and exploit **potential customers** to become loyal customers.
The Marketing Director asked to provide a segmentation analysis base on **RFM Model**. 


## Clarify Requirements

### Analyze Requirement using User Stories
<img width="736" alt="Screenshot 2023-07-30 at 18 08 00" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/7ebbf480-48c3-4462-9ba4-9ecaea22cdb6">

*Tools: Python

### Clarify Details
Provide a Python analysis, including:
- Segment overview:
  + Customers categorized into each group following RFM method.
  + Visualize number of customers, Revenue and Profit per segments.
- "Potential" group:
  + Identify buying behaviors via Channel, Category and Ship Method.
  + Identify Sales overtime


### Meaning of RFM Segments:
![image](https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/04e74d97-a5be-430b-a978-df07eab45dbd)


## Insights and Suggestions

### Insights by segments: 
<img width="720" alt="Rev_prof" src="https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/3095c83d-a5d4-4689-9921-e251758d80fd">
<img width="548" alt="Numb" src="https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/5381103f-b611-4514-bcb6-8bd002b17937">

**- Mostly, high revenue and profit are not proportional to high number of customers groups.**
  + Except for "At Risk", revenue and profit of 3 other leading  groups ("Champions", "Loyal", "Need Attention") were brought back by top 6,8,5 numbers respectively. These 4 groups comprised of **61,3%** total revenue, **66,2%** total profit, but only **38,1%** total customer quantity.
**=> Suggest:**
- Instead of quantity, prioritize more beneficial groups to maximize revenue and profit:
  + "At Risk": Need to bring them back - Send personalized emails to reconnect, offer renewals, provide helpful resources. 
  + "Champions": Reward them - Can be early adopters for new products.
  + "Loyal": Engage them - Upsell higher value products. Ask them for reviews. 
  + "Need Attention": Reactivate them - Make limited time offers. Recommend based on past purchases.


 
### Insights by "Potential Loyalist" group: 
<img width="785" alt="Rev_chan" src="https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/e948ebf6-56bc-47ee-8339-171e7f56c0d1">
<img width="783" alt="Rev_Cat" src="https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/055835ea-5178-49e9-9661-01b36e496ec3">
<img width="761" alt="Rev_ship" src="https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/17bd2b88-7ffd-48de-a835-e70bc7b2ab1a">

**- Potential customers preferred buying through Consumer, shipping by Standard Class, and shared almost the same interest on 3 categories .**
  + **Half of** customers **(50,3%)** buyed through **Consumer** channel.
  + **59,8%** customers chose **Standard Class** shipping method.
  + Customers slightly preferred **Technology(36,9%)** products, Furniture(31,9%) and Office Supplies(31,1%) almost got the same consuming proportion.


<img width="778" alt="Line" src="https://github.com/ChloeM1515/Marketing-Analysis-Project-in-Python/assets/130263988/b9cecc97-1a50-4e8e-b298-0f7835d9b777">

**- In general, sales increased overtime, except for a down trend in February and October.**
  + From 2014-2016, sales in December increased **>3 times** compared to them in January. Sales in Dec2017 **doubled** it in Jan2017.
  + February and October saw a plunge in sales. Highest plunge (in **Oct 2014, 2015**) was **>60%** compared to its previous month.


**=> Suggest:**
- Offer membership/ loyalty program, recommend other products.
- Set priority for Consumer, Shipping Standard group.
- Conduct further analysis to identify the reason of plunge in February and October.


