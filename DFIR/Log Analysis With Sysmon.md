# <a href="https://app.letsdefend.io/challenge/log-analysis-with-sysmon">Log Analysis With Sysmon</a>

**Platform:** LetsDefend

**Scenario:** Our company has experienced a breach on one of its endpoints. Your task is to investigate the breach thoroughly by analyzing the Sysmon logs of the compromised endpoint to gather all necessary information regarding the attack.

**Role:** DFIR

**Difficulty:** Easy

**Files:** `N/A`

**Tools:** `` 

**Note:** In this walkthrough, LetsDefend provides a lab environment for our use. However, I found the lab to be quite slow based on my experience.


![image](https://github.com/user-attachments/assets/a102b4e5-7d45-4875-8cbe-b8facef276b1)

![image](https://github.com/user-attachments/assets/b6bd4a82-41d3-475c-bba7-9314a5af4ceb)

![image](https://github.com/user-attachments/assets/9a0b74c3-9df8-470c-a02d-859affecadfb)

![image](https://github.com/user-attachments/assets/cde8d0b4-5e2e-45b0-bc3c-58b0c03dfa2f)

![image](https://github.com/user-attachments/assets/3c31398f-62cb-495d-b558-7a67262aefd8)


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
