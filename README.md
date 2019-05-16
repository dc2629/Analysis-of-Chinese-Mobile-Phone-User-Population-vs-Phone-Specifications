# Analysis-of-Chinese-Mobile-Phone-User-Population-vs-Phone-Specifications
## What is the problem you want to solve?

  Through the analysis of the phone user’s features (information regarding age group, location, app usage, or gender) is it possible to determine the user’s phone manufacturer? In addition through the knowledge of the user’s phone features and app usage, can I determine extrapolate some of the user’s details? In addition to these two questions, can we use the data to map out any correlations that may help a business make a more informed decision on advertising?

## Who is your client and why do they care about this problem? In other words, what will your client do or decide based on your analysis that they wouldn’t have done otherwise?

  If we are capable of determining the user’s phone manufacturer, we can propose a more targeted advertising direction to phone manufacturers looking to expand or enlarge sales in specific regions. It will also allow for targeted ads to be placed in apps that can be used as reinforcement of phone brand loyalty. If we are capable of extrapolating some of the user’s data through phone features and app usage, then we can use that successfully predict future users and extend the same model to other populations, through that we can shift the advertising budget to appeal new users of less researched populations. 
  An example of the former is that if we know that in Shanghai most Samsung consumers are also males in their twenties. Perhaps the client can leverage that information to purchase advertising specific only to that region (as a cost saving measure) or perhaps if we can deduce that the users of that region that have a Samsung phone typically play games, then they can cooperate with the game publishers to help create a solid brand loyalty campaign. In a different scenario, by looking at a completely new region to start a business the model can be leveraged with a less complete description of the region’s expected consumers. This may be a stretch for regions outside of China but it is mostly likely a better starting point than random guessing. The cleaned and analyzed data can also be used as a guide for entrepreneurs looking for locations to start a new business (e.g. an Apple store or Samsung store).  

## What data are you using? How will you acquire the data?

  There is a kaggle dataset showing the chinese mobile user demographics which can be used with the GSMArena data (can be parsed through other people’s open sourced work). 

## Issues that occur with collected data
	
  The collected data comes from TalkingData SDK and only a portion of the device_ids are matched with the event data. Also, the device_id to device_brand/model has translation problems and foreign-only releases. A lot of brands and devices cannot be matched with the gsmarena data so I had to eliminate a good portion of the available data. This analysis surprisingly does not include "Apple" as a brand which can be a result of the TalkingData SDK being unable to collect data from Apple devices or being a Android-only SDK. This analysis can only be used to give insight of the available data and not regarded as evidence to a conclusion. 
