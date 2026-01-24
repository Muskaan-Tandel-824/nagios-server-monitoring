
---

# 📄 6️⃣ installation/step-03-plugins-install.md

```md
## Step 3: Install Nagios Plugins

```bash
cd /tmp
wget https://nagios-plugins.org/download/nagios-plugins-2.3.3.tar.gz
tar -zxvf nagios-plugins-2.3.3.tar.gz
cd nagios-plugins-2.3.3

./configure
make
sudo make install

