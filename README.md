# -AI-Powered-YouTube-Title-Description-Generator
An n8n-based AI agent that automatically generates YouTube titles and descriptions using OpenAI based on video transcript or input.
# 🎥 AI-Powered YouTube Title & Description Generator (n8n + Gemini)

An automated YouTube content generator built with [n8n] that processes video links from Google Sheets, summarizes content using RapidAPI, generates SEO-optimized descriptions with Gemini, and crafts viral titles using an AI agent. Final results are emailed and logged back into Google Sheets to streamline content creation.

---

## 🚀 Key Features

- Scheduled workflow execution  
- Reads new YouTube video links from Google Sheets  
- Summarizes video content via RapidAPI  
- Generates rich, SEO-friendly descriptions using Gemini (LLM chain)  
- Creates catchy, viral titles through an AI agent  
- Sends final title and description via Gmail  
- Logs all generated outputs back into Google Sheets  

---

## 🔄 Workflow Overview

1. **Trigger:** Scheduled run at defined intervals  
2. **Input:** Fetches new video links from Google Sheets  
3. **Summary Generation:** RapidAPI processes video link to extract key points  
4. **Description Generation:** Gemini generates detailed video descriptions  
5. **Title Generation:** AI agent crafts engaging, viral titles  
6. **Output:** Sends results via Gmail and updates Google Sheets  

---

## 🧪 Demo Output Example

**Video Link Input (from Google Sheet):**  
https://www.youtube.com/watch?v=1aR7tcmWo_w

**Generated Title:**  
1. ⚡️ 10 JavaScript Tricks You Should’ve Learned Yesterday!
2. 🧨 Stop Using `var`! Learn Modern JavaScript FAST 💻
3. 🧠 I Solved 5 JavaScript Problems… Here’s What I Learned
4. 😱 You’re Writing JavaScript WRONG – Here’s How to Fix It!
5. 🔥 Master JavaScript in 7 Days – No BS, Just Code!
6. 🚀 From Beginner to JavaScript Pro in One Video
7. 🧪 This JavaScript Hack Will Save You HOURS!
8. 💥 JavaScript Developers DON’T Want You to Know This!
9. 🕵️‍♂️ Can You Solve This JavaScript Puzzle? (98% Fail!)
10. 📉 Why Your JavaScript Code is Slowing Everything Down

**Generated Description:**  
Do you understand JavaScript tutorials but struggle when it comes to writing your own code? This comprehensive Part 2 of our "JavaScript: Become a Developer" series is designed to solve exactly that, taking you from theory to practical application! 🚀 Join Harshvandana Sharma from Sheryians Coding School as he breaks down advanced JavaScript concepts and builds real-world projects step-by-step. In this in-depth tutorial, you'll master: * **DOM Manipulation:** Learn how to select, modify, and dynamically create/remove elements on your web page. * **Events & Event Handling:** Understand how to make your websites interactive by responding to clicks, inputs, mouse movements, and more. * **Forms & Form Validation:** Build robust forms with JavaScript, preventing default submissions and implementing client-side validation using regex and conditional error messages. * **Timers & Intervals:** Discover `setTimeout` and `setInterval` to control the timing of your JavaScript code, creating dynamic effects like download progress bars and countdowns. * **Local Storage, Session Storage & Cookies:** Dive deep into client-side data storage, learning the differences and practical applications of each, including how to store complex data structures. This video includes hands-on projects like a live character counter, custom file upload, an email/password validator, a theme preference manager, and a real-time search filter! Don't just watch, code along and transform your JavaScript skills. 👍 Like this video if you found it helpful! 🔔 Subscribe to Sheryians Coding School for more advanced web development tutorials. ➡️ Watch Part 3 coming soon – follow us on Instagram & X (formerly Twitter) for updates! **Connect with us:** * **Sheryians Coding School:** * Instagram: [@sheryianscodingcollege](https://www.instagram.com/sheryianscodingcollege/) * X: [@SheryiansCoding](https://twitter.com/SheryiansCoding) * **Harshvandana Sharma:** * Instagram: [@harshvandanamaybe](https://www.instagram.com/harshvandanamaybe/) * X: [@harsh_bhaiya](https://twitter.com/harsh_bhaiya) * LinkedIn: [Link to Harsh's LinkedIn if available, otherwise remove] **🚀 Ready to take your coding to the next level?** Explore our comprehensive web development courses and bootcamps at [sheryians.com](https://sheryians.com). --- 🔍 **SEO Meta Tags:** JavaScript tutorial, JS for developers, DOM manipulation, JavaScript events, event handling, form validation JavaScript, JavaScript projects, local storage JS, session storage, cookies JavaScript, setTimeout, setInterval, JavaScript fundamentals, web development tutorial, Sheryians Coding School, Harshvandana Sharma, JS DOM, addEventListener, JavaScript forms, regex JavaScript, client-side storage, character counter JS, theme preference JS, real-time search filter, JS concepts, coding for beginners, advanced JavaScript 
#️⃣ **Hashtags:** #JavaScript #JS #WebDevelopment #CodingTutorial #DOMManipulation #EventHandling #FormValidation #LocalStorage #SessionStorage #Cookies #Timers #JavaScriptProjects #BecomeADeveloper #SheryiansCodingSchool #HarshvandanaSharma #Programming #FrontendDevelopment #WebDev #CodingForBeginners in md foramt

---

## ⚙️ Technologies Used

- **n8n:** Low-code automation platform  
- **Google Sheets:** Input and output data storage  
- **Gmail:** Email delivery of generated content  
- **RapidAPI:** Video content summarization  
- **Gemini (LLM chain):** SEO-friendly description generation  
- **AI Agent (LLM):** Viral title creation  

---

## 🧩 Future Enhancements

- Auto-publish generated content as YouTube drafts via API  
- Integrate hashtag and keyword generation  
- Support multilingual content generation  

---

Feel free to explore the workflow and adapt it to your needs.
