1.Why use SSH instead of HTTPS for Git?
	- Coz it makes it easier to manage acces, aspecialy with multiple repos and users, and is more secure.

2.Explain the difference between cmd, PowerShell, and Windows Terminal.
	- They are kind of the same thing, but cmd are legcy and barebones while powershell allows you to do basically everything.

3.What are the potential security risks of having too many Admin accounts?
	- Other than making it a pain in the ass for the admin to manage acces settings and make it harder to notice issues, in IT in general you wan't to always maximally minimise acces to all data. Makes it safer, easier to audit and less messy.

4.What’s the difference between NTFS permissions and share permissions?
	- NTFS are local restrictions and share are remote acces

5.Name 3 signs of poor system performance and where you’d investigate them.
	- slow startup
	- long load times
	- freezing/errors
You gotta use the windows tools to search for startup bloat and see what's putting pressure on components. See if there are any errors or crashes in the logs. Check if everything is up to date. And if that fails check the hardware.
 
6.What steps would you take to harden a freshly installed Windows system?
	- Depends whitch Windows. If it's 11 I'd start with installing the lightest version and then throw out the rest of the useless crap. Other than that, add passwords to users, manage their acces as needed and set good password policies. 

7.How would you safely remove remnants of an uninstalled app that left behind services and scheduled tasks?
	- I usually use a dedicated app, it even has a portable version. But some are resistant to it, and then you have to go manual. Find it in the registry and delete all of it through shell and then sweep the disks for any remnants manually.

8.What tool would you use to inspect current CPU, Disk, and RAM load in detail?
	- The resource monitor for detailed, HWMonitor for everyday temp/performance checks.

9.A user says their login fails, and they forgot their password. What do you do?
	- So does it fail or did they forget theyre password? That's unclear. If it's the first, check if the password expired or user got deleted. If second, reset their password on admin acc.

10.What happens if the only admin account is disabled or deleted?
	- If youre lucky there's a hidden admin accoun you can acces through bios, if you're not you can try to break in with some dedicated tools, try to recover some of the data with others or worst case just straight up format the partition/disk with the system and do a clean install

