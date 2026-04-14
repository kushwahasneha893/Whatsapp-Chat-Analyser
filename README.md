# WhatsApp Chat Analyzer 📊

This project analyzes WhatsApp chat data to extract meaningful insights and visualize communication patterns. It processes exported chat files and provides statistics related to messages, users, and activity trends.

## 📌 Problem Statement

WhatsApp chats contain a large amount of unstructured text data. This project aims to analyze chat logs and transform them into structured insights such as message frequency, user activity, and word usage.

## 🚀 Features

* Total messages, words, media, and links count
* User-wise message statistics
* Daily and monthly activity timeline
* Most active users identification
* Word frequency analysis
* Emoji analysis
* Data visualization using graphs

## 🧠 How It Works

1. Export WhatsApp chat as `.txt` file
2. Preprocess chat data:

   * Remove system messages
   * Extract date, time, user, and message
3. Perform analysis:

   * Count messages, words, links
   * Identify active users
4. Visualize results using charts

## 🛠️ Tech Stack

* Python
* Pandas
* Matplotlib
* Seaborn
* Regex (for text processing)

## 📁 Project Structure

```id="wapp1"
whatsapp-chat-analyzer
│
├── app.py
├── helper.py
├── preprocess.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Setup

1. Clone the repository:

```id="wapp2"
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
```

2. Navigate to project folder:

```id="wapp3"
cd whatsapp-chat-analyzer
```

3. Install dependencies:

```id="wapp4"
pip install -r requirements.txt
```

4. Run the application:

```id="wapp5"
python app.py
```

## 📊 Output

The application generates:

* Message statistics
* Activity graphs (daily/monthly trends)
* Word cloud
* Emoji usage insights

## 📂 Input Format

Export your WhatsApp chat:

* Open chat → More → Export Chat → Without media
* Use `.txt` file as input

## 🔮 Future Improvements

* Real-time chat analysis dashboard
* Sentiment analysis integration
* Web deployment using Streamlit
* Support for group chat comparison

## 👩‍💻 Author

Sneha Kushwaha
