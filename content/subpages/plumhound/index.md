---
title: "Plumhound"
_build:
  list: never
---
google plumhound github


```
## Steps to Install (Subject to change - view github):

cd /opt
sudo git clone https://github.com/PlumHound/PlumHound.git
cd /opt/PlumHound
sudo pip3 install -r requirements.txt
```

## Process:

 Step 1:
 IMPORTANT! - need to keep bloodhound running in neo4j to utilize plumhound as it analyses the information injested from bloodhound in neo4j

Step 2:
 `sudo python3 PlumHound.py --easy -p neo4j1`     :    -p is for password set for neo4j  
 ![Pasted image 20251201215128](images/Pasted-image-20251201215128.png)
 
Step 3:
`sudo python3 PlumHound.py -x tasks/default.tasks -p neo4j1`
   used the default task

Step 4:
 `cd /opt/Plumhound/reports`

Step 5:
bunch of reports were present ....
`firefox index.html`

note: ignore the tags present in field like 'high value' or 'sensitive', figure that out on ur own
