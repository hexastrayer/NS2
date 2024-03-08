### Zero-shot Text to Speech 
This demo page shows the audio from my implement (ns2) and official demo page (ns2_demo) while conducting zero shot speech synthesis. The model is trained on 44k hours MLS dataset and test on Librispeech and VCTK.


### Librispeech

<table>
    <tr>
    	<th> prompt </th>
        <th> ns2 </th>
        <th> ns2_demo </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_1_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_1_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_1_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>
	
    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_2_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_2_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_2_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_3_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_3_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_3_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_4_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_4_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_4_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_5_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_5_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_5_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_6_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_6_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_6_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_7_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_7_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_7_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>    

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_8_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_8_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/librispeech_8_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>
</table>

### VCTK

<table>
    <tr>
    	<th> prompt </th>
        <th> ns2 </th>
        <th> ns2_demo </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_1_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_1_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_1_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>
	
    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_2_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_2_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_2_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_3_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_3_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_3_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_4_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_4_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_4_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_5_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_5_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_5_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_6_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_6_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_6_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_7_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_7_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_7_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>    

    <tr>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_8_ref.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_8_tts.wav" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/demo-compare/vctk_8_demo.wav" type="audio/mpeg"></audio> </th>
    </tr>
</table>