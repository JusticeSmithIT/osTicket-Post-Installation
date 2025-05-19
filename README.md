# osTicket-Post-Installation






<h2>Description</h2>
This project demonstrates the post-installation of the ticketing system, osTicket, showing how to use Admin and Agent Panels. Also, creating teams, departments, agents, help topics, and SLA plans.


<h2>Languages and Utilities Used</h2>

- <b>osTicket</b>


<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> 

<h2>Program walk-through:</h2>

<p align="center">
Once you log in, navigate to the top right corner and make sure you are in the Admin panel, if you can see "Agent Panel" then that means you are in the Admin panel. Click  <br/>
  
![image](https://github.com/user-attachments/assets/d51ea604-dd60-475b-a3be-9c2dceba52a8)

<br />
<br />

Select Destination Server, which in this case it is "dc-1" and select "next.". <br/>

![image](https://github.com/user-attachments/assets/668fd29b-e419-40f9-a3b6-bd356de3c751)



<br />
<br />


Once you get to this window, select "add features" and keep the box checked that says "include management tools," then click next. <br/>

![image](https://github.com/user-attachments/assets/fe947089-d5fd-464d-b1b6-6d510ead61ae)




<br />
<br />


Confirm installation selections and allow automatic restarts. Check the box that shows "Restart the destination server automatically if required.":  <br/>

![image](https://github.com/user-attachments/assets/96bf5ca2-31fd-49c0-848c-a1b6e2c60dc2)



<br />
<br />
The Installation process will then start, wait a few moment for it to complete.   <br/>

![image](https://github.com/user-attachments/assets/b3be1edf-4172-4c18-9084-55feaa5b6880)



<br />
<br />
The Installation process is now complete but we still must promote the server to a domain controller.  <br/>

![image](https://github.com/user-attachments/assets/db730492-5d0d-4b27-bc4b-6398f28d244d)




<br />
<br />
Select the flag icon in the top right corner of the window and under "post deployment configuration" click "promote this server to a domain controller."  <br/>

![image](https://github.com/user-attachments/assets/f77836e6-f2a1-4011-91fa-c0ffcd6c615e)



In this window, select add a new forrest and name it "mydomain.com", then select next.  <br/>

![image](https://github.com/user-attachments/assets/08ab55ea-099c-44c1-bfdb-8fb5f0206472)


Under domain controller options, leave everything the way it is besides the password. Create a password and confirm it. This is the password for non-local users to log in with for the new domain.  <br/>

![image](https://github.com/user-attachments/assets/d48f184b-3a50-439e-902a-3814b2eecda5)



Deselect the box, "create DNS delegation" and select next.  <br/>

![image](https://github.com/user-attachments/assets/9f791c2d-5d87-408e-b7df-925fb2bb613b)


The Prerequisites check will take a few moments to finish.  <br/>

![image](https://github.com/user-attachments/assets/56188418-e49f-4f48-b490-e18543700bf3)


Installation will now begin, wait a few moments for completion.  <br/>

![image](https://github.com/user-attachments/assets/d1716eed-ed51-4c1d-aebb-f4acbd685f7a)


As soon as the installation is complete, the computer will automatically restart.  <br/>

![image](https://github.com/user-attachments/assets/206679d0-c116-4d24-9b59-2760e986bff7)


Log back in to dc-1 as your domain, in this case it is "mydomain.com\user." Once you are logged in, press the start button in the bottom left corner, and search for "active directory users and computers." If it shows up, then active directory has been properly installed.  <br/>

![image](https://github.com/user-attachments/assets/90a6d53f-f71c-4742-b02f-7043ea6500b6)

Log back in to dc-1 as your domain, in this case it is "mydomain.com\user." Once you are logged in, press the start button in the bottom left corner, and search for "active directory users and computers." If it shows up, then active directory has been properly installed.  <br/>

![image](https://github.com/user-attachments/assets/0c625cfe-26d8-40fd-b667-597838db8664)

Log back in to dc-1 as your domain, in this case it is "mydomain.com\user." Once you are logged in, press the start button in the bottom left corner, and search for "active directory users and computers." If it shows up, then active directory has been properly installed.  <br/>

![image](https://github.com/user-attachments/assets/1386c1dd-ac1b-4bb0-a54c-7ec437402f07)

As soon as the installation is complete, the computer will automatically restart.  <br/>

![image](https://github.com/user-attachments/assets/ee12232e-25c6-4343-8626-c1be9cfec0a3)

As soon as the installation is complete, the computer will automatically restart.  <br/>

![image](https://github.com/user-attachments/assets/26b8b68d-6765-4215-8720-3cd254b0b36d)

As soon as the installation is complete, the computer will automatically restart.  <br/>

![image](https://github.com/user-attachments/assets/66ba47d6-5a0f-4da7-a7fc-bc9c4e922527)
