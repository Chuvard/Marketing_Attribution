# Marketing_Attribution

SQL queries to define marketing attribution

## During this project, we will analyze CoolTShirts database to identify first- and second touches from customers as well as to identify their incentives to purchase beginning from the first visit to the site.

The dataset describes each time a user visits the CoolTShirts website, and it grouped into one SQL table named "page_visits".

The given SQL table includes the following columns:

	1. user_id				    - unique identifier for each visitor to a page
	2. timestamp			    - the time at which the visitor came to the page
	3. 'page_name’ 		    - the title of the section of the page that was visited	
	4. 'utm_source’ 		  - identifies which site sent the traffic (i.e., Google, newsletter, or Facebook ad)	
	5. 'utm_campaign’ 	  - identifies the specific ad or email blast (i.e., june-21newsletter or memorial-day-sale)
