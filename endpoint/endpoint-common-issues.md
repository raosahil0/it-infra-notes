# 💻 Endpoint Common Issues & Fixes

---

## 1. Endpoint Not Connecting to Server

### Problem
Device not syncing with endpoint management server.

### Possible Causes
- Agent not running  
- Network issue  
- Firewall blocking communication  

### Troubleshooting
- Check internet connectivity  
- Restart endpoint agent service  
- Verify server URL accessibility  
- Check firewall rules  

### Fix
- Restart agent  
- Reinstall agent if required  
- Allow required ports in firewall  

---

## 2. Device Not Receiving Policies

### Problem
Policies not applied to endpoint.

### Possible Causes
- Agent not updated  
- Sync failure  
- Device not in correct group  

### Troubleshooting
- Force policy sync  
- Check agent status  
- Verify device group  

### Fix
- Reassign policy  
- Update/reinstall agent  

---

## 3. Patch Deployment Failure

### Problem
Patches not installing on device.

### Possible Causes
- Device offline  
- Insufficient permissions  
- Patch repository issue  

### Troubleshooting
- Check device status  
- Verify patch download  
- Review logs  

### Fix
- Retry deployment  
- Ensure device connectivity  
- Fix repository access  

---

## 4. Slow System Performance

### Problem
User reports system is slow.

### Possible Causes
- High CPU usage  
- Background updates  
- Endpoint scans  

### Troubleshooting
- Check task manager  
- Identify high resource processes  
- Check endpoint scan activity  

### Fix
- Stop unnecessary processes  
- Reschedule scans  
- Optimize system  

---

## 🔥 Key Insight

Most endpoint issues are caused by:
- Agent problems  
- Connectivity issues  
- Policy misconfiguration  

Not complex system failures.