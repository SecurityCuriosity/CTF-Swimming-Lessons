# CTF-Swimming-Lessons
Write-up for Swimming Lessons challenge
---
## 1. How many packets were captured? **15892**
  
  a. The number of packets is displayed at the bottom of the screen on Wireshark
  
  ![swimming-1](https://user-images.githubusercontent.com/86580417/166746893-e092eb15-0681-4964-a86d-77de4b4f16a9.png)
---
## 2. How many TCP streams? **149**
  
  a. The number of TCP conversations (streams) can be viewed under the "Conversations" tab: 
  
  ![swimming-2](https://user-images.githubusercontent.com/86580417/166766980-ff483086-f5e2-4cdc-a042-46ba5da9d71c.png)
---
## 3. Which domain belonged to 81.166.122.238 at the time of capture? **www.harveycartel.org**
  
  a. First, let's filter for that IP address. 
  
  ![swimming-3a](https://user-images.githubusercontent.com/86580417/166781370-0a25bb1b-1a0a-4c89-9e74-67a62d1b518f.png)
  
  b. We are immediately shown an http conversation destined to 81.166.122.238. Let's take a look: Follow the TCP stream!
  
  ![swimming-3b](https://user-images.githubusercontent.com/86580417/166801551-345d0258-dbc3-4567-a4a9-3a83a22b0de0.png)
  
  c. This shows the GET request being sent to www.harveycertel.org which was hosted at 81.166.122.238:80
  
---
## 4. What was the capture date? **2015-03-17**

  a. To get the date we can change the Time/Date view to display the full date instead of the milliseconds since the beginning of the capture:
  
  ![swimming-4a](https://user-images.githubusercontent.com/86580417/166806381-6de1b017-f572-44c3-b467-84e98a226915.png)
  
  b. Once this is complete we can simply view the dates in the PCAP:
  
  ![swimming-4b](https://user-images.githubusercontent.com/86580417/166806456-307b86b2-49bd-4cf8-8d65-2771aeb8b403.png)
---
## 5. Which operating system did Kim use during the event? 



