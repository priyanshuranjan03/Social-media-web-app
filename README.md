# Social-media-web-app
This project replicates social media app to follow its multiple features.

### Pages

- Login Page
- Signup Page
- Create Profile Page
- Edit Profile Page
- Create Post Page
- Delete Post Page
- Update post page
- Password Reset Page
- Feed/Home page
- User Profile Page
- Search Results Page
- Post Comment Page

### Features

- Follow/Unfollow Users
- Like/Unlike the posts
- Download the post images
- Comment on user posts
- User suggestion section
- Search users through the search bar

### Tools and Techs

Backend Framework: `Django`
<br/><br/>
Front-end : `Bootstrap, SCSS, HTML,CSS, Javascript`
<br/><br/>
Database: `Sqlite3`
<br/><br/>

### Installation

1. 
   - Clone the repo to your local system
   ```git
   git clone https://github.com/priyanshuranjan03/Social-media-web-app.git
   cd Social-media-web-app
   ```
   Make sure you have python installed on your system.
2. Create a Virtual Environment for the Project

   If u don't have a virtualenv installed

   ```bash
   pip install virtualenv
   ```
   **For Windows Users**
   ```bash
   virtualenv env
   env/Scripts/activate
   ```


   **For Linux Users**
   ```bash
   virtualenv env
   source env/Scripts/activate
   ```

   If you are giving a different name than `env`, mention it in `.gitignore` first

3. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```

    ```bash
   cd socials
   ```


4. Make migrations/ Create db.sqlite3

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create a super user.
   This is to access Admin panel and admin specific pages.

   ```djangotemplate
   python manage.py createsuperuser
   ```
   

   Enter your username, email and password.

6. Run server
   ```bash
   python manage.py runserver
   
  
 ### Snapshots

**1. Signup Page**

![Signup page](https://user-images.githubusercontent.com/84091455/208101528-a448872c-6e8c-4f9e-b287-1c64a58d0c6f.png)

**2. Login Page**

![Login page](https://user-images.githubusercontent.com/84091455/208101465-29c16377-81a7-47c5-a051-c5ca103994a2.png)


