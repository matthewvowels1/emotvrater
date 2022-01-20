# emotvrater
Live motion rating with video. 

Compiled distribution is over GitHub's max file size. Please request for compiled distribution.

EmoTVRater.app is designed using Max/MSP 8 on Mac OSX. It allows for frame-by-frame recording of rated emotion, and visual feedback using online slider ranging from ‘negative emotion’ (left) to ‘positive emotion’ (right) via ‘neutral emotion’ (centre). The rating is taken to be the horizontal position of the cursor. The output is a .csv file of slider position (from 0 = negative emotion, to 1 = positive emotion) at each frame instance. The participant ID is stored as the first row of the .csv file. 

When beginning a new recording, the mouse is positioned centrally. There is a pause/resume spacebar function (but be mindful that mouse movement is not inhibited during pause). The reset button wipes the current text buffer, and resets the frame count to 0. You can then undertake the same starting procedure to begin a new run.


If you have trouble with running:

1. Open Terminal
2. Type ‘sudo spctl --master-disable’ and hit enter
3. Enter your password. This will now have reinstated the ‘open apps from anywhere’ option in your System Preferences security settings (if you want to check, look at the screen before and after this change – first it wasn’t there, and now it is!).
4. Unzip the file.
5. Drag ‘emoTVrater_v2’ from its folder onto your desktop (or anywhere, actually).
6. Drag ‘emoTVrater_v2’ back into the original folder (sounds weird, I know!)
7. Open – a warning might pop up, but click ok. Now – it should work!
