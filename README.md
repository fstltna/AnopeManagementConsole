# Anope Management Console (1.0.0)
Allows you to manage your Anope server with a text based UI - 
Official support sites: [Official Github Repo](https://github.com/fstltna/AnopeManagementConsole)

---

Edit "amc" and change the settings at the top if your Anope services are not in /home/ircdaemon/services.

You also need to have my Anope Startup Script installed.

I suggest you then add this to your /home/ircdaemon/.bashrc file:
	export PATH=/home/ircdaemon/bin:/home/ircdaemon/AnopeManagementConsole:$PATH
You will need to install the required perl modules (as root):

- sudo /home/ircdaemon/AnopeManagementConsole/installdeps


After that you should log out and back in and now "amc" should work.
