# LinkedIn-Post-Automation-with-n8n-Google-Gemini
Automate LinkedIn posting with n8n, Google Gemini AI, and Google Sheets! This workflow fetches topics, creates engaging posts using AI, publishes directly to LinkedIn, and updates your sheet with post status — boosting your online presence with zero manual effort. 🚀✨

# Automate your LinkedIn posting process using n8n, Google Gemini AI, and Google Sheets! This workflow:

1-Fetches post topics from Google Sheets 📋

2-Uses Gemini AI to generate compelling LinkedIn posts 🪄

3-Publishes them directly to LinkedIn 🔗

4-Updates Google Sheets with post status and timestamp 📝

# How It Works 👇

# [Schedule Trigger]
       ⬇️
# [Google Sheets: Get Rows (Not posted)]
       ⬇️
# [Google Gemini AI: Generate Post]
       ⬇️
# [LinkedIn: Publish Post]
       ⬇️
# [Google Sheets: Update Row]


1. Schedule Trigger ⏰
~Automatically triggers at a specified hour (e.g., every day at 10 PM).

~Initiates the automation sequence, so you don’t have to do it manually.

2. Get Rows from Google Sheets 📑
~Connects to your sheet and fetches rows where the status is “Not posted”.

~Ensures only new/unposted topics are considered.

3. AI-powered Post Generation 🤖
~Gemini AI receives the topic and generates a concise, engaging LinkedIn post.

~Uses a custom prompt to ensure:

~Under 250 words 🖋️

~Includes a hook and call to action

~No AI boilerplate language—just clean content!

4. Publish to LinkedIn 🌐
~The generated content is posted directly to your LinkedIn account.

~Seamless integration with LinkedIn OAuth credentials.

5. Update Google Sheets 🗂️
~After posting, the workflow updates the original row:

~Sets status to “posted”

~Adds “Posted at” timestamp (current date & time)

~Tracks your history and avoids duplicate posting.


 # 🟢 Optional: Email Notification

If configured, you can add an email node to notify when a post is successfully published.

