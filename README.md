# trn-ico

A command-line tool to help you assign transparent icon to any specified **file** (not **folder**).

# Installation

Install `trn-ico` by issuing the following command in your teminal:
```
$ git clone https://github.com/chuah48263/trn-ico.git ~/.trn-ico/ && chmod +x ~/.trn-ico/trn-ico && ln -s ~/.trn-ico/trn-ico /usr/local/bin/trn-ico
```

# Usage

`trn-ico <argument>`:
- `/path/to/file`: Assign transparent icon to specified file, one at a time.
- **desktop [-d]**: Assign transparent icon to desktop `.DS_Store` & `.localized`.
- **help [-h]**: `man` page for `trn-ico`.

# Example

```
$ touch ~/test
$ trn-ico ~/test
"~/test"
Assign transparent icon to this file. Confirm [Y/n]? y
Operation completed. Icon of file "~/test" is now transparent.
```

# Reminder

`trn-ico` works only on **files**, not **folders**.
