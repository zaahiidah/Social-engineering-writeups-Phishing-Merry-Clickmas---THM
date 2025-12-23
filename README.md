# Phishing Merry Clickmas - THM
TryHackMe Social Engineering Write-Ups

Social Engineering Write-Up
Name: ZAHIDAH AZ-ZAHRA BINTI SAFARIZAM
ID: 52215226218
Platform: TryHackMe

Exercise 1: Phishing-Merry Clickmas

1.	Objective<br>
The objective of this exercise is to understand how to use the Social-Engineer Toolkit to send phishing emails and harvest credentials by mimicking legitimate login page.

3.	Tools/Platform Used<br>
  •	TryHackMe<br>
  •	Social-Engineer Toolkit (SET)

5.	Steps Taken
   
      1. Set up a local environment to simulate a credential collection server.
      2. Verified the server connection through a web browser.
      3. Used the Social-Engineer Toolkit (SET) to explore social engineering attack options.
      4. Selected an email-based phishing attack scenario within the tool.
      5. Created a realistic phishing email scenario with a convincing subject line.
      6. Configured the email content to include a link to a simulated login page.
      7. Observed how user interaction with the phishing email could lead to credential capture.
      8. Monitored the server to understand how phishing attacks collect user input.
      9. Harvest the credentials from target users by using username and password capture. 

6.	Findings/What I learned <br>
  •	Human manipulation plays an important role in phishing attacks, especially through convincing messages and legitimate-looking sender email addresses.<br>
  •	Create fake login pages and phish email using the configured SMTP server<br>
  •	The Social-Engineer Toolkit (SET) supports various types of social engineering attacks and helps demonstrate how phishing campaigns are created.

6.	Conclusion<br>
This exercise gave exposure and awareness education on social engineering attacks by using Social Engineering Toolkit (SET) and showed how simple techniques can be used to deceive users.

7.	Evidence

 <img width="666" height="472" alt="image" src="https://github.com/user-attachments/assets/c7b845d3-a104-4d46-9c7b-79c04be688c5" />

Figure 1: Setup machine<br>


 <img width="694" height="532" alt="image" src="https://github.com/user-attachments/assets/03f3f184-2c92-460e-bfef-d09383d14c4a" />

Figure 2: Mimicking legitimate login page<br>


<img width="718" height="510" alt="image" src="https://github.com/user-attachments/assets/bf1d34b8-6616-4abf-8e21-a89a2136dc4a" />
 
Figure 3: Social Engineering Toolkit (SET) menu based<br>


<img width="727" height="552" alt="image" src="https://github.com/user-attachments/assets/018d184d-1e24-4023-8b15-711bea59b405" />
 
Figure 4: Create phishing email using SET <br>


 <img width="682" height="543" alt="image" src="https://github.com/user-attachments/assets/d2e5033a-01bb-44d5-835a-4a2b93a10061" />

Figure 5: Capture user’s username and password<br>


<img width="581" height="486" alt="image" src="https://github.com/user-attachments/assets/ac205630-e3ea-46ff-b0f3-215c840ee394" />
 
Figure 6: Access Roundcube Webmail to access user’s inbox using user’s password<br>


<img width="606" height="506" alt="image" src="https://github.com/user-attachments/assets/0dea6716-2365-4ac7-bf4f-c0fd50b206f1" />
 
Figure 7: In target user’s inbox and show our email we sent<br>


<img width="637" height="394" alt="image" src="https://github.com/user-attachments/assets/0beadbc7-d786-4d75-9566-080b426b1870" />
 
Figure 8: Complete task
