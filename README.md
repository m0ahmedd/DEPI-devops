This repo to exercise on pushing it to 3 remote repos usin one command:
- By adding 3 remote repos using:
	$ git remote add all-repos url1
	$ git remote set-url --add all-repos url2
	$ git remote set-url --add all-repos url3
- Then, pushing your local repos to all-repos:
	$ git push --force all-repos main
