#Custom mail deleter for IITG webmail(for firefox only )
This script is for those who are too lazy to delete mails till folder size reaches its limit.
You can run this script using Greasemonkey or simply on web-console.

##To run this on Greasemonkey(Recommended)

  1. Install
  [greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
  2. Create new user script.
  3. In includes field add this [link](https://webmail.iitg.ernet.in/src/right_main.php?PG_SHOWALL=1&use_mailbox_cache=1&startMessage=1&mailbox=INBOX).
  4. Copy paste mailDeleter.js

Now whenever you want to delete mails just open webmail and click on "show all ", that's it.

##To run this on webconsole
  1. Go to the [link](https://webmail.iitg.ernet.in/src/right_main.php?PG_SHOWALL=1&use_mailbox_cache=1&startMessage=1&mailbox=INBOX)
  2. Open web-console (Mouse right click + 'Q')
  3. Copy-Paste mail mailDeleter.js

###Note
	I have already added some webmailIds in list,  You may want to add or remove some of them. Change it accordingly in file mailDeleter.js .
