# Where2Eat

![WhereToEat logo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/657/678/datas/original.jpg)

# What inspired us
Our project was inspired by the difficulty of deciding on a restaurant as a large group and the tension it creates for the remainder of your friendship. We also wanted to help small businesses, especially with the difficulty they've had due to COVID, and we believe that our app is a great way to find local restaurants to support.

# What Where2Eat does
Where2Eat uses an online room for users to access via code. The host can select a price range and then voting commences! Each user can choose what type of food they want and also any dietary restrictions they need met and WhereToEat will generate five nearby restaurants matching what the group is looking for. The users can then vote on which of these restaurants they want and head there while the night is still young.

# How we built it
We used HTML, CSS, and JS for the frontend and NodeJS for the backend: mainly to do the underlying algorithms choosing restaurants and sending votes. The Google Places API was used to access nearby restaurants' information based on the users' location and categorical preferences. The chosen restaurants are not only based on the most popular food type, but are weighted to the percentage of votes for each category. Even if only one person has a dietary restriction, all suggestions will accommodate it. Rating was also taken into account to rank the array of options.

# How to run
In the project directory, run
```
npm i
```
to install necessary dependencies. Then, run
```
node index
```
to start the server. In your browser, head to
```
http://localhost:3000
```
