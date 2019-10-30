# torrentstreaming.html
<audio id="player">
  <source src="song.mp3" type="audio/mpeg"/>
  <source src="song.ogg" type="audio/ogg"/>
  
</audio>

<button id="play">Play</button>
<button id="pause">Pause</button>
<button id="mute">Mute</button>
(function () {
  var player = document.getElementById('player'),
      play = document.getElementById('play'),
      pause = document.getElementById('pause'),
      mute = document.getElementById('mute');

  play.addEventListener('click', function () {
    player.play();
  });

  pause.addEventListener('click', function () {
    player.pause();
  });

  mute.addEventListener('click', function () {
    player.muted = true;
  });
})();
<form name="upload" enctype="multipart/form-data" method="post" action="upload.php">

        <input type="file" name="arquivo" 100 mb ="arquivo" />
	<label>
	<input name="enviar" type="submit" 100 mb ="Enviar">
	</label>
		
</form>
upload.php
<?php
$diretorio D:\Usuario\Desktop\media 777 = "";

if (!is_dir($diretorio)){ echo "A pasta $diretorio nao existe...";} 
else { echo"A pasta Existe!!!<br>";

$arquivo=$_FILES["arquivo"];
$destino = $diretorio."/".$arquivo['name'];

if (move_uploaded_file($arquivo['tmp_name'],$destino)) {echo "MOVEUUUUUU<br>"; }
{ else } {echo "NAOOOO MOVEU";}

}// fecha o else do primeiro if
?>
<audio controls>
    <source src="i_am_the_doctor.ogg" type="audio/ogg">
    <source src="i_am_the_doctor.mp3" type="audio/mpeg">
    Seu navegador não possui suporte ao elemento audio
</audio>
<video>
    <source src="video/video.mp4" type="video/mp4">

    <track label="Português" kind="subtitles" srclang="pt" src="legenda-portugues.vtt" default>
