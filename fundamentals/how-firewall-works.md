# 🔥 How Firewall Works (Packet Flow)

---

## 📌 Goal

To inspect and control traffic between networks based on rules.

---

## 🔄 Step-by-Step Packet Flow

### 1. Packet Arrives at Firewall

- Source sends request (user/device)
- Packet reaches firewall interface  

---

### 2. Basic Validation

- Check if packet is valid  
- Check interface (LAN/WAN/VPN)

👉 Invalid packet → dropped immediately  

---

### 3. Session Check (Stateful Inspection)

- Firewall checks if session already exists  

👉 If YES → allow (fast processing)  
👉 If NO → move to rule evaluation  

---

### 4. Rule Matching

Firewall checks rules **top to bottom**:

- Source  
- Destination  
- Port/service  

👉 First matching rule is applied  

---

### 5. Action Applied

- Allow → packet forwarded  
- Deny → packet dropped  

---

### 6. NAT (if configured)

- Source/Destination IP may be translated  

---

### 7. Forwarding

- Packet forwarded to destination  

---

### 8. Logging

- Action recorded in firewall logs  

---

## ⚠️ Where Firewall Blocks Traffic

- No matching allow rule  
- Explicit deny rule  
- Wrong rule priority  
- Security policy restriction  

---

## 🔥 Real-World Insight

- Firewall doesn’t “break” traffic  
👉 It **intentionally blocks it based on rules**

- Most issues:
  - wrong rule order  
  - missing allow rule  

---

## 🧩 Interview Insight

Shows:
- Understanding of packet-level flow  
- Ability to debug using logs  
- Awareness of rule processing logic  