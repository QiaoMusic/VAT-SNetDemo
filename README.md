# <center> Demonstration on Music Source Separation Using Multiresolution Deep Layered Analysis (MRDLA)</center>

<center> Qiaoxiaoman</center> 

**In this demo page, we show music source separation results using our proposed MRDLA [1] and conventional time-domain
audio source separation methods. The mixture and ground truth signals of musical instruments (vocals, bass, drums, and
other) are from the MUSDB18 dataset [2].**

**In addition to the separated audio signals of each method, we provide so-called minus-one audio estimates, which were
computed by subtracting the separated audio signals from the mixture audio signals. The minus-one audio estimates were
helpful for listeners to check the leakage of the target sources.**

<style>
.center 
{
  width: auto;
  display: table;
  margin-left: auto;
  margin-right: auto;
}
</style>


<div class="center">

|                                                                    Miture                                                                     |                                                                     Vocal                                                                     |                                                                 accomponiment                                                                 |
|:---------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------:|
| <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_04/abjones_3_04.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_04/spk1.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_04/spk2.wav"></audio> |
| <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_06/abjones_3_06.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_06/spk1.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_06/spk2.wav"></audio> |
| <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_09/abjones_3_09.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_09/spk1.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_09/spk2.wav"></audio> |
| <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_10/abjones_3_10.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_10/spk1.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_3_10/spk2.wav"></audio> |
| <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_4_01/abjones_4_01.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_4_01/spk1.wav"></audio> | <audio id="audio" controls="" preload="none" style="width: 145px; height: 40px"><source id="mp3" src="./files/abjones_4_01/spk2.wav"></audio> |

</div>

