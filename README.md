# McDonalds' Menu Analysis (Python)

**Background:** McDonalds is an American-based, international fast-food chain that has served meals & snacks to customers since the 1940's. Over time, their menu has grown to include a large variety of foods including burgers, beverages, breakfast foods, chicken, fish, coffee, salads, desserts, & more. They are one of the most well-known food chains in the world.  
In the mid-1990's, the United States Food & Drug Administration (FDA) passed into the law the requirement for food packages to contain detailed information about a food item's nutrients, serving size, calories, & such. Consequentially, McDonalds has provided various nutritional facts on their menus for each of their food items that they offer such as calories, carbohydrates, sodium, fat, etc. Such information can be explored to understand what McDonalds items are made of & how healthy they might be.

Data from Kaggle was utilized which contains nutritional information & other details of items across the McDonalds menu. Nutritional notes & recommendations from the US FDA were also incorporated.

This project was done in September, 2025.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Brief Summary
This project analyzed various details & nutritional information of items across the extensive McDonalds menu. Food items were assessed individually & across categories to determine how they contribute to a typical daily diet across various nutritional elements. Through these analyses, items that exceed daily recommendations in terms of nutrients were identified. As an exercise, daily meal plans were built from the McDonalds menu to try & satisfy a healthy distribution of daily nutrients.  
As part of these processes, recommended daily quantities of nutrients produced by the US FDA were utilized. As general advice, the US FDA encourages people to choose foods that are higher in dietary fiber, calcium, & iron, & lower in saturated fat, sodium, & added sugars. Analyses of these & other nutrients helped in evaluating how balanced &/or healthy McDonalds items generally are. Ultimately, individuals have various needs & desires in terms of how they want to consume nutrients including as dietary or health restrictions; however, the analyses & recommendations in this project generalized a typical diet, & by extension what levels of nutrients are considered generally healthy & balanced, to consist of 2,000 calories.

#### Analysis I - Rich Foods
To start, foods that exceeded daily recommended values of various nutrients were identified. By identifying such foods that are excessively rich in nutrition, it can indicate whether such foods, in isolation, are generally unhealthy in some way. Such foods can be important for people looking to follow a particular or balanced diet.

Of the 260 food items in the menu, 21 of them exceed one or more nutrients in terms of how much they account for in a single serving. In this selection of items, the nutrients which saw excessive amounts in a single serving include total fat, saturated fat, cholesterol, sodium, vitamin A, & vitamin C. Of these items, seven are breakfast foods, six are salads, & four are beverages. In particular, the Big Breakfast with Hotcakes (Large Biscuit) & 40-piece Chicken McNuggets are exceptionally rich across multiple nutrients & are therefore the least advisable for consumption.  
Many of these 21 items contain very unbalanced amounts of nutrients. In consuming such items, not only can it put the consumer "over their daily limit" when it comes to certain nutrients, but it also compromises what other foods they might eat over the rest of the day if they are trying to follow a balanced diet. While there are certainly foods that can help balance out these richer items in terms of nutrients, consuming them will make it more challenging for a consumer to properly balance their diet due to how disproportionate they are in their nutritional balance.

With this in mind, if people are looking to avoid consuming excessive amounts of certain nutrients, they would be advised to avoid these foods or get them in smaller quantities, particularly those high in saturated fat, sodium, & added sugars. Conversely, for those with a desire to consume greater amounts of certain nutrients, particularly total fat, saturated fat, cholesterol, sodium, vitamin A, & vitamin C, these items might be viable options.


#### Analysis II - Rich Foods by Nutrient
In an extension of **Analysis I**, the five most abundant foods across each nutrient were obtained & analyzed to assess how McDonalds foods generally contribute to nutritional balance.

Of the nutrients analyzed, McDonalds seems to offer several items that are generally either very rich, moderately heavy, or underwhelming in terms of their nutritional abundances.
- Nutrients in which several McDonalds items are generally **very rich** in include: Saturated Fat, Cholesterol, Sodium, Sugars, Vitamin A, & Vitamin C.
- Nutrients in which several McDonalds items are generally **moderately heavy** in include: Calories, Total Fat, Trans Fat, Carbohydrates, Protein, & Calcium.
- Nutrients in which several McDonalds items are generally **underwhelming** include: Dietary Fiber & Iron.

