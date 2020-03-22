<h1>Boogo</h1>
<h2>What is Boogo?</h2>
<p>Boogo app is an application that gives ability to find different peoples and also chat with them</p>
<h2>Main functionality:</h2>
<ul>
<li><strong>The user can fill in their profile with certain data (this data will consist of user information such as age, gender, city, country, address information and so on). User will be able to view and edit it, if necessary</strong></li>
<li><strong>User can upload different files that will be in different places:</strong></li>
<em>Add audio recordings</em><br>
<em>Add photos</em>
All the provided data will be stored on the Amazon S3.
<li><strong>User can chat with other people</strong></li>
<li><strong>Add to your friends list, different people</strong></li>
<li><strong>Search for friends or people</strong></li>
</ul>

### Addvanced plan:
<p><strong>User can make video calls</strong></li>

### Technologies

#### Frontend:
- HTML5 + CSS;
- React;

#### Backend:
- PostgreSQL; 
- Node.js;
- WebSocket;
- OpenTok.

#### Work Scenario
When we open a Boogo site, we will have a sign-up or login account. If we do not have an account, we click on the registration button, where we will need to enter the name, age, gender, country, city, status: "Married", "Search" or blank, as well as a phone number , and after we have completed all the information, we will have a "Complete Registration" button. After that, we will need to enter the SMS number that came to our phone number. In case of incorrect code, there will be a button "Resend message" or "Change phone number".
        After successful registration, we are on our profile. If we accidentally entered the wrong data during registration, we will be able to edit them by clicking somewhere under the profile (I do not know exactly where), on the button "edit profile", where we will be able to change our data during registration, when changing the phone number, the scheme works with sms with code.
        We have a profile with a default photo, depending on the gender, by clicking on the form, we can add a picture, and when added to our profile below will be news, that is, what photo they added, which they added to their audio recording.

       On the side, we will have buttons:
1) **"Friends"**
        When clicked, we are forwarded to friends, picture of this profile, name, age, gender, when you click on the button next to "View profile", or just on the name, we will go to the profile of this person, where we can see his (her) news: audio recordings , photos, chat with her by clicking on the "Send message" button and also "Remove from friends"
        In case there are none, (until I came up with where) there will be a button, "search people", which I will explain in the 2nd paragraph
2) **"Find people"**
        When clicked, we are taken to a page where you can search, enter the name of the person there, and bring us to certain people, again, as in the previous paragraph, click on the button, or on the name and we show the profile of the person, if she liked it, we can add it to friends by clicking "Add to friends".
3) **"Photos"**
        When clicked, it takes us to a page with our photos and if we do not have any, there will be a button "Upload Photos", where you can save the photo data. If you do not like a particular photo, click on it and there will be a "Delete Photo" button.
4) **"Audio recordings"**
        The same situation with the previous item "Photos"
5) **"News"**
        When clicked, we are taken to a page with all the news, that is, friends have posted a page
6) **"Messages"**
        When clicked, we are taken to the list of people to whom you wrote, and if you did not write, there will be a "Send message" button, where you can select the person you want to write.
