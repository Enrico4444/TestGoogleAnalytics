1. go to analytics.google.com and setup an account (follow the instructions)
2. once logged in, go to Data Streams > Web > enter a random website name if you develop on localhost without DNS > copy the MEASUREMENT_ID
3. go to tagmanager.google.com and create a new account
4. copy the code snippets into your code as indicated by the popup window "install google tag manager"
5. test the connection by clicking "preview" and inserting the http://localhost:PORT of your local website - if Connected appear in both google tag manager page and your website page, it worked
6. in tag manager, go to Tags > New > Tag Configuration > GA4 Configuration > enter MEASUREMENT_ID > Triggering > All Pages > give the tag a name
7. Click Preview again to test. Go to Container Loaded and check that the name given above appears in Tags Fired
8. Return to Google Analytics. On the left side panel click Configure > Debug View and test actions on your webiste - they should appear here

Triggers for page view: https://support.google.com/tagmanager/answer/7679319?hl=en
