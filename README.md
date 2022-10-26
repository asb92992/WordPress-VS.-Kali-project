# WordPress-VS.-Kali-project

Explotis Found: Comment XSS vulnerability

Summary:
- Vulnerability types: XSS
- Tested in version: 4.2
- Fixed in version: 4.2.1

Steps to Recreate: 
- Go to a post and leave a comment then post the infected code inot the comment and click the submit button. 

Gif Walkthrough:

![screenfetch gif](https://user-images.githubusercontent.com/58159183/197911388-72704e01-ed66-4ff4-8f27-e7853888c5f2.gif)

Affected source code: 
- https://wpscan.com/vulnerability/7945


2) XSS vulnerability in Page's Edit-page
- Adding scipt to the title of the page can lead to a xss vulnerablility. The scirpt does not show up on the blog page but it shows the alert

- Tested Version: 4.2 
- Fixed Version: 4.7.1

Steps to Recreate: 
- Go to the all page seciton and select a page to edit. Then add the script to the end of the page title and update the page. Finally check the publish website to see the script. 

Gif Walkthrough:

![screenfetch gif](https://user-images.githubusercontent.com/58159183/197914811-9b6362d7-b634-4436-ae67-21390e1b0770.gif)

3) Vulnerability Name or ID: User Enumeration

Summary:
- Vulnerability types: User Enumeration
- Tested in version: 4.2
- Fixed in version: N/A

Gif walkthrough:

![hw gif](https://user-images.githubusercontent.com/58159183/197917608-758af780-ee8c-4f6d-80b0-13cfb50ff591.gif)

Steps to Recreate: 
- Go to WordPress login page and enter a random username. Then WordPress will tell you that this username doesn't exist and that is when you can type admin into the username. From doing that WordPress will tell you "the password for username admin is incorrect", letting us know that admin is the username.

Affected source code: https://www.wpwhitesecurity.com/wordpress-username-disclosure-vulnerability/
