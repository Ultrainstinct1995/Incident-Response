# Incident-Response


## Introduction

In this project, I conducted an incident response investigation focused on addressing alerts and potential security breaches targeting my VM infrastructure. By intentionally triggering alerts and simulating intrusion attempts, I created a controlled environment to understand incident response processes firsthand.

Throughout the project, I documented each step of the incident response lifecycle, from detection to mitigation. I assessed the severity of each case and devised response strategies in collaboration with security teams and system administrators.

Ultimately, this project provided practical experience in incident response, equipping me with the skills to detect, respond to, and mitigate security incidents effectively.

The showcased metrics include the steps of part 2 of the Detection and Analysis phase and also following the incident response playbook if further action requires it for the Containment, Eradication and Recovery phase. 



## First and Foremost! I took the initative to always prepare and i have already did that following ingestion in the Log analytics in my azure account.


## Step 1
![image](https://github.com/Ultrainstinct1995/Incident-Response/assets/155921166/0ac15698-f848-4130-a20c-19e4a700e846)


In this image, I've configured parameters to track a potential threat: a Brute Force Attack SUCCESS on my VM. By setting the owner, status, and severity, I'm ensuring a thorough investigation. With the owner as myself, I oversee the investigation and coordinate responses. The status keeps me updated on progress, while severity helps prioritize actions based on threat impact. This proactive approach demonstrates my commitment to securing my VM environment and mitigating risks effectively.




## Step 2
![image](https://github.com/Ultrainstinct1995/Incident-Response/assets/155921166/d6b07d64-b235-4add-a3fc-f8d3d45243ff)


I took the initiative to review and investigate the issue firsthand. With meticulous attention to detail, I ensure thorough scrutiny of critical information, such as the IP address and host details of the computer involved etc. Additionally, I carefully track the frequency of attempted breaches to gain insights into the severity and persistence of the threat posed by the host attempting unauthorized access.



## Step 3
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/6c4db3f4-14d4-404d-b159-aff9d63e27b8)


As for here we observer the history and or activity log for anymore suspicious behavior.



## Step 4
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/1742c9b3-6db0-48ae-a15b-3e408f784618)


We search for the geographical information of where this is taken place or where the IP Address is located, We also observe the timeline and Activity that is taken place.



## Step 5
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/34e789e5-8499-4498-ae3f-2573eb58cfde)


Concerning this investigation, we carefully check network data to find anything unusual. we focus on spotting any other possible sources that the hacker may have tried to do. By looking at the investigation and how often they occur, we can understand how big the attack is. This helps us take quick action to protect the system from further harm.



## Step 6
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/00ff82e0-49b0-4258-87e4-b1eb2b58d9f4)


here we review the entities involved and check for any related events.





## Step 7
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/9e25bdc8-7098-4ff5-8440-9ed5b34fdfce)


Upon anticipating a brute force attack, I utilized KQL to investigate further and discovered ongoing failed login attempts from a specific IP address, even after a successful login. This persistence raised suspicion of a false positive, potentially triggered by a service account.





## Step 8
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/c78d8f77-d404-4435-a126-665be824c18b)



Based on my analysis, I've determined that this alert was a false positive due to incorrect alert logic. I've documented my findings and notes from the investigation in the comment box, and I've marked the alert as closed.






## Added Step (9)
## I have hidden the IP address as in asteriks 
![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/30f35a90-fa2c-4fc0-944b-c991577fb30f)

![image](https://github.com/Ultrainstinct1995/Incident-Response-NIST-Implementation/assets/155921166/1b6e5f13-c706-4a20-9d16-839274b688fd)


By establishing a private endpoint, addressing NIST recommendations, and implementing additional security rules, I've fortified the security of my environment. Additionally, a further layer of protection is provided with a restriction allowing access to my VM solely from my IP address, as depicted in another illustration.

