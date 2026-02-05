# Expense Detective 🧠💸

Expense Detective helps people understand *why* their money disappears — without manual expense tracking.

## ✨ Key Features
- Upload bank statements (PDF / CSV)
- Automatic transaction categorization
- AI-generated spending insights
- Subscription detection
- Ask questions in plain English

## 🧠 How It Works
1. User uploads a bank statement
2. Data is parsed asynchronously
3. Transactions are normalized and categorized
4. AI detects patterns and generates insights
5. Users explore insights or ask questions

## 🏗 Architecture
- Frontend: React / Next.js
- Backend: Node.js (API + orchestration)
- AI Engine: Python (LLM + deterministic logic)
- Database: PostgreSQL
- Queue: Redis
- Storage: S3-compatible object storage

## 🔐 Privacy First
- No bank credentials stored
- Files processed asynchronously
- Users can delete data anytime

## 🚀 Why This Project
Most finance apps focus on tracking. Expense Detective focuses on *understanding*.

Built as a full-stack + AI system with real-world constraints.