When evaluated against particular recommendations from the US FDA, the analyses seem to indicate that McDonalds foods generally provide unhealthy amounts of saturated fat, sodium, & sugars & insufficient amounts of dietary fiber & iron. Across these six nutrients, McDonalds foods only seem satisfactory when it comes to calcium levels.  
For people looking to follow a balanced or particular diet, they should keep these findings in mind because it might dictate what foods they do or do not consume.


#### Analysis III - Nutrients by Food Category
Next, nutrients were broken down across the nine food categories in the McDonalds menu to evaluate how they were typically distributed. These distributions can potentially be helpful in informing customers & how they can consume a more balanced collection of foods when eating at McDonalds. For example, if a customer consumes an item high in cholesterol, having an understanding of nutritional balances in other items can help assist them in assessing what other foods they could eat that aren't as high in cholesterol.

Of the 14 nutrients that were examined, some categories consistently have some of the largest nutritional abundances.
- McDonalds Smoothies & Shakes & Beef & Pork items each have the highest typical quantities across four of the 14 nutrients. Moreover, Chicken & Fish as well as Breakfast items are also fairly rich in terms of nutritional abundance.
- Conversely, McDonalds Beverages are usually among the least fulfilling of the nine categories across most of these nutrients (11 of 14). Snacks & Sides & Desserts items are also typically less sufficient in supplying adequate amounts of nutrients.

When assessing how extreme food categories typically were from McDonalds across these nutrients, there were two instances in which a category exceeded the daily recommendation of a nutrient. More specifically, Salads typically exceeded the recommended amount of vitamin A (165%) that should be consumed in a day, & Smoothies & Shakes (75 g) typically exceeded the recommended amount of sugars (50 g). Moreover, multiple categories also typically contained fairly heavy abundances of various nutrients particularly saturated fat, sodium, & protein. On the other hand, there were a few nutrients in which many food categories typically fail to provide adequate amounts specifically dietary fiber, vitamin A, vitamin C, & iron.

In regard to the nutrients most emphasized by the US FDA:
- Breakfast, Beef & Pork, & Smoothies & Shakes items from McDonalds are particularly rich in **saturated fat**. Given that the FDA recommends people to consume foods with less saturated fat, such items would generally be considered unhealthy.
- Breakfast, Chicken & Fish, & Beef & Pork items from McDonalds are fairly rich in **sodium**. Given that the FDA recommends people to consume foods with less sodium, such items would generally be considered unhealthy.
- Smoothies & Shakes & Coffee & Tea items from McDonalds are fairly rich in **sugars**. Given that the FDA recommends people to consume foods with less added sugars, such items would generally be considered unhealthy.
- The greatest abundance in **dietary fiber** of the nine McDonalds food categories is about 4.5 grams (Salads). Given that the FDA recommends people to consume foods with more dietary fiber (the daily recommendation is about 28 grams), McDonalds foods generally seem to lack adequate amounts of dietary fiber.
- Three McDonalds food categories typically contain between 20 to 40 percent of the daily recommended value of **calcium**; Smoothies & Shakes, Coffee & Tea, & Beef & Pork. While these categories are somewhat sufficient in providing customers with adequate amounts of calcium--a nutrient in which the FDA encourages people to consume more of--the other six categories are not.
- The greatest abundance in **iron** of the nine McDonalds food categories is about 20% of the daily recommended value (Beef & Pork & Chicken & Fish). Given that the FDA recommends people to consume foods with more iron, McDonalds foods generally seem to lack adequate amounts of iron.


#### Analysis IV - Assessing Nutrition of Daily Meals
Finally, daily meal plans were assembled from the McDonalds menu to assess whether McDonalds foods are generally more biased towards certain nutrients or not & whether they are generally capable of providing customers with well-balanced meals.  
Two approaches were conducted as part of this assessment.
1) Random daily meals were assembled to evaluate how & if a day's worth of McDonalds food satisfies daily nutritional recommendations.
2) The food items were explored to manually construct a day's worth of McDonalds food such that none of the daily nutritional recommendations were excessively exceeded.

