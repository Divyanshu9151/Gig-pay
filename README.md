# 🚀 GigPay — Real-Time Payroll for Gig Workers

## 🧩 Problem

India has over **15 million gig workers** (delivery, home services, etc.) who typically receive payments **5–7 days after completing tasks**.

This delay creates:
- Financial stress for daily expenses (fuel, food, recharge)
- Dependence on high-interest, predatory credit systems
- Lack of financial inclusion for a large workforce

---

## 💡 Solution

**GigPay** is an **autonomous on-chain payroll agent** that enables **instant payments for gig workers**.

Instead of waiting days, workers get paid **within seconds of task completion**.

### ⚡ Key Idea
- Platforms pre-fund an escrow pool
- Tasks are verified in real-time
- Payments are released instantly via smart contracts

---

## 🛠️ How It Works

1. 📦 Worker completes a task  
2. 🤖 AI agent listens to platform webhook  
3. 🔐 Verification happens via **x402 oracle (HTTP 402 flow)**  
4. ✅ Proof is validated cryptographically  
5. 💰 Smart contract releases payment in **USDC**  
6. 💸 Worker can instantly convert to INR via UPI  

⏱️ Total time: **< 30 seconds**

---

## 🧱 Architecture

- **Blockchain:** Algorand  
- **Smart Contracts:** PyTeal / ARC4  
- **Verification Layer:** x402 SDK (pay-per-verification oracle)  
- **Backend Agent:** Python (event-driven AI agent)  
- **Frontend:** React (Worker dashboard)  
- **Payments:** USDC → INR offramp via UPI  

---

## 🔑 Key Features

- ⚡ Instant micro-payments per task  
- 🔍 Trustless delivery verification  
- 🔐 On-chain escrow & settlement  
- 🤖 Autonomous AI-driven payroll agent  
- 📊 Real-time worker dashboard  
- 🇮🇳 INR offramp via UPI  

---

## 🌍 Impact

- Eliminates delayed payments  
- Reduces dependency on credit apps  
- Enables financial inclusion at scale  
- Generates real on-chain transaction volume  

---