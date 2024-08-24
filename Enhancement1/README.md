Artifact enhancements in app_api folder. 

Focused on updating the API to connect with a new dataset of scraped web novels. New schema implemented to link User IDs with any number of unique Novel IDs that can be added or removed with the api. Rewrote routes to handle accessing master novels dataset (/novels), and managing personal list of novels (/lists). Wrapped methods in try/catch blocks for error handling, and formatted comments for consistency. 
