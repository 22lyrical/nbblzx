---
title: 音乐
date: 2026-08-17 23:00:00
type: music
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.css">
<script src="https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.js"></script>
<div id="player"></div>
<script>
var ap = new APlayer({
  container: document.getElementById('player'),
  fixed: false,
  mini: false,
  autoplay: false,
  audio: [{
    name: '歌名',
    artist: '歌手',
    url: 'https://music.163.com/song/media/outer/url?id=1992712131.mp3',
    cover: ''
  }]
});
</script>