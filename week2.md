[Home](./README.md)
[Week 1](./week1.md)
[Week 2](./week2.md)
[Group Reflection](./group_reflection.md)

## Problem Statement:

A realistic goal I would like to set myself is gaining a better understanding of Web Application penetration testing. I would like to develop these core skills first and playing around with these applications will help me develop the fundamentals to go into other challenges and then eventually start doing some boxes. Practicing on these challenges helps emulate the feeling on what I would do when going into a penetrating test on a web application and what patterns I should be looking for to exploit or follow to penetrate the application.
I would like to complete the majority of the Natas challenges, and complete write ups for them. Detailing my thoughts, struggles and how I completed the challenge and my logic through the whole challenge.

### 11/02/2019 Reflection

Today, we had a presentation from Luke, explaining his view on red teaming and his idea of what you should have when doing penetrating testing. He made it clear that we need to have an Ethical mindset, not just penetrating testing because it’s all about the rush about getting inside the web application. Luke explains that we need to get into the habit and to test our abilities and think “How does this site/web application work in its entirely?” and “What are the possible paths, you can take?”.  Also, he reinforces the statement that we need to always maintain this attitude, to always challenge yourself. There is no such thing as a perfect system, or undetectable exploits. 

After saying this, I was practicing some Natas challenges trying to learn Web App penetration testing. All my write ups and thoughts are written on a separate document.

Natas Writeups: https://hackmd.io/s/ByI4tVA4V

### 13/02/2019 Reflection

Today, we had a presentation with Luke, explaining what XSS is. I knew what XSS was, but I didn’t know there were different types of XSS like:
-	Reflected XSS
-	Stored XSS
-	DOM-Based XSS
It was interesting how Luke explained how each one works and functions how they get sent to the web application, how it gets treated. I personally didn’t know how it works, it gives me more insight how they work, so now I’m aware how it works I use them in the future.

We went into groups, and I meet new people, who I haven’t worked with before. This gave me the simulation what it is like in the real world where I must work with people who I haven’t met before and come up with ideas and start to develop some teamwork with them. We were researching some XSS attacks that were exploited in the past. We came across an exploit that was done to eBay, where customers were using XSS to steal accounts credentials. This exploit could be mitigated by limiting the use of active content (like JavaScript), they suggested that they want to get of JavaScript all together. 
The link to the article: 

https://news.netcraft.com/archives/2017/02/17/hackers-still-exploiting-ebays-stored-xss-vulnerabilities-in-2017.html


### Homework for Wednesday

Ethical hacking and bug bounties are impacting stakeholders as they allow people who have these hacking skills and people who hunt through bugs, go through their system and find vulnerabilities. Businesses that go through these bug bounty programs looking for people to attack their web application, with the intent to find any bugs and vulnerabilities. As stated in the bug crowd responsible disclose.

![Picture](./images/bug_crowd.PNG)

The security researcher must report the vulnerability, and disclose the company privately, with detailed response on how they found the vulnerability, and how to fix the problem. This will benefit the stakeholder a lot as if their system does get targeted in the future, they don't get any sensitive data leaked. It is also better that they get exploited my security researchers who are doing their job, and wanting to better strengthen the web application. Then by a hacker exploiting the vulnerabilities and using that information for bad.

![Picture](/images/SQL_Injection_3.PNG)

An example that could be used is the SQL injection on the Juice Shop last week. If a hacker finds this out and exploits the SQL database and gains admin access, he can then jump on and try to own the whole server, and get a lot of sensitive information about clients, credit card numbers etc. But if a security research finds this exploit and discloses it to the company and patch it. It will greatly help the web application. 

Ethical Hacking and bug bounties are greatly needed to help strengthen stakeholders to better their web app security to fix their mistakes so hackers can’t exploit them!


https://www.bugcrowd.com/resource/what-is-responsible-disclosure/

https://www.hackerone.com/disclosure-guidelines

https://www.cybrary.it/2018/03/ethical-hacking-necessary/

