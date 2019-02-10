# Week 1


### Reflection on 4/02/2019

Today we got introduced to the studio, and how the studio was going to run in the next 4 weeks. I felt very excited to start this studio as it will help me learn more of the basics and help me understand where I need to go for this year. I meet my team, and we were assigned a presentation to do. We spent an hour researching what topics we would like to talk about regarding cybersecurity.

![Picture](/images/teams1.PNG)

The topic we picked was an article about SYN Floods. This was an interesting topic for us to do because personally, I wasn't sure what an SYN Flood was. It was fun researching and understanding how it works and its effect on a business. I learned that an SYN Flood is a DDOS attack which targets available ports and sends constant SYN packets. It exhausts resources like the CPU on the server as the server is constantly expecting a connection to the attacker.

We made a powerpoint for a presentation and started working on it.

![Picture](/images/teams2.PNG)

### Reflection on 6/02/2019

Today was the day to do our presentations. I was feeling confident in our team's presentation. But once it came to our presentation, my group did well proud of our content and what we spoke about. I felt like my part was lacking as I did research my topic but due to my presentations skills, it felt like I didn't know what I was speaking about. Larry brought this up, as he was wanted to know if I knew what I was talking about or not. This just shows how much confidence and practicing what you're saying comes into a presentation. Since I was stuttering and feeling nervous about the presentation it took the better at me. Even though I did my research, it didn't show in the presentation. So for the next presentation, I need to practice my presentation skills, ways I can do this is speaking to myself or practicing in front of family and getting pointers from there.


![Picture](/images/teams4.PNG)


Today I was working on my static website as well, I had a lot of troubles with Hugo as I couldn't get the page to run locally. So I decided that I'll just make a GitHub page, for now, just to keep my portfolio up for now. I want to go back to Hugo and give it a proper shot, as I do like the templates and just the general look of the sites. I also want to learn Hugo, so I can help my Father with his website.

![Picture](/images/github.PNG)

### Reflection on 8/02/2019

Today we presented what we were doing this week and how we felt, and our thoughts. I said that I was working on my Github pages, and stated my concerns with my ability with presenting, and it was nice to know that other people in the class also had their concerns with public speaking. 

We practiced web pentration on a CTF that was made by OWSAP. The website was a online shop selling juice. The challange I had the most trouble with was gaining admin rights. I knew it was an SQL injection, but since I couldn't google properly to find the answer I was looking for, and also I haven't done SQL since 2016, it took a while. The SQL injection was very intresting and learning it again was very fun.

SQL injection I did eventually after a while, and some research was the following logic. 

```MySQL
1' OR 1=1--
```

The following query will be sent to the database server and be treated as:

```MySQL
SELECT id FROM users WHERE email=’email’ AND password=’password’ OR 1=1’
```

Since the login will try to find in their database if the following email and password was the one you inputed. If that isn't found it will run the 1=1-- command. Since an OR statement only needs to be 1 of the following statements to be true. It will treat your code as a valid statement and log you in. 

![Picture](/images/SQL_Injection.PNG)

After learning this, I decided to try some other ways to get admin rights. Corey my group member showed me a shorter way to gain admin rights which was the following:

![Picture](/images/SQL_Injection_2.PNG)

This works aswell because the following query is just asking to check if the OR statement 1=1 is true. And since 1=1 is true, it gives you admin access.

One way I found on my own, is just writing the admin's email. I found an order confirmation which was done by an admin. I found this by acessing their FTP server. 

![Picture](/images/ftp1.PNG)

![Picture](/images/Order.PNG)

Just by writing a simple query:

```MySQL
admin@juice-sh.op';
```

So since the email is true, it allows me to access the admins email. Giving me admin rights!

![Picture](/images/SQL_Injection_3.PNG)
