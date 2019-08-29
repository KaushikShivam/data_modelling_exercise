# Data Model Task

For each of the following scenarios, write down the models, columns, validations and associations you might use to implement it. Some of these are more difficult than others and you’ll have to use a bit of creativity to infer which columns might need to be present for the scenario to make sense in the real world.

The trick is identifying what should be a different model and how these models will relate to each other via simple associations (all the ones below are has_many, has_one and/or belongs_to relationship). If you can’t quite figure out how it might look, keep the scenario in mind as you go through the next few lessons.

Remember, if you feel like you will be hard coding data multiple times, it’s probably a sign that you should create a separate table. A common example is address information – you could write down the city and state explicitly for each user. How about making separate City and State models and relating them to each other?

1. You are building an online learning platform (much like this!). You’ve got many different courses, each with a title and description, and each course has multiple lessons. Lesson content consists of a title and body text.

2. You are building the profile tab for a new user on your site. You are already storing your user’s username and email, but now you want to collect demographic information like city, state, country, age and gender. Think – how many profiles should a user have? How would you relate this to the User model?

3. You want to build a virtual pinboard, so you’ll have users on your platform who can create “pins”. Each pin will contain the URL to an image on the web. Users can comment on pins (but can’t comment on comments).

4. You want to build a message board like Hacker News. Users can post links. Other users can comment on these submissions or comment on the comments. How would you make sure a comment knows where in the hierarchy it lives?
