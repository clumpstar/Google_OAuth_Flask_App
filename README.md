
😃 Demonstartion of Oauth with Flask Python

✅ First after downloading the files run the **pip install -r requirements.txt**

✅ Then python virtual environment i.e. **.\venv\Scripts\Activate.ps1**.

✅ Now coming to the root directory where all of the repository files are downloaded, run the python **app.py** file.

  👇 The Below is the Image of the home page.
  
   ![image](https://github.com/clumpstar/Google_OAuth_Flask_App/assets/91057057/278dee3a-2802-45ed-aa5c-429f6af92bd3)


ℹ️ Now on clicking the google sign-in button we get a google accounts login card. Like the below image 👇

![image](https://github.com/clumpstar/Google_OAuth_Flask_App/assets/91057057/3093f998-988c-4c97-8e49-658266bd4ed8)

ℹ️ Now if you observe the cookie section before clicking on the sign-in button there would have been no session cookies ❌

ℹ️ But after logging in we can see a session cookie present under the cookie tab of the inspect element section. 🍪 
   This is created by the session present in the Flask module itself. This gets stored in the client side and not on the server side.

ℹ️ Now the landing page looks like the below given image 👇

 ![image](https://github.com/clumpstar/Google_OAuth_Flask_App/assets/91057057/da02f5ee-f8d3-4a8f-af39-f644b3f894cc)


ℹ️ Now on clicking the logout button the session is cleared so that the user can be logged out safely without leaving behind any cookie details.

                                        **PLEASE VIEW THE app.py FILE TO GET AN IDEA OF WHAT IS SAID ABOVE ☝️**
                                        
