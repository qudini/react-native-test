# ReactNative-code-test

#Task

Develop a cross platform react native application that will fetch a list of customers from an API and display them on screen as detailed below. 
The API is: https://app.qudini.com/api/queue/gj9fs

The Username and password for the API are: 
- Username: codetest1
- Password: codetest100

The API will need to be authenticated against using HTTP Basic auth and will return a JSON object that contains some queue data containing a list of customer objects. 

# Requirements: 
-  The app should make a request to this api and display the list of customers name and their ‘expectedTime' and ordered by the expected time closest time first.
-  It should also fetch the profile image of the customer by using the Gravatar Image request api (use their email for this, or show a placeholder if no email is present): https://en.gravatar.com/site/implement/images/.
-  The app should have a text input present at the top of the list and allow customers to be filtered by customer name.
-  The app should ensure that the list reloads automatically every 30 seconds. 
-  The app is expected to use some form of state management (Redux or Mobx).
-  The application is expected to function correctly on both android and ios platforms and resize appropriately for a variety of screens.

# Bonus:
- Every Component is a PureComponent
- Cached profile images locally
- Some level of test coverage

The completed project should be uploaded to github and the URL submitted along with a description on how you coded it and reasons for doing things in the way you chose. 

You’re free to use any 3rd part library or framework that you can justify the need.
