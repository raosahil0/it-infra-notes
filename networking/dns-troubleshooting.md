# 🌐 DNS Troubleshooting

---

## 📌 What is DNS?

DNS converts domain names into IP addresses.

Example:
google.com → 142.250.x.x

---

## ⚠️ Common Issues

### 1. Website Not Opening

### Causes
- DNS server not responding  
- Wrong DNS configuration  

### Troubleshooting
- Try opening via IP address  
- Check DNS server settings  
- Use alternative DNS (e.g., 8.8.8.8)  

### Fix
- Update DNS settings  
- Restart network  

---

### 2. Slow Website Loading

### Causes
- Slow DNS resolution  
- Network latency  

### Troubleshooting
- Check DNS response time  
- Flush DNS cache  

### Fix
- Change DNS server  
- Clear cache  

---

### 3. Intermittent Resolution

### Causes
- DNS server instability  

### Troubleshooting
- Test with multiple DNS servers  

### Fix
- Switch to reliable DNS  

---

## 🔧 Useful Commands

- `ping google.com`
- `nslookup google.com`
- `ipconfig /flushdns`

---

## 🔥 Real-World Insight

- If internet works but website doesn’t → often DNS issue  
- Always test:
  - domain vs IP  

---

## 🧩 Interview Insight

Shows:
- Understanding of name resolution  
- Ability to isolate DNS vs network issue  