+++
title = "2.3 - Scale the front-end"
weight = 25
+++

* Return to the <a href="https://lightsail.aws.amazon.com/ls/webapp/home/" target="_blank">Lightsail console home page</a>

* Click the 3 dot menu for the ***node-fe-1*** instance and choose ***Manage***

    ![](../../images/2-3-2.jpg?classes=border)

* From the horizontal menu choose ***Snapshots***

    ![](../../images/2-3-3.jpg?classes=border)

* Click Create Snapshot

    ![](../../images/2-3-4.jpg?classes=border)

    Under ***Recent snapshots*** the status will change to ***creating***, you will need to wait for the process to complete to move forward. This can take up to 5 minutes. 

* Click the 3 dot menu to the right of the newly created snapshot and select ***Create new instance***

    ![](../../images/2-3-5.jpg?classes=border)

* Scroll down and name the instance ***node-fe-2***

* Click ***Create***

* Click the 3 dot menu for the ***node-fe-1*** instance and choose ***manage***

    ![](../../images/2-3-2.jpg?classes=border)

* From the horizontal menu choose ***Snapshots***

    ![](../../images/2-3-3.jpg?classes=border)

* Click the 3 dot menu to the right of the previously created snapshot and select ***Create new instance***

    ![](../../images/2-3-5.jpg?classes=border)

* Scroll down and name the instance ***node-fe-3***

* Click ***Create***

* Test the public IP of each of the two newly created front end instances in your web browser. Notice that the hostname for that particular web front end instance is listed under your task list, and that it changes based on which instance you are visiting in your web browser

    ![](../../images/2-3-13.jpg?classes=border)