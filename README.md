# Lab-Sudden-Network-Slowdowns

## 🛡️ Objective

The **server team** reported **significant network performance degradation** on several older devices within the **10.0.0.0/16** network range.  
After ruling out any external Distributed Denial of Service (**DDoS**) attacks, the **security team** suspected that the cause might be **internal network activity**.

All traffic originating from within the local network is by default allowed by all hosts. There is also unrestricted use of PowerShell and other applications in the environment. It’s possible someone is either downloading large files or doing some kind of port scanning against hosts in the local network.

**Goal:**  
Investigate the root cause of the performance degradation and determine whether malicious or unauthorized internal activity — such as **network scanning** — was occurring.
