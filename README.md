# peerflix

a streaming torrent client.
it requires node.js to run and currently only have a terminal interface.

	npm install -g peerflix

this will install a terminal app called `peerflix`. simply call it with a torrent file

	peerflix http://www.clearbits.net/get/53-star-wreck---in-the-pirkinning.torrent

peerflix will print a terminal interface. this first line contains a address to a http server.

![peerflix](https://raw.github.com/mafintosh/peerflix/master/screenshot.png)

simply open this address in vlc or similar to start viewing the file. If the torrent contains multiple files `peerflix` will choose the biggest one.
