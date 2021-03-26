<template>
  <div id="app">
    <button class="stop" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause();">STOP</button>

    OFFENSE

  <audio class="audio" id="16" src="./assets/sicko.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('16').currentTime = 0; document.getElementById('16').play();">Sicko Mode</button>

  <audio class="audio" id="17" src="./assets/triple1.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('17').currentTime = 0; document.getElementById('17').play();">Oh Baby A Triple</button>

    <audio class="audio"  id="42" src="./assets/Yeah.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('42').currentTime = 0; document.getElementById('42').play();">Lil Jon Yeah</button>

    <audio class="audio"  id="44" src="./assets/yeahbuddy.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('44').currentTime = 0; document.getElementById('44').play();">Yeah Buddy</button>

    <audio class="audio"  id="45" src="./assets/woo.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('45').currentTime = 0; document.getElementById('45').play();">Ric Flair Woo</button>

    <audio class="audio"  id="41" src="./assets/dynamite.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('41').currentTime = 0; document.getElementById('41').play();">Boom Goes the Dynamite</button>
    
    <audio class="audio"  id="4" src="./assets/COIN.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('4').currentTime = 0; document.getElementById('4').play();">Coin</button>

    <audio class="audio"  id="43" src="./assets/CASH.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('43').currentTime = 0; document.getElementById('43').play();">Cash</button>
    
    <audio class="audio"  id="10" src="./assets/homerun.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('10').currentTime = 0; document.getElementById('10').play();">Smash Sound</button>

  <audio class="audio" id="15" src="./assets/sixerschime.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('15').currentTime = 0; document.getElementById('15').play();">Freethrow Chime</button>

  <audio class="audio" id="21" src="./assets/powerup.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('21').currentTime = 0; document.getElementById('21').play();">Power Up</button>

    <audio class="audio"  id="1" src="./assets/SWORD.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('1').currentTime = 0; document.getElementById('1').play();">Sword</button>
    
    <audio class="audio"  id="2" src="./assets/bell.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('2').currentTime = 0; document.getElementById('2').play();">Bell</button>
    
    <audio class="audio"  id="8" src="./assets/EXCELLENT.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('8').currentTime = 0; document.getElementById('8').play();">Excellent</button>

  <audio class="audio" id="22" src="./assets/shmashfinal.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('22').currentTime = 0; document.getElementById('22').play();">Game Winner</button>

  
 
        
    <audio class="audio"  id="11" src="./assets/hwg11.mp3" preload="auto"></audio>
    <button class="chant" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('11').currentTime = 0; document.getElementById('11').play();">HERE WE GO CHANT</button>
    
    <audio class="audio"  id="12" src="./assets/lght11.mp3" preload="auto"></audio>
    <button class="chant" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('12').currentTime = 0; document.getElementById('12').play();">LETS GO CHANT 1</button>
    
    <audio class="audio"  id="13" src="./assets/lght21.mp3" preload="auto"></audio>
    <button class="chant" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('13').currentTime = 0; document.getElementById('13').play();">LETS GO CHANT 2</button>
    
    <audio class="audio" id="14" src="./assets/lght31.mp3" preload="auto"></audio>
    <button class="chant" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('14').currentTime = 0; document.getElementById('14').play();">LETS GO CHANT 3</button>

  DEFENSE

  <audio class="audio" id="20" src="./assets/wrong.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('20').currentTime = 0; document.getElementById('20').play();">The Price is Wrong</button>
    
    <audio class="audio"  id="3" src="./assets/blocked.mp3" preload="auto"></audio>
    <button class="sfx" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('3').currentTime = 0; document.getElementById('3').play();">Blocked</button>
  
  <audio class="audio"  id="5" src="./assets/DEFENSE11.mp3" preload="auto"></audio>
    <button class="chant" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('5').currentTime = 0; document.getElementById('5').play();">DEFENSE CHANT 1</button>
    
    <audio class="audio"  id="6" src="./assets/DEFENSE21.mp3" preload="auto"></audio>
    <button class="chant" onclick=" var sounds = document.getElementsByTagName('audio');
  for(i=0; i<sounds.length; i++) sounds[i].pause(); document.getElementById('6').currentTime = 0; document.getElementById('6').play();">DEFENSE CHANT 2</button>


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
  color: white;
  font-size: 50px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

button{
  width: 100vw;
  height: 50px;
  margin: 2px 0px 2px 0px;
  font-size: 30px;
  font-weight: 400;
  border: none;
}

button:focus{
  outline: none;
}

.song{
  background: rgb(124, 0, 0);
  color:white;
}

.sfx{
  background: rgb(0, 121, 20);
  color:white;
}

.chant{
  background: rgb(0, 67, 121);
  color:white;
}

.stop{
  background: rgb(172, 0, 0);
  color:white;
}
</style>