</video>
let videoAsset = AVURLAsset(url: videoURL)
let audioAsset = AVURLAsset(url: file:///D:/Usuario/Desktop/grachi%201%20temporada/grachi%201%20temporada%20episodio%2050%20traidor.mp3)
let duration = videoAsset.duration
let composition = AVMutableComposition()

let videoTrack = composition.addMutableTrack(withMediaType: AVMediaType.video, preferredTrackID: kCMPersistentTrackID_Invalid)
try? videoTrack?.insertTimeRange(CMTimeRange(start: kCMTimeZero, duration: duration), of: videoAsset.tracks(withMediaType: .video)[0], at: kCMTimeZero)

let audioTrack = composition.addMutableTrack(withMediaType: .audio, preferredTrackID: kCMPersistentTrackID_Invalid)
try? audioTrack?.insertTimeRange(CMTimeRange(start: kCMTimeZero, duration: duration), of: audioAsset.tracks(withMediaType: .audio)[0], at: kCMTimeZero)

let playerItem = AVPlayerItem(asset: composition)
https://github.com/seriesonline/PowderPlayer.git
var torrentStream = require('torrent-stream');
var fs = require('fs');

var engine = torrentStream('magnet:my-magnet-link');

engine.on('ready', function() {
    engine.files.forEach(function(file) {
        console.log('filename:', file.name);
        var stream = file.createReadStream();
        // stream is readable stream to containing the file content
    });
}); inserir link magnetico 
<audio id="player">
  <source src="song.mp3" type="audio/mpeg"/>
  <source src="song.ogg" type="audio/ogg"/>
  Seu navegador não suporta HTML 😞
</audio>

<button id="play">Play</button>
<button id="pause">Pause</button>
<button id="mute">Mute</button>
(function () {
  var player = document.getElementById('player'),
      play = document.getElementById('play'),
      pause = document.getElementById('pause'),
      mute = document.getElementById('mute');

  play.addEventListener('click', function () {
    player.play();
  });

  pause.addEventListener('click', function () {
    player.pause();
  });

  mute.addEventListener('click', function () {
    player.muted = true;
  });
})();
<form name="upload" enctype="multipart/form-data" method="post" action="upload.php">

        <input type="file" name="arquivo" 100 mb ="arquivo" />
	<label>
	<input name="enviar" type="submit" 100 mb ="Enviar">
	</label>
		
</form>
upload.php
<?php
$diretorio D:\Usuario\Desktop\media 777 = "";

if (!is_dir($diretorio)){ echo "A pasta $diretorio nao existe...";} 
else { echo"A pasta Existe!!!<br>";

$arquivo=$_FILES["arquivo"];
$destino = $diretorio."/".$arquivo['name'];

if (move_uploaded_file($arquivo['tmp_name'],$destino)) {echo "MOVEUUUUUU<br>"; }
{ else } {echo "NAOOOO MOVEU";}

}// fecha o else do primeiro if
?>
<audio controls>
    <source src="i_am_the_doctor.ogg" type="audio/ogg">
    <source src="i_am_the_doctor.mp3" type="audio/mpeg">
    Seu navegador não possui suporte ao elemento audio
</audio>
<video>
    <source src="video/video.mp4" type="video/mp4">

    <track label="Português" kind="subtitles" srclang="pt" src="legenda-portugues.vtt" default>
</video>
let videoAsset = AVURLAsset(url: videoURL)
let audioAsset = AVURLAsset(url: file:///D:/Usuario/Desktop/grachi%201%20temporada/grachi%201%20temporada%20episodio%2050%20traidor.mp3)
let duration = videoAsset.duration
let composition = AVMutableComposition()

let videoTrack = composition.addMutableTrack(withMediaType: AVMediaType.video, preferredTrackID: kCMPersistentTrackID_Invalid)
try? videoTrack?.insertTimeRange(CMTimeRange(start: kCMTimeZero, duration: duration), of: videoAsset.tracks(withMediaType: .video)[0], at: kCMTimeZero)

let audioTrack = composition.addMutableTrack(withMediaType: .audio, preferredTrackID: kCMPersistentTrackID_Invalid)
try? audioTrack?.insertTimeRange(CMTimeRange(start: kCMTimeZero, duration: duration), of: audioAsset.tracks(withMediaType: .audio)[0], at: kCMTimeZero)

let playerItem = AVPlayerItem(asset: composition)
https://github.com/seriesonline/PowderPlayer.git
var torrentStream = require('torrent-stream');
var fs = require('fs');

var engine = torrentStream('magnet:my-magnet-link ) 
<audio id="player">
  <source src="song.mp3" type="audio/mpeg"/>
  <source src="song.ogg" type="audio/ogg"/>
  Seu navegador não suporta HTML 😞
</audio>

<button id="play">Play</button>
<button id="pause">Pause</button>
<button id="mute">Mute</button>
(function () {
  var player = document.getElementById('player'),
      play = document.getElementById('play'),
      pause = document.getElementById('pause'),
      mute = document.getElementById('mute');

  play.addEventListener('click', function () {
    player.play();
  });

  pause.addEventListener('click', function () {
    player.pause();
  });

  mute.addEventListener('click', function () {
    player.muted = true;
  });
})();
<form name="upload" enctype="multipart/form-data" method="post" action="upload.php">

        <input type="file" name="arquivo" 100 mb ="arquivo" />
	<label>
	<input name="enviar" type="submit" 100 mb ="Enviar">
	</label>
		
</form>
upload.php
<?php
$diretorio D:\Usuario\Desktop\media 777 = "";

if (!is_dir($diretorio)){ echo "A pasta $diretorio nao existe...";} 
else { echo"A pasta Existe!!!<br>";

$arquivo=$_FILES["arquivo"];
$destino = $diretorio."/".$arquivo['name'];

if (move_uploaded_file($arquivo['tmp_name'],$destino)) {echo "MOVEUUUUUU<br>"; }
{ else } {echo "NAOOOO MOVEU";}

}// fecha o else do primeiro if
?>
<audio controls>
    <source src="i_am_the_doctor.ogg" type="audio/ogg">
    <source src="i_am_the_doctor.mp3" type="audio/mpeg">
    Seu navegador não possui suporte ao elemento audio
</audio>
<video>
    <source src="video/video.mp4" type="video/mp4">

    <track label="Português" kind="subtitles" srclang="pt" src="legenda-portugues.vtt" default>
</video>
let videoAsset = AVURLAsset(url: videoURL)
let audioAsset = AVURLAsset(url: file:///D:/Usuario/Desktop/grachi%201%20temporada/grachi%201%20temporada%20episodio%2050%20traidor.mp3)
let duration = videoAsset.duration
let composition = AVMutableComposition()

let videoTrack = composition.addMutableTrack(withMediaType: AVMediaType.video, preferredTrackID: kCMPersistentTrackID_Invalid)
try? videoTrack?.insertTimeRange(CMTimeRange(start: kCMTimeZero, duration: duration), of: videoAsset.tracks(withMediaType: .video)[0], at: kCMTimeZero)

let audioTrack = composition.addMutableTrack(withMediaType: .audio, preferredTrackID: kCMPersistentTrackID_Invalid)
try? audioTrack?.insertTimeRange(CMTimeRange(start: kCMTimeZero, duration: duration), of: audioAsset.tracks(withMediaType: .audio)[0], at: kCMTimeZero)

let playerItem = AVPlayerItem(asset: composition)
https://github.com/seriesonline/PowderPlayer.git
var torrentStream = require('torrent-stream');
var fs = require('fs');

var engine = torrentStream('magnet:my-magnet-link');

engine.on('ready', function() {
    engine.files.forEach(function(file) {
        console.log('filename:', file.name);
        var stream = file.createReadStream();
        // stream is readable stream to containing the file content
    });
});
