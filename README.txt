-Caution-

Do not sync to or from a directory with passwords set.  Copy the files
in and out, and avoid ever copying the identity file in.  Review any
updates to the identity file.  Please don't post a password on github.

-Setup-

Replace "account1", "account2", "account3", with your account names in
identity and colors files.  Change the domain if appropriate.  Set your
password(s) in identity where the word "password" appears.

Edit macros/subtract to target unwanted messages, and edit colors to
match.

  cd
  cp -r path/to/mutt.d/ .mutt.d/
  ln -s .mutt.d/muttrc .muttrc
  cat .mutt.d/mailcap >> .mailcap
  mutt
