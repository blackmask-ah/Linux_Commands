# **Linux_Commands**
Basic & Advanced Commands of Kali Linux Everyone Should Know  

```bash
# 🔹 Basic Linux Commands
ls                      # List directory contents
pwd                     # Show current directory
cd [dir]                # Change directory
cp [src] [dest]         # Copy file or folder
mv [src] [dest]         # Move/rename file
rm -rf [file/folder]    # Delete file/folder
mkdir [dir]             # Create a directory
rmdir [dir]             # Remove empty directory
cat [file]              # View file contents
echo "text" > file      # Create file with text
touch [file]            # Create an empty file
clear                   # Clear terminal

# 🔹 User & System Management
whoami                  # Show current user
id                      # Show user ID (UID, GID)
passwd                  # Change password
adduser [user]          # Add a new user
deluser [user]          # Delete a user
usermod -aG [group] [user]  # Add user to a group
groups [user]           # Show groups of a user
hostname                # Show system hostname
uptime                  # Show system uptime
reboot                  # Restart system
shutdown now            # Shutdown system immediately

# 🔹 File Permissions & Ownership
chmod +x [file]         # Make file executable
chmod 777 [file]        # Give full permissions
chown user:group [file] # Change file owner
ls -l                   # Show file permissions

# 🔹 Networking & Ethical Hacking
ifconfig                # Show network interfaces (deprecated)
ip a                    # Show IP and network details
ping [host]             # Check network connection
netstat -tulnp          # Show open ports
nmap -A [IP]            # Scan target for vulnerabilities
whois [domain]          # Get domain info
dig [domain]            # Get DNS info
nslookup [domain]       # Find IP address of a domain
wget [URL]              # Download file from URL
curl -O [URL]           # Download file using curl
tor                     # Start Tor network
proxychains firefox [URL]  # Open browser via proxy

# 🔹 Advanced Penetration Testing (Kali Tools)
airmon-ng               # Enable monitor mode
airodump-ng wlan0       # Capture wireless packets
aircrack-ng -b [BSSID] [file]  # Crack WiFi password
metasploit              # Start Metasploit framework
msfconsole              # Open Metasploit console
sqlmap -u [URL] --dbs   # SQL Injection attack
hydra -l admin -P passwords.txt [IP] ssh  # Bruteforce SSH login
john --wordlist=wordlist.txt hash.txt  # Crack password hashes

# 🔹 Process Management & System Monitoring
ps aux                  # Show running processes
top                     # Show real-time system usage
htop                    # Interactive process viewer
kill [PID]              # Kill a process by ID
pkill [name]            # Kill process by name
history                 # Show command history
df -h                   # Show disk usage
du -sh [dir]            # Show folder size
free -m                 # Show RAM usage

# 🔹 Package Management
apt update              # Update package list
apt upgrade             # Upgrade installed packages
apt install [package]   # Install package
apt remove [package]    # Remove package
dpkg -i [package.deb]   # Install .deb package

# 🔹 Git & Version Control
git clone [repo]        # Clone a GitHub repo
git status              # Show repo status
git add .               # Stage all changes
git commit -m "message" # Commit changes
git push origin main    # Push changes to repo

```


## **How to Use This List**
- 📌 Copy & paste this markdown into your **README.md** file.
- 💻 Use it as a **Kali Linux cheat sheet**.
- 🛠 Modify and update it as per your needs.

🚀 **Happy Hacking with Kali Linux!** 🚀
