# Real-Time Chat Application using Serverless Architecture

> **Objective:** Build a real-time messaging app using serverless architecture with WebSockets.

This project is a fully functional real-time chat application like WhatsApp Web / Slack, built entirely on serverless AWS services. It supports multiple users chatting instantly without page refresh.

**Guidelines Implemented:**
1. ✅ **Compute:** AWS Lambda (Python)
2. ✅ **API + Database:** API Gateway WebSocket API + DynamoDB for messages & connections
3. ✅ **Real-time:** WebSockets for instant updates

## 🚀 Live Working Demo

**Features Implemented & Tested:**
- ✅ **WebSocket Connection:** `wss://hucmib3l53.execute-api.ap-southeast-2.amazonaws.com/production`
- ✅ **Live Status:** `✅ Connected - LIVE!` / `Reconnecting...` handling
- ✅ **Real-time Broadcast:** Message from User A instantly appears in User B
- ✅ **No Duplicate Bug Fixed:** Sender exclusion logic implemented
- ✅ **Persistent Messages:** Chat history saved in DynamoDB
- ✅ **Auto Cleanup:** Disconnect Lambda removes stale connections


