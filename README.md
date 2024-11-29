# REST API Testing Project - TMDB API

 ### **This project is for educational purposes and is intended to help participants test their own skills.*

### **One Week Sprint**

### **URL:** [TMDB](https://www.themoviedb.org/)


 ### -*The project was created using the API of the TMDB page. You can find the description of the functions and their usage at https://developers.themoviedb.org/3/getting-started/introduction.*

 ### -*In order to use the project, you must be a member of the TMDB page and then the authorization procedures must be done. After getting the API key from the settings page, session_id should be obtained from https://developers.themoviedb.org/3/authentication/how-do-i-generate-a-session-id page.*

 ### -*API key, session_id and username must be written into the variables in the file in \src\main\java\com\tmdb\spec\RequestSpec.java.*

## Function tests included in the project:

 **Account**
 
- *Get Details*
- *Post Add Movie To Favorite*
- *Post Add Movie To Watchlist*
- *Get Favorite Movies*
- *Get Favorite TV*
- *Get Rated Movies*
- *Get Rated TV*
- *Get Watchlist Movies*
- *Get Watchlist TV*

**Genres**

- *Get Movie List*
- *Get TV List*

**Movie Lists**

- *Get Now Playing Movies*
- *Get Popular Movies*
- *Get Top Rated Movies*
- *Get Upcoming Movies*

**Search**

- *Get Movie*
- *Get TV*
- *Get Person*
- *Get Keyword*

**Movies**

- *Get Details*
- *Get Lists*
- *Post Add Rating*
- *Post Add Movie*
- *Delete Rating*


**Note:** It may give an error after creating lists 4 or 5 times with the CreateList function. Even if the lists are deleted,an error may occur while generating the list with the same explanation. 
If the description of the requestBody variable in the ListService class is changed and retried, the function will work without error.

## Contributor 

| Contributor                                               |               Role                    |        
|-----------------------------------------------------------|---------------------------------------|
| [Merve Kaya](https://github.com/kayyamervee)              | Project Lead & QA Automation Engineer |
| [Sefa Kahraman](https://github.com/SefaKahramann)         | QA Automation Engineer                | 
| [Ümmühan Teke](https://github.com/UmmuhanTeke)            | QA Automation Engineer                | 
| [Songül Çam](https://github.com/songulcam)                | QA Automation Engineer                | 
