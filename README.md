# Revised-Geolocation-Code
Updated code for https://github.com/zlisto/User_Geo_Location
1. Enter correct keys in twitter_credentials
2. Enter apikey for google geocode in line 198 of function_helper.
3. Ensure that all the requirements are installed. See more in the "zlisto codeREADME" pdf. Current version of networkx is 2.6.2
4. Alter language, UTC offset, location_terms and geocode name in the get_ULDS file to run the code.
5. Manually calibrate the algorithm with a small sample size of seed users in seed_users_ids.
6. Run get_ULDS to obtain a list of twitter users, then run get_tweets to obtain the timelines of those users.


