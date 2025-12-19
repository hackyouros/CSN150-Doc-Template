# Cybersecurity : CSN150
Project: Gophish

## Purpose
Send some phishing emails & explore how phishers do it. 

## Equipment
* Computer
* Gophish
* Email account

## Links to documentation and tools
* [Gophish](https://getgophish.com/)
* [GitHub link for Gophish (Latest version as of 12/18/2025)](https://github.com/gophish/gophish/releases/tag/v0.12.1)

# Steps for using Gophish to send phishing emails
1. **Download Gophish**
   - Visit the official [Gophish GitHub page](https://github.com/gophish/gophish) or the [official website](https://getgophish.com/) to download the latest version of Gophish.
   - Choose the appropriate version for your operating system (Windows, macOS, or Linux).

2. **Extract the Gophish Files**
   - After downloading, extract the compressed file (usually a `.zip` or `.tar.gz`).

4. **Navigate to the Gophish Folder**
   - Open your terminal or command prompt and navigate to the extracted Gophish directory.

5. **Start the Gophish Server**
   - Run the command to start the Gophish server

6. **Access the Admin Panel**
   - Open your browser and navigate to `http://127.0.0.1:3333` or the address provided.

7. **Configure Gophish**
   - Once logged in, configure the Gophish server settings, such as SMTP server settings for sending emails and other parameters.
   - Update your SMTP settings to use a mail server that allows you to send emails from Gophish.

8. **Create a New Phishing Campaign**
   - In the admin panel, go to the “Campaigns” section and click on “New Campaign.”
   - Fill in the details, including email templates, landing pages, and targets.

9. **Design Email Templates**
   - Create realistic email templates for your phishing campaign (e.g., a cloned email from a legitimate source).
   - You can use the built-in email template editor or upload HTML files for the email content.

10. **Create Landing Pages**
    - Design or clone a phishing landing page that will be presented to users who click the email link.
    - Customize the page with necessary form fields (e.g., login page for phishing) and other elements.

11. **Set Up Targets**
    - Add the email addresses of the targets to the campaign.

12. **Launch the Campaign**
    - Once all settings are configured, launch the campaign.
    - Monitor the campaign’s performance and track results in the Gophish dashboard.

## Problems and Solutions
* No problems.

## Final Report
This project demonstrates how to use Gophish, an open-source phishing framework, to simulate phishing attacks for educational purposes. The objective was to showcase how phishing campaigns can be carried out, with a focus on raising awareness about social engineering tactics and improving security practices.

## Screenshots
This is the fake email. Looks legit but is not. It shows how easy these tools can make phishing & how legit they can look↓↓↓↓<img width="1920" height="870" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/f562896b-4e41-4727-b7ff-a236cf2258b3" />

This is confirming the email work & is ready for phishing↓↓↓↓<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/f87c289c-b796-44e8-a631-bfe631a777db" />

This is testing your email to make sure it works↓↓↓↓<img width="1920" height="907" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/c6ba11b9-9499-4039-a496-f4b6b47079f5" />

This is the page they'd land on after clicking any links in the email↓↓↓↓<img width="1920" height="908" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/7d8632fb-cc84-480f-aae8-053504ef7f66" />
