Cron is powerful utility for job scheduling. you can set automated jobs to run on daily, weekly, monthly or specific time basis.

<img width="263" height="24" alt="image" src="https://github.com/user-attachments/assets/0c4f20a4-c9be-4c33-9f32-f360455a1706" />

'*' represent min hr day month weekday

|Schedule | Description |
|---------|-------------|
| 0 0 * * * | run script at midnight everyday |
| */5 * * * * | run script every 5 minutes |
| 0 6 * * 1-5 | run a script at 6 AM from Mon to Fri |
| 0 0 1-7 * * | run script on first 7 days of every month |
| 0 12 1 * * | run script on the first day of every month at noon |

- crontab -e : to edit the cron
- crontab -l : to view the cron
- crontab -r : to clear the cron 
