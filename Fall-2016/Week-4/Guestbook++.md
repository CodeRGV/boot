# Guestbook++;
#### Week 4 {Running Challenge}

### Assignment
Build upon your original guestbook, time to make it great. Turns out your guestbook was spammed so we now need to add email and password authentication, and social authentication to get rid of this anonymous spam.

###### Implement the following features
- Login with email and password
	- Passwords must be encrypted using bcrypt and a salt
	- Everything should be securely stored in a user object in your DB
- At least 2 social logins (i.e. Facebook, Twitter, Github, etc.)
	- Your users should also be given the option to login using their favorite social network
	- If they do authenticate with a social network store their profile image which you can query from the respective social network's API
- If they __do__ have a profile picture link in your database (you would only have this if they logged in with FB/Twitter etc.) then display it next to their guestbook entry. If they __do not__ then display a dummy place holder, have fun with this.
- Think about security, implement the best security practices

###### A couple of things to think about
- This is assignment is more open ended think about the coding decisions you will make before starting to write your code. Map out how everything will look. Ask yourself how will I solve this problem?
- You can change anything from your original code, anything goes.
- Think about how you will differentiate between facebook and normal users. Here is an example:

		⋅⋅⋅ Let's say I create an account in your guestbook using email and password authentication. My email is bob@codergv.org, later I come back and I log in with Facebook. In my facebook account my primary email is bob@codergv.org. 
		Should I be redirected back to my original account? Or should a new account be created?

### Submission

Post your progress to your original repo, __do not__ make one big commit when you are done. 

Record your progress, all your commit messages should be insightful on what work you are submitting.

```
https://github.com/{username}/guestbook
```

### Resources
