# wplinux 

**Version: 1.3.4, 2023-10-04**

## Project Description:
Provides information about Unix and Linux commands from German Wikipedia articles in the bash shell. This script reads and parses Wikipedia pages and tries to display the beginning of the articles concerning those commands in text mode right in the terminal.

## Requirements

The script requires the following dependencies to be installed:

### External Programs Used

| Program Name   | &nbsp;&nbsp;&nbsp;Task / Program Catgegory           | &nbsp;&nbsp;&nbsp;Installed by default|
|:---------------|:-----------------------------------------------------|:--------------------------------------|
| wikipedia2text | &nbsp;&nbsp;&nbsp;Converts Wikipedia articles to text| &nbsp;&nbsp;&nbsp;no                  |
| links2         | &nbsp;&nbsp;&nbsp;Shows Webpages in the Terminal     | &nbsp;&nbsp;&nbsp;no                  |
| lynx           | &nbsp;&nbsp;&nbsp;Shows Webpages in the Terminal     | &nbsp;&nbsp;&nbsp;no                  |
| elinks         | &nbsp;&nbsp;&nbsp;Shows Webpages in the Terminal     | &nbsp;&nbsp;&nbsp;no                  |
| sed            | &nbsp;&nbsp;&nbsp;Deletes or replaces text           | &nbsp;&nbsp;&nbsp;yes                 |
| less           | &nbsp;&nbsp;&nbsp;Pager for viewing text files       | &nbsp;&nbsp;&nbsp;yes                 |
| wget           | &nbsp;&nbsp;&nbsp;Downloads files from Servers       | &nbsp;&nbsp;&nbsp;yes                 |
| grep           | &nbsp;&nbsp;&nbsp;Filters lines based on patterns    | &nbsp;&nbsp;&nbsp;yes                 |

Only one of the web browsers 'links2', 'lynx' or 'elinks' needs to be installed.

## Installation

To install this program, copy the file `wplinux` to a directory of your choice and make the script file executable with the following command:

```bash
chmod +x wplinux
```

If you want to be able to invoke the script from any directory, it needs to be stored in a directory that is part of the search path. You can display the search path using the command `echo "$PATH"` and extend it if necessary or desired by editing the file `~/.bashrc` or the file `/etc/bash.bashrc`. The file `~/.bashrc` defines the search path for a user; `/etc/bash.bashrc` defines it system-wide for all users.

## Usage

Open a terminal and execute one of the following commands.

### If the script is in the search path:

```bash
wplinux
```

### If the script is in the current directory but not in the search path:

```bash
./wplinux
```

## Author

Bernd Storck: I am a certified webmaster/web developer and Linux aficionado from Berlin. I had my first programming experiences around 1984 with an ATARI 800XL. Since this time I've tried or learned a bunch of programming languages. Especially I'm certified as JavaScript developer, PHP Programmer and WebDeveloper. I have extensive experience in Bash Programming.

Contact: [Facebook: Linux-Infos von Bernd Storck](https://www.facebook.com/BStLinux/), [www.facebook.com/BStLinux](https://www.facebook.com/BStLinux/)

&nbsp;

---

## License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but **without any warranty**; without even the implied warranty of merchantability or fitness for a particular purpose. See the GNU General Public License for more details.

You will find the GNU General Public License at <http://www.gnu.org/licenses/>.
