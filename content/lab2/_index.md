+++
title = "Lab #2"
weight = 70
+++

### Scaling the application front-end

The first iteration of the application's web front end is not inherently scalable becaue the database and front end are located on the same machine. It would be problematic to add additional database instances whenever additional front-end capacity was needed. 

To fix this issue the front end and database each need to be running on their own instance. In this lab you will create an instance for the database and one for the web front end. Then you will take a snapshot of the web front end, and deploy two additional web front end instances from that snapshot. Finally, you'll add a loadbalancer in front of the three front end instances. 