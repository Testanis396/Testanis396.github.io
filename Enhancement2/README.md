Artifact enhancements in app_api folder.

Working on same artifact, original is my finished Enhancement1. 
Focused on updating the API to create custom fields for user list novels, refactoring CRUD functionality to reflect list Schema changes, implemening .put request routes, and desiging /novels/search route to query the novels collection. 

Lists schema updated include novels reference ID's, status, rating, and notes. User can check each novel off as "Completed", or "To Read", rate novel from 1-5, and attach notes about each title. 

Searching implemented to allow the novels collection to be searched by Tag or Title. Can sort by Title or any of the fields in the Stats array. Can order asc or desc. Can set a results limit to define the length of the response JSON. 

Found out that most of my data is stored in strings in my Database— limiting the amount of sorting I can do. That will be one of the changes I need to make for my third enhancement, by: converting, re-seeding, and or re-examining the processing code in the scraper. 

