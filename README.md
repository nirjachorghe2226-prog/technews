# 🚀 Tech News Research Agent

An AI-powered automated research workflow that collects technology news from multiple sources, generates intelligent summaries, and distributes curated reports through Email and Discord.

---

## 📌 Project Overview

The Tech News Research Agent automates the entire process of technology news discovery, analysis, and distribution.

The workflow continuously gathers articles from multiple RSS sources, combines and processes them, uses AI to identify the most relevant technology news, generates concise summaries, and automatically delivers reports to communication channels.

This eliminates the need for manual news monitoring while ensuring timely access to important technology updates.

<img width="1120" height="432" alt="Screenshot 2026-06-12 at 9 33 53 PM" src="https://github.com/user-attachments/assets/a3680991-65b1-4bd6-b1ca-0200a5d3b034" />

---

## 🎯 Objective

Build an autonomous AI research agent capable of:

* Collecting technology news from multiple sources
* Identifying the most relevant stories
* Generating AI-powered summaries
* Creating structured research reports
* Delivering reports automatically through Email and Discord

---

## ⚙️ Workflow Architecture

```text
Daily Schedule
      │
      ▼
 ┌─────────────┐
 │ Hacker News │
 └─────────────┘
      │
 ┌─────────────┐
 │ TechCrunch  │
 └─────────────┘
      │
 ┌─────────────┐
 │ RSS Feeds   │
 └─────────────┘
      │
      ▼
Combine All Articles
      │
      ▼
JavaScript Processing
      │
      ▼
AI Categorization & Summarization
      │
 ┌────┴────┐
 ▼         ▼
Email   Discord
```

---

## 🔄 Workflow Steps

### 1. Daily Schedule Trigger

The workflow executes automatically based on a predefined schedule, ensuring continuous news monitoring without manual intervention.

### 2. News Collection

The agent collects articles from:

* Hacker News RSS Feed
* TechCrunch RSS Feed
* Additional RSS Sources

### 3. Article Aggregation

All collected articles are merged into a unified dataset for processing.

### 4. Data Processing

A JavaScript node prepares and formats the collected articles before sending them to the AI model.

Tasks include:

* Article aggregation
* Data cleanup
* Formatting
* Preprocessing

### 5. AI Analysis

Using an AI model through OpenRouter, the workflow:

* Analyzes collected articles
* Identifies technology-related news
* Selects the most important stories
* Generates summaries
* Produces formatted reports

### 6. Report Distribution

Generated reports are automatically delivered through:

#### 📧 Email

Daily technology news digests are sent directly to recipients.

#### 💬 Discord

Condensed summaries are posted automatically to Discord channels.

---

## ✨ Features

* Automated RSS feed monitoring
* Multi-source news aggregation
* AI-powered categorization
* Intelligent article ranking
* Automated summarization
* Daily report generation
* Email notifications
* Discord integration
* Scheduled execution
* End-to-end automation

---

## 🛠️ Technologies Used

### Automation
* n8n

### AI
* OpenRouter
* Large Language Models (LLMs)

### Data Sources
* Hacker News RSS
* TechCrunch RSS
* Custom RSS Feeds

### Integrations
* Gmail
* Discord Webhooks

### Processing
* JavaScript

---

## 📊 Workflow Benefits

### Time Savings
Eliminates manual research and news monitoring.

### Better Coverage
Aggregates articles from multiple trusted technology sources.

### Intelligent Filtering
AI selects only the most relevant technology stories.

### Automated Distribution
Reports are delivered automatically without user intervention.

### Scalability
New RSS feeds and delivery channels can be added easily.

---

## 🚀 Future Improvements

* Slack Integration
* News Deduplication
* Trend Analysis
* Sentiment Analysis
* Topic-Based Categorization
* AI-Powered Recommendations
* Web Dashboard
* Real-Time Alerts
---

## 📦 Deliverable

An autonomous AI-powered research agent that:

✅ Collects technology news automatically

✅ Aggregates articles from multiple sources

✅ Generates AI-powered summaries

✅ Creates structured research reports

✅ Delivers reports via Email and Discord

✅ Runs automatically on a schedule
---

## 👩‍💻 Built With

* n8n Workflow Automation
* OpenRouter AI Models
* RSS Feed Processing
* JavaScript
* Gmail Integration
* Discord Integration

## Sample Output

## 📧 Email Report

```html
<h1>📰 TECH NEWS DIGEST</h1>

<h2>1. [Article Title]</h2>

Summary:
• Point 1
• Point 2
• Point 3
• Point 4
• Point 5

Link:
[Original Article URL]

----------------------------------------------------------------------

<h2>2. [Article Title]</h2>

Summary:
• Point 1
• Point 2
• Point 3
• Point 4
• Point 5

Link:
[Original Article URL]
```

## 💬 Discord Report

```markdown
# 📰 Tech News Digest

## 1. [Article Title]

**Summary:**
• Point 1
• Point 2
• Point 3
• Point 4
• Point 5

**Link:**
[Original Article URL]

## 2. [Article Title]

**Summary:**
• Point 1
• Point 2
• Point 3
• Point 4
• Point 5

**Link:**
[Original Article URL]
```

