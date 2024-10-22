# <a href="https://app.letsdefend.io/challenge/log-analysis-with-sysmon">Log Analysis With Sysmon</a>

**Platform:** LetsDefend

**Scenario:** Our company has experienced a breach on one of its endpoints. Your task is to investigate the breach thoroughly by analyzing the Sysmon logs of the compromised endpoint to gather all necessary information regarding the attack.

**Role:** DFIR

**Difficulty:** Easy

**Files:** `N/A`

**Tools:** `` 

**Note:** In this walkthrough, LetsDefend provides a lab environment for our use. However, I found the lab to be quite slow based on my experience.

## **Questions and Answers**

***1. Which file gave access to the attacker?***  
**Answer: IDM.exe 

***2. What did the attacker use to bypass UAC? Mention the EXE.***  
**Answer:** *********.***  

***3. What registry path and value was used by the above EXE to gain higher privileges? (path\value)***  
**Answer:** ****:\********\*******\**-********\*****\****\*******\********  

***4. The attacker dropped a file. What is the file location?***  
**Answer:** *:\*****\****\*********\********.***  

***5. What are the technique name and ID used by the dropped EXE?***  
**Answer:** ********** *******: *****  

***6. What is the name of the attack?***  
**Answer:** **** *** ****  

***7. What EXE did the attacker run using elevated privileges from the above attack?***  
**Answer:** **********.***  

***8. The attacker downloaded and ran a file. What is the filename?***  
**Answer:** *********.***  
