# Usage

* Install and configure `pass`.
* Install `markdown`.
* Clone this repo to `~/.mutt.d`.
* Make `~/.muttrc` a symlink pointing to `static/muttrc`.
* Copy the lines from `system/mailcap` to `~/.mailcap`.
* Check `system/mailcap` for other programs to install.
* Check and/or edit `bin/mutt` for expected paths to passwords.
* Edit `static/accounts` to reflect your own account(s).
* Run the wrapper at `bin/mutt`.

# Contents

## static

Static configuration files for mutt.

### static/muttrc

Link this to ~/.muttrc .

## bin

Executable material including scripts to produce configuration lines.

## filters

Filters used for sorting messages by color.  These are also used to mark messages for automatic removal, so that messages ready to be removed are colored appropriately.

## system

Files required or suggested to be installed in the local environment but not part of mutt configuration.
