# DIRECTING CUSTOMERS TO SUBSCRIPTION PRODUCTS THROUGH APP BEHAVIOR ANALYSIS

# INTRODUCTION
<p>In today's market, many companies have a mobile presence. Often, these companies provide free products/services in their mobile apps in an attempt to transition their customers to a paid membership. Some examples of paid products, which originate from free ones, are YouTube Red, Pandora premium, Audible Subscription, and You Need a Budget. Since marketing efforts are never free, these companies need to know exactly who to target with offers and promotions.</p>

* <b>Market :</b> The target audience is customers who use a company's free product. In this case study, this refers to users who installed the company's free mobile app.

* <b>Product :</b> The paid memberships often provide enhance versions of the free products already given for free, alongside new features. Ex: Youtube Red allows you to leave the app while still listening to a video.

* <b>Goal :</b> The objective of this model is to predict which users will not subscribe to the paid membership. so that greater marketing efforts can go into trying to "convert" them to paid users.

# Columns
* <b>user :</b> this is the user identifier with unique numbers.
* <b>first_open :</b> it has the date and time that the user first opened the app 
* <b>dayofweek :</b>it represents the day of the week that is 0 meaning Sunday and 6 means saturday, this gives in which day the app was first opened.
* <b>hour :</b> it means the hour of the day when the first app opened.
* <b>age :</b> age of the user
* <b>screen_list :</b> list of all screen names that the user has visited.
* <b>numscreens :</b> number of screens the user visited (in numerical form)

* <b>minigame :</b>if the user played the game then value is '1', else it is '0'.

* <b>used_premium_feature :</b>if the user has used the premium features then value is 1 else it is 0

* <b>enrolled :</b> if the user has enrolled then value is 1 else it is 0.
* <b>enrolled_date :</b> the date and time of enrollment.
* <b>liked :</b> if the user liked the application then value is 1 else 0.
