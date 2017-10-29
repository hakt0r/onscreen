## onscreen - simple on-screen scripts
Put stuff on other screen. Worksforme :)
### Installation
```
sudo sh -c 'for m in shot stream; do
  p=/usr/bin/onscreen-$i;
  wget -O $p https://raw.github.com/hakt0r/onscreen/master/onscreen-$i;
  chmod a+x $p;
  done'
```
### Usage
```
onscreen-shot   [{user@}host]
onscreen-stream [{user@}host]
```

### Set default host
```
echo user@host > ~/.onscreen
```

### Copyrights
  * c) 2013 flyc0r <anx@ulzq.de>
  * c) 2013 anx (Sebastian Glaser) <anx@ulzq.de>

### Licensed under GNU GPLv3

onscreen is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2, or (at your option)
any later version.

onscreen is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this software; see the file COPYING.  If not, write to
the Free Software Foundation, Inc., 59 Temple Place, Suite 330,
Boston, MA 02111-1307 USA

http://www.gnu.org/licenses/gpl.html
