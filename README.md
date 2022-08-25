#ArchiveDL

A tool for interacting with the Internet Archive.

## Why
I needed a tool for logging in and downloading files on remote machines. This is ultimately a wget wrapper.

## How
```
archivedl [ command ]
	archivedl is a tool for logging into the internet archive and downloading files
	as the logged in user. Uses wget to communicate.

	commands:
		    help: Display this help message
		   login: Perform a login and save cookies
		  plogin: Prompt for user/pass if not stored and then login.
		   store: Prompt for and store login information (password will not be secured).
		          Exit after entering username to only store username.
		download: Pass everything after this to wget directly. For more options see: man wget
		          Recommended options are [--continue] [--tries=0] [URL]
```
