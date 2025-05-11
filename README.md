# diarization-benchmarking

Different tests on frameworks for English speech recognition and diarization (identifying who is speaking) based on 1 video

Test was made on this video from the BBC "Pope Leo XIV celebrates first Mass as new head of Catholic Church | BBC News"
https://www.youtube.com/watch?v=dEv3fkRIsNI
Duration : 7min54s

Audio file also included "[dEv3fkRIsNI]".mpe

## Test 1 - Youtube to transcript 
https://youtubetotranscript.com/

Ok and fast results, but no diarization, and results very similar to the native Youtube approximative subtitles

## Test 2 - Whisper Plus
https://github.com/kadirnar/whisper-plus

Leveraging Whisper, but does not give better results than 1
No Diarization without a complex setup
Time to transcript = < 3 min 

## Test 3 - Insanely Fast Whisper 
https://github.com/Vaibhavs10/insanely-fast-whisper

Results were fast but again, no diarization
Need to add a pre-trained model for diarization
Time to transcript = < 1 min 

## Test 4 - Whisper Diarization
https://github.com/MahmoudAshraf97/whisper-diarization

Great results, with diarization with both a .txt file and a .srt file
Time to transcript = 42 min, quite high