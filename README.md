# **Boston House Price Prediction**

### Objective <br>
To predict the housing prices of a town or a suburb based on the features of the locality provided to us. In the process, identify the most important features affecting the price of the house. Employ techniques of data preprocessing and build a linear regression model that predicts the prices for the unseen data.

### Actionable Insights and Recommendations <br>
Overall, the interaction between the attributes and the median value of owner-occupied homes has provided a lot of insight into key features and their affects.  From this relatively small and simple dataset we can easily find value for home buyers, property investors, housebuilders, and even policy makers. We are able to quantify the effects of a mixture of evironmental, socioeconomic, and geographical features with the use of a simple model that can easily be used for informed decison making.

  Key points that can be made that are actionable for various entities:
  * Prioritizing investing in areas with lower pupil to teacher ratios.
  * The valuing of proximity to employment centers.
  * Addressing the negative impact of pollution on home values.
  * Understanding asthetics plays an important role in value.
  * Associating larger dwellings with increased marketability.

Considering this dataset orginates from 1970 and we have the gift of hindsight, the most obvious reccommendation for what the information gathered indicates is in fact what has happened all over the Eastern coasts and Riverfronts of American during this time, and that is the repurposing highly industrial areas that are found on the waterways to affluent modern downtown communities.  The Boston Housing dataset is a perfect depiction of why and how this urbanization was effective.  Let's look at what the dataset indicates:
  * The presence of the Charles River tracting the suburb or town increases the median values by 12.83%.
  * The increased number of rooms of the dwellings increased the median values by 11.52%.
  * The presence of industry, as indicated by Nitric Oxide levels, decreased the median values by 56.94%.

As the change in our countries lanscape from highly industralized areas to a more environmental conscious method of production, compounded by techniological advancements, and outsourcing, our country's industrial areas were and are the perfect recipe for transitioning to downtown affluent, modern, loft style, highly accessibile areas.  In this dataset, there are 8 suburbs or towns that are the exact discription of this scenario, riverfront, industrial, highly accessible areas. These are the areas that I would reccommend looking towards investing in.  Public and private investment is mandatory for tranisitioning these areas in the the downtown beautification projects that have happened all over our country in the last half century. For example:
  * Private investment means property investors reclaiming these insdustrial warehouses to large (6+ rooms) to be owner-occupied apartments.
  * Public investment means policy makers allowing for the infastructure like creating schools which will decrease the student to teacher ratios that attract the more affluent portion of society.
  
The time frame of this dataset leaves little to the imagination of the success of this concept, but it does feel rewarding to know that while the ability to write models to determine these factors at the time were unavailable, we are now able to look back at these datasets and be proud of the pioneers that were able to see this future that has given us the beautiful downtown areas that we all travel to and enjoy now.

There are also multiple reccommendations to be made that could improve the modeling for this dataset.  Limiting modeling to Linear Regression has value in the interpretablility of the information, but it can also lead to a lower model performance, especially with a data set such as this.  I would reccommend comparing Linear, Ridge, Lasso, and Elastic Net, but also exploring other options such as Decsision Trees and Random Forests.  And of course, if possible, simply increasing the size of the dataset would greatly impact the performance of any model.
