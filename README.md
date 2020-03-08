# Monitor-Diskspace
Shell script to monitor linux disk space
It will send an email to $ADMIN, if the (free available) percentage of space is >= 90%.
Also you can exclude list partitions of unwanted monitoring.

# Make Cron job
chmod +x disk.sh

Write cronjob as per your requirement

10 0 * * * bash disk.sh
