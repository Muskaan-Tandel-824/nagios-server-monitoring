
---

# 📄 5️⃣ installation/step-02-nagios-core-install.md

```md
## Step 2: Install Nagios Core from Source

```bash
cd /tmp
wget https://assets.nagios.com/downloads/nagioscore/releases/nagios-4.4.14.tar.gz
tar -zxvf nagios-4.4.14.tar.gz
cd nagios-4.4.14

./configure --with-command-group=nagcmd
make all
sudo make install
sudo make install-init
sudo make install-commandmode
sudo make install-config
sudo make install-webconf

