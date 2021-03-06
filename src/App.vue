<template>
  <div id="app">
    <audio class="audio"  id="1" src="./assets/SWORD.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('1').currentTime = 0; document.getElementById('1').play();">SWORD</button>
    
    <audio class="audio"  id="2" src="./assets/bell.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('2').currentTime = 0; document.getElementById('2').play();">BELL</button>
    
    <audio class="audio"  id="3" src="./assets/blocked.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('3').currentTime = 0; document.getElementById('3').play();">BLOCKED</button>
    
    <audio class="audio"  id="4" src="./assets/COIN.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('4').currentTime = 0; document.getElementById('4').play();">COIN</button>
    
    <audio class="audio"  id="5" src="./assets/DEFENSE1.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('5').currentTime = 0; document.getElementById('5').play();">DEFENSE CHANT 1</button>
    
    <audio class="audio"  id="6" src="./assets/DEFENSE2.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('6').currentTime = 0; document.getElementById('6').play();">DEFENSE CHANT 2</button>
    
    <audio class="audio"  id="8" src="./assets/EXCELLENT.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('8').currentTime = 0; document.getElementById('8').play();">EXCELLENT</button>
    
    <audio class="audio"  id="9" src="./assets/goingbad.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('9').play();">GOING BAD</button>
    
    <audio class="audio"  id="7" src="./assets/drip.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('7').play();">RIC FLAIR DRIP</button>
    
    <audio class="audio"  id="10" src="./assets/homerun.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('10').currentTime = 0; document.getElementById('10').play();">HOMERUN</button>
    
    <audio class="audio"  id="11" src="./assets/hwg1.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('11').currentTime = 0; document.getElementById('11').play();">HERE WE GO CHANT</button>
    
    <audio class="audio"  id="12" src="./assets/lght1.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('12').currentTime = 0; document.getElementById('12').play();">LETS GO CHANT 1</button>
    
    <audio class="audio"  id="13" src="./assets/lght2.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('13').currentTime = 0; document.getElementById('13').play();">LETS GO CHANT 2</button>
    
    <audio class="audio" id="14" src="./assets/lght3.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('14').currentTime = 0; document.getElementById('14').play();">LETS GO CHANT 3</button>

  <audio class="audio" id="15" src="./assets/sixerschime.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('15').currentTime = 0; document.getElementById('15').play();">CHIME</button>

  <audio class="audio" id="16" src="./assets/sicko.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('16').currentTime = 0; document.getElementById('16').play();">SICKO MODE HIT</button>

  <audio class="audio" id="17" src="./assets/triple.mp3" preload="auto"></audio>
    <button onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('17').currentTime = 0; document.getElementById('17').play();">OH BABY A TRIPLE</button>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app{
  min-height: 100vh;
  background: black;
  display: flex;
  flex-direction: column;
  align-items: center;
}

button{
  width: 70vw;
  height: 60px;
  margin: 30px 15px 30px 15px;
  font-size: 30px;
  font-weight: 700;
  border-radius: 10px;
  border: none;
}

button:focus{
  outline: none;
}
</style>