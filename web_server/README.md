## 📂 Files Overview

1. **0-transfer_file**  
   - Bash script to transfer a file from local machine to a remote server using `scp`.  
   - Accepts 4 parameters: file path, server IP, username, and SSH private key path.  
   - Transfers the file to the user’s home directory (`~/`).  

2. **1-install_nginx_web_server**  
   - Bash script to install and configure **Nginx** on the server.  
   - Ensures Nginx is running and accessible on port 80.  
   - Automates installation without manual intervention.  

3. **2-setup_a_domain_name**  
   - Bash script to configure a domain name pointing to the server’s IP.  
   - Uses DNS records to associate the domain with the server.  
   - Ensures the domain resolves correctly to the web server.  

4. **3-redirection**  
   - Bash script to configure Nginx to redirect traffic.  
   - Redirects requests from one URL to another (e.g., `/redirect_me`).  
   - Implements HTTP redirection rules.  

5. **4-not_found_page_404**  
   - Bash script to configure a custom **404 error page** in Nginx.  
   - Ensures users see a friendly error page when accessing non-existent resources.  

6. **5-design_a_beautiful_404_page.html**  
   - HTML file containing a styled, user-friendly **404 error page**.  
   - Designed to replace the default Nginx error page with a customized version.  

---

## ⚙️ Project Notes
- All scripts must be executable (`chmod +x filename`).  
- Scripts must start with `#!/usr/bin/env bash` and include a descriptive comment.  
- Must pass **Shellcheck (v0.3.7)** without errors.  
- Environment: **Ubuntu 16.04 LTS**.  
- Scripts are run as root (no need for `sudo`).  

---
