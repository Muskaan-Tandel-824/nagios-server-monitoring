
---

# 📄 7️⃣ installation/step-04-cpu-monitoring.md

```md
## Step 4: Configure CPU Monitoring

File: /usr/local/nagios/etc/servers/localhost.cfg

```cfg
define service{
    service_description CPU Load
    check_command check_load!5,4,3!10,6,4
}

