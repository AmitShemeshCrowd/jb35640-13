# DEVOPS COURSE
---
## news (updated on Mar 31th, 2019)
- maven issues:
  
  after investigating, the root cause for mvn not working properly, is fact maven was installed with older version, here is the fix:
```bash
wget https://www-us.apache.org/dist/maven/maven-3/3.6.0/binaries/apache-maven-3.6.0-bin.tar.gz -P /tmp
sudo tar xf /tmp/apache-maven-*.tar.gz -C /opt
sudo ln -s /opt/apache-maven-3.6.0 /opt/maven
sudo ln -s /opt/maven/bin/mvn /usr/local/bin/mvn
mvn --version
```
What we are going to do today: 
- translating jenkins "free-style" job into pipeline 
- deploying the output artifact into a target server:
  - how to deploy using jenkins node agent
  - using a "push method" from jenkins 
- introduction to docker


## news (updated on Mar 20th, 2019)
- PLEASE READ THE WHOLE MANUALS!!!

## news (updated on Mar 20th, 2019)
- Finally succeed with pushing you the HW :) 
- Several quizzes will be published today & every week 
- 2 more HW tasks will submitted soon
- please Open an Issue when you got Question
- if you want conf call tomorrow (Fri 22th), I will send the link
- will send more materials soon :)


## news (updated on Mar 3rd, 2019)
- HW from the 20190227, cay be delivered on Wen, 6th Mar 2019.
- on the lesson today we will review the HW & perform Introduction to the DevOps world
- HW for next lesson is on the air, at **home-works/20190227/readme.md**
- 2 new items added to **guide-book**:
    - vagrant @ **guide-book/devops-tools.vagrant.md**
    - tomcat @ **guide-book/operational-servers/tomcat.md**
- in the HW, you may skip the park to installing wetty 

## TODO (@danielm):
- add inside the guidebook linux commands references

enjoy your weekend,
I'm available for any other questions 
