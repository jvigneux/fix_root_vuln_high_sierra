# fix_root_vuln_high_sierra
A quick fix to patch the passwordless root vuln in Mac Os X High Sierra by disabling the root user with a binary. 
Source shell script provided.

It will disable the root user in the /etc/passwd file + in the Directory Service of Mac Os X

You can provide this binary to your users to quickly fix the vulnerability that allows anyone to login, (remotly via Screen Sharing if enabled) as the root user without a password.

Source of the vuln:
https://www.wired.com/story/macos-high-sierra-hack-root/

* runme.app : The compiled shell script
* disable_root.sh : The shell script

*** Update ***

Apple released a fix today:
https://support.apple.com/en-ca/HT208315
(Use it instead of this)
***************