##### Analysis IV A - Random Daily Meal Plans
The **first approach** randomly assembled daily meal plans by sampling items from the various McDonalds food categories based on what items people typically eat throughout a day. For example, a random breakfast & coffee item could be chosen for a typical breakfast meal, whereas a random salad & beverage item could be sampled for a typical lunch meal. By assembling multiple meal plans, it could help assess how daily meal plans from McDonalds typically contribute towards a consumer's daily nutrition & whether they are generally balanced or not.

Ten random daily meal plans were assembled each of which consisted of eight items from the McDonalds menu. Of the ten daily meal plans, at least three of them exceeded the daily recommended quantity for at least 13 of the 15 nutrients analyzed. Furthermore, at least eight meal plans exceeded the daily recommendations for nine of the nutrients. The two nutrients whose daily values were never exceeded in any daily meal plan were dietary fiber & iron. Moreover, daily recommendations of trans fat & vitamin C were only exceeded in four of the ten daily meal plans. Given this information, some conclusions can be made regarding a typical day's worth of McDonalds food items.
- McDonalds meals usually fail to provide enough dietary fiber & iron for a balanced daily diet.
- McDonalds meals often provide excessive amounts of calcium, calories, calories from fat, carbohydrates, protein, saturated fat, sodium, sugars, & total fat.
- McDonalds meals sometimes provide too much cholesterol, trans fat, vitamin A, & vitamin C than a balanced daily diet typically requires.

Of the six nutrients specifically pointed out by the US FDA, the analyses indicate that typical McDonalds meals are only sufficient in regard to one of them. More specifically, McDonalds meals typically provide ample amounts of calcium which is more desirable than the opposite according to the FDA; however, McDonalds meals typically provide insufficient amounts of dietary fiber & iron & excessive amounts of saturated fat, sodium, & sugars.  
As such, it can be said that McDonalds meals typically fail to provide appropriate amounts of nutrients for balanced, healthy diets.

##### Analysis IV B - Manually Constructed Meal Plan
The **second approach** built an eleventh meal plan by hand such that the recommended daily nutritional quantities were not grossly excessive or insufficient. This process was tinkered with until the entire collection of food items did not exceed any recommended daily nutritional values. Through this, it can be determined as to how difficult assembling a balanced daily meal plan of McDonalds foods generally is & what nutrients consumers may need to look elsewhere for otherwise.

In the meal plan that was assembled, it was determined that while the items provided adequate amounts of several nutrients, they underwhelmed for some others particularly those emphasized by the US FDA. In a daily meal plan that contains about 1,490 calories (about three-quarters of a typical daily diet), the foods provided fairly adequate amounts of calories from fat, protein, saturated fat, sodium, sugars, total fat, & trans fat. Conversely, they underwhelm appreciably when it comes to calcium, cholesterol, dietary fiber, iron, vitamin A, & vitamin C.

Regarding the six nutrients particularly emphasized by the US FDA, these meals are fairly rich in saturated fat, sodium, & sugars. Given that these items account for at least 84% of the daily recommended quantities but only about 75% in terms of calories, they provide somewhat excessive amounts of saturated fat, sodium, & sugars, which might be indicative of unhealthy food options given that such levels of these nutrients are particularly discouraged by the FDA.  
Moreover, these meals are quite insufficient in dietary fiber, iron, & calcium--nutrients in which the FDA encourages people to consume more of.

As such, given the uneven proportions in nutrients, particularly of those emphasized by the US FDA, this daily meal plan leans more towards being unhealthy & unbalanced based on a typical diet; however, there is still enough room, in terms of calories, such that these imbalances can be righted, but consumers may need to go beyond McDonalds to find suitable food items. Moreover, for those trying to follow a healthier, more balanced diet, eating these eight items will likely make it more challenging for them to find healthier foods that can supplement these items without exceeding certain nutrients that these eight foods are relatively rich in.

In relation to the first approach in **Analysis IV**, in which ten random daily meal plans were assembled, this eleventh meal plan seems to be a slight outlier in some aspects given that it did not exceed _any_ daily nutritional recommendations, whereas all but two nutrients & their recommendations were exceeded across many of the former ten meal plans. This might be indicative as to how challenging it generally is to assemble a day's worth of meals from McDonalds that can generate a balanced diet in terms of nutrients.
