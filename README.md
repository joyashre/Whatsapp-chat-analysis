# 📱💬 WhatsApp Chat Analysis 📊🧠
![image](https://github.com/user-attachments/assets/124266df-3487-4991-9912-2c814c3b2b60)

Dive into the insights of your WhatsApp group conversations using data visualization techniques like Word Clouds. This analysis helps uncover patterns, frequent topics, and the chatting behavior of each participant—turning raw chat logs into meaningful visuals!


A Python-based project to analyze and visualize WhatsApp group chats using word clouds, emoji usage, and more. This tool helps uncover patterns in conversations, top contributors, and commonly used words.

---

## 🚀 Features

- 📊 **Group Word Cloud** – Visualize the most used words in the group.

- 👤 **Author-wise Word Clouds** – See what each person talks about most.

- 😂 **Emoji Frequency Analysis** – Find out which emojis are used the most (optional).

- 📈 **Message Statistics** – Basic stats like total messages, words, media shared (optional extensions).

- 📅 **Time-based Analysis** – Check activity by day, hour, or month (extendable).

---

## 🛠️ Installation libraries


### 📂 How to Use

#### >1️⃣ Extract Your WhatsApp Chat

To get your chat exported:

Open the WhatsApp chat 📱.

Click on the three dots (⋮) > More > Export Chat.

Choose to export without media, and share it via email or save it to your PC.

#### >2️⃣ Load & Clean the Chat Data

Use pandas to read and process the exported .txt file. Preprocessing steps may include:

Splitting lines into date, time, author, and message.

Filtering out system messages.

Removing media placeholders.

You can also use regex to parse and structure the data.

#### >3️⃣ Run the Analysis

#### > 📊 Sample Output

Word clouds showing dominant words

![wordjo](https://github.com/user-attachments/assets/28218863-e926-442f-9554-f66ba25dddd0)


Author-wise contribution visualization

Emoji usage 

#### 📌 Future Improvements (Optional)

⏰ Add time-based activity heatmaps

📉 Track monthly or daily message volume

🧠 Sentiment analysis using NLP

🌍 Geo-location based activity (if metadata available)

