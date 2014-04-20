trash (based on [rm](https://github.com/artmees/rm))
==

Since you've reached this page, I assume you did the same bad thing I did before. After using `rm very_important_file` and later realize that you can't retrieve that file.

This is custom script used to avoid deleting files permanently and instead files will be moved to /Users/user_name/.Trash folder

-----

Install
-
`sudo cp trash.sh /usr/local/bin/trash`

you might need to restart the terminal or run `source ~/.bashrc` or `source ~/.bash_profile`

Uninstall
-
`sudo rm /usr/local/bin/trash`

you might need to restart the terminal or run `source ~/.bashrc` or `source ~/.bash_profile`

**please make sure that local/bin PATH before /bin PATH**

add `export PATH="/usr/local/bin:$PATH"` to `.bash_profile` or `.bashrc` to achive this

Usage
-
`trash [OPTION]...FILE...`

###Options
| option      |  desc. |
|-------------|--------|
| `-h,--help` | display this help text and exit. |
| `--version` | output version information and exit. |
| `-r, -R, --recursive` | **move** the directories and their content to the Trash folder. |

Bugs
-
Please report found bugs to <https://github.com/artmees/rm/issues>


COPYRIGHT
---------
Copyright (C) 2013, Ahmed Abdel Razzak. All rights reserved.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the
Free Software Foundation; version 2 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 59
Temple Place, Suite 330, Boston, MA 02111-1307 USA or see http://www.gnu.org/licenses/.
