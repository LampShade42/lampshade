# lampshade
A Windows enumeration script that displays potential paths of Windows Privilege Escalation


A common issue with enumerating Windows machines is that modern enumeration scripts might be too modern for older versions of Windows. For instance, an enumeration script might require Powershell 3.x but the Windows host may only have 2.x. Shell stability is also a concern, as an advanced enumeration script could cause the session to lock up. Such disasters can cost Penetration Testers precious time, a way into a Windows box, and stress. Lampshade aims to make the job of professional Penetration Testers easier, while at the same time reminding them of an iconic leg lamp. 


The philosophy of lampshade is to:

1. Prioritize compatibility
2. Display results in a clean manner
3. Not use unnecessary commands that might set off alerts
