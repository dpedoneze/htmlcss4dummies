##  HTML - tags interativas


```html
<img src="resources/starters.png" alt="PKM Starters">

<audio controls="controls" volume="0.5" loop="true">
  Mensagem avisando usuário que elemento audio não é suportado
  <source src="pkm_sound.ogg" type="audio/ogg">
  <track kind="captions" src="lyrics.en.vtt" srclang="en" label="EN">
  <track kind="captions" src="lyrics.pt.vtt" srclang="en" label="PT-BR">
</audio>

<video width="400" controls poster="resources/poster.gif" >
  <!-- sources mp4, ogg, webm ...-->
</video>

```

<div class="row">
  <div class="col-6">
    <img src="resources/starters.png" alt="PKM Starters" width="450">
  </div>
  <div class="col-6">
    <video width="400" controls poster="https://archive.org/download/WebmVp8Vorbis/webmvp8.gif" >
      <source src="https://archive.org/download/WebmVp8Vorbis/webmvp8_512kb.mp4" type="video/mp4">
      <source src="https://archive.org/download/WebmVp8Vorbis/webmvp8.ogv" type="video/ogg">
      <source src="https://archive.org/download/WebmVp8Vorbis/webmvp8.webm" type="video/webm">
      Your browser doesn't support HTML5 video tag.
    </video>
  </div>
</div>

<div class="row">
  <audio controls="controls" volume="0.5" loop="true">
    Mensagem avisando usuário que elemento audio não é suportado
    <source src="resources/pkm_sound.ogg" type="audio/ogg">
  </audio>
</div>

