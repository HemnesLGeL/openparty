Open-Party
==========

This open-source project is a **simple** and **fast** framework for multiplayer chat games, written in clean javascript.
It uses **node.js, socket.io & angular.js** technologies. It is able to create a webserver for that purpose.

Project Status
--------------

Under heavy development! The todo-list is available at `TODO.md`.

Features
--------

- **Realtime** game rooms accross the web
- Multiple rooms & gameplay support
- Highly customizable gameplay definitions to suit your needs
- No registration required for players
- Fully tested by an automatic process
- And more !

For what games ?
----------------

With **Open-Party**, you should be able to play to an infinite number of games!

- Quizzes
- Role-based text games, like "Mafia"
- *Even yours?!*

Basically, it's just a framework, and you'll have to program games that have not been developed yet.
But it's a lot more simple and user-friendly than basic IRC bots, don't be afraid :)

How to install ?
----------------

You'll have to download the source code, and then download additionnal gameplay definitions.
Please note that Open-Party **is not tested under Windows**. We suggest you to install it under Unix distributions.

### Install Open-Party

```
sudo apt-get install nodejs git
git clone https://github.com/Lesterpig/openparty.git
cd openparty
cp config/config_sample.js config.js
npm install
```

### Install example gameplays

```
mkdir data
cd data
git clone https://github.com/Lesterpig/openparty-examples.git
```

### Start the server!

```
cd /path/to/openparty
npm start
```

License - GPL3
--------------

    Copyright (C) 2015 Loïck BONNIOT

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, version 3 of the License.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.