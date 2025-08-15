![Skyport Banner](<img width="821" height="532" alt="image" src="https://github.com/user-attachments/assets/a1842bfd-323d-4c98-b335-5a6fd3b7b9fc" />
)

# How to Create Skyport Panel in Any VPS (CodeSandbox, GitHub Codespaces, Gitpod, etc.)

This guide will help you set up the **Skyport Panel** and Wings/Node on any VPS running Debian/Ubuntu.  
It has been tested and confirmed to work 100% on:
- CodeSandbox
- GitHub Codespaces
- Gitpod
- Any VPS with Debian/Ubuntu

---

## 🚀 Panel Installation
```bash
# Switch to root user
sudo su

# Run the panel installation script
bash <(curl -s https://raw.githubusercontent.com/JishnuTheGamer/skyport/refs/heads/main/panel)
```

---

## 🛠 Wings / Node Installation
```bash
# Switch to root user
sudo su

# Run the wings installation script
bash <(curl -s https://raw.githubusercontent.com/JishnuTheGamer/skyport/refs/heads/main/wings)

# Navigate to skyportd directory
cd skyportd

# Paste your node configuration
# (Follow instructions in Skyport Panel to get this configuration)

# Start the node using PM2
pm2 start .
```

---

## ✅ Mission Successful!
Your **Skyport Panel** and node are now up and running.  
Log in to the panel via your browser, add nodes, and start hosting!

---

**Credit:** Jishnu Extra  
**Subscribe on YouTube:** [@ITZ_YTANSH_OFFICAL](https://youtube.com/@Jishnuextra69)

![Skyport Footer](<img width="821" height="414" alt="image" src="https://github.com/user-attachments/assets/b80e92a6-e4ff-4865-b953-ccb895572111" />
)
