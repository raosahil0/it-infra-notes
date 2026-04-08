# 🌐 What Happens When You Open a Website

Example: Opening https://google.com

---

## Step 1: URL Input

User enters URL in browser:
https://google.com

---

## Step 2: DNS Resolution

- Browser checks cache
- OS checks local DNS cache
- If not found → request sent to DNS server

DNS server returns:
google.com → IP address (e.g., 142.250.x.x)

---

## Step 3: TCP Connection

- System initiates TCP handshake with server
- 3-way handshake:
  1. SYN
  2. SYN-ACK
  3. ACK

Connection established

---

## Step 4: SSL/TLS Handshake (HTTPS)

- Secure connection established
- Certificate verified
- Encryption keys exchanged

---

## Step 5: Request Sent

Browser sends HTTP request:
GET / 

Includes:
- Headers
- Cookies
- User agent

---

## Step 6: Server Processing

- Request reaches server
- Application processes request
- Response generated (HTML, CSS, JS)

---

## Step 7: Response Received

Server sends response back:
- Status code (200 OK)
- Content

---

## Step 8: Browser Rendering

- HTML parsed
- CSS applied
- JS executed
- Page displayed to user

---

## ⚠️ Where Things Can Fail (Important)

- DNS failure → website not found  
- TCP failure → connection timeout  
- SSL issue → security warning  
- Firewall block → request denied  
- Slow response → server/network issue  

---

## 🔥 Real-World Relevance

This flow helps troubleshoot:
- “Website not opening”
- “Slow internet”
- “VPN connected but site not loading”
- “Application access issues”