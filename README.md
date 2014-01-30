git-jira-commit-message
==========

Simple Script to commit a task by only entering the Jira ID. The script will add automatically the task title to the commit message.


How it works
------------
1. Replace the credentials and the url in the file with your valid credentials.

2. copy the script to your bin folder ( /usr/bin/ ) and make it executable ( chmod +x /usr/bin/git-jira-commit-message )

3. add an alias to your .gitconfig file which is located in your home dir

    [alias]
        c = !sh -c 'git-jira-commit-message "$0"'

Usage
-----
	git c <Jira ID>

	Example:
	git c PR-1201


Contact
-------
* Github: [http://www.github.com/markus-perl](http://www.github.com/markus-perl)
* E-Mail: markus (at) open-mmx.de
