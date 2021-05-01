These are just a few notes on how Etcher works, these will come handy later.

```py
def isElevated():
	if platform == 'win32':
		try:
			system('fltmc');
		catch PermissionError as e:
			return false
		return true
	return process.geteuid() === UNIX_SUPERUSER_USER_ID
```

Catalina is Darwin >= 19.0.0

GitHub is shit. Its search doesn't find some things.
