# 🔥 Firewall Rules & Traffic Control

---

## 📌 Purpose

Firewall rules control **which traffic is allowed or blocked** between networks.

---

## ⚙️ Basic Rule Structure

- Source (who is sending traffic)
- Destination (where traffic is going)
- Service/Port (what type of traffic)
- Action (Allow / Deny)
- Priority (rule order)

---

## 🔍 Example Rule

### Scenario
Allow users to access websites over HTTPS.

### Configuration
- Source: LAN
- Destination: WAN
- Service: HTTPS (Port 443)
- Action: Allow
- Priority: Above deny rules

---

## ⚠️ Rule Processing Logic

- Firewall checks rules **top to bottom**
- First match = action applied
- If no match → default deny

---

## 🚫 Common Issues

### 1. Application Not Opening
- Cause: Traffic blocked by deny rule
- Fix: Check logs → create allow rule

---

### 2. Rule Not Working
- Cause: Wrong rule order
- Fix: Move rule above conflicting rules

---

### 3. Intermittent Access
- Cause: Session drops / load issues
- Fix: Check firewall resources

---

## 🔥 Real-World Insight

- Most issues are not “network failure”  
- They are **blocked by firewall policies**

---

## 🧩 Interview Insight

Shows:
- Understanding of traffic flow  
- Rule priority logic  
- Real troubleshooting ability  