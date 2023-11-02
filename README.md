# Front-end Engineer React / React Native Exercise

# Preface
At Qudini we utilise a range of front-end technologies which make up our stack. We're evolving our existing and greenfield applications to make use of a more modern set of technologies. We make use of React on both the web with React-DOM and on mobile devices using React-Native.

This exercise is intended to give you freedom to build an application from scratch and showcase your capabilities.
 
# Tasks
Develop a cross platform React Native application that will display a real time list of customers currently in the Queue waiting to be served.

The API to fetch the list of customers is: https://app.qudini.com/api/queue/gj9fs

Before making the API request you will need to authenticate it using HTTP `Basic Auth`. 

The Username and Password to use the API are: 
- Username: codetest1
- Password: codetest100

After making the GET request you'll receive a JSON object that contains information about the given Queue and contatin list of Customer objects.

You’re free to use any 3rd part library or framework if you can justify the need.

# Requirements
-  The app should make a request to this API and display the list of customers (`name` and `expectedTime`), ordered by _earliest_ `expectedTime`.
-  The app should fidplsy the profile image of the customer by using the `Gravatar` Image request api (using their email for this, if no email provided show a placeholder): https://en.gravatar.com/site/implement/images/.
-  The app should have a text input present at the top of the list and allow customers to be filtered by customer name.
-  The app should ensure that the list reloads automatically every 30 seconds. 
-  The app is expected to use some form of state management (preferably `Redux`).

# Bonus
- Some level of test coverage (using `React Testing Library` or `Jest`)
- Use of Types (using `Typescript` ideally)

# Extra bonus
- Cached profile images locally


# How to subimit?
The completed project should be shared via a public `Github` repo.


