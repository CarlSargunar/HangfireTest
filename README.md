# HangfireTest

Messing around to learn how hangfire works, and how I can translate scheduled tasks in to hangfire

## Aims

- Run Hangfire scheduler in a website
	- Database in LocalDB
- Run an Umbraco 8 website and use The Cultiv Hangfire project to connect
	- Umbraco Database in SQL CE, so it can go into source control
- Create standalong workers to connect to that localDB and run tasks 


## Notes

- https://docs.hangfire.io/en/latest/getting-started/aspnet-applications.html
- https://www.youtube.com/watch?v=s42z4uWapRc
- https://www.grantbyrne.com/2021/05/02/getting-started-with-hangfire/
- https://stackoverflow.com/questions/27952142/using-hangfire-connection-string-given-in-startup-cs-throws-cannot-attach-file