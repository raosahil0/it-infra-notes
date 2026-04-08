## ⚠️ Multi-User Network Incident (Intermittent VPN & Application Failure)

---

### 📌 Problem

Multiple users across different locations reported:

- VPN disconnecting intermittently  
- Internal applications not loading  
- Frequent session drops  

The issue was inconsistent and difficult to reproduce.

---

### 🔍 Initial Assessment

- Impact: Multiple users (Pan-India)
- Scope: Not limited to a single system or location  
- Pattern: Occurring mostly during peak usage hours  

→ Indicated a **system-level issue**, not user-specific

---

### 🧠 Troubleshooting Approach

#### 1. Scope Validation
- Confirmed issue across multiple users  
- Eliminated local device/network as root cause  

#### 2. VPN Health Check
- Verified VPN service status on Sophos Firewall  
- Observed high number of active sessions  

#### 3. Firewall Log Analysis
- Checked live logs for denied/dropped traffic  
- Observed intermittent session drops (not consistent deny rules)

#### 4. Resource Monitoring
- Checked firewall CPU and memory usage  
- Noticed spikes during peak hours  

#### 5. Correlation
- High load + session drops + peak timing  
→ Strong indicator of **resource saturation**

---

### ⚠️ Root Cause

Firewall resource exhaustion under peak load resulted in:

- Dropped sessions  
- Unstable VPN connections  
- Intermittent application failures  

---

### 🛠️ Resolution

- Restarted VPN services to stabilize active sessions  
- Cleared inactive/stale connections  
- Optimized firewall rules to reduce processing overhead  
- Escalated for infrastructure capacity review  

---

### ✅ Outcome

- VPN stability improved  
- Reduced number of user complaints  
- Identified infrastructure limitation for future scaling  

---

### 🔥 Key Learning

- Intermittent issues often indicate **resource or load problems**, not configuration errors  
- Always correlate:
  - user impact  
  - system load  
  - timing patterns  

---

### 🧩 Interview Insight (Important)

This scenario demonstrates:

- Ability to handle **multi-user incidents**
- Understanding of **system behavior under load**
- Structured troubleshooting instead of guesswork