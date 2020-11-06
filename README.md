# Play mp3 file with playback control

Example from the esp-adf framework [https://github.com/espressif/esp-adf/tree/master/examples/get-started/play_mp3_control] extended to the Ai Thinker Board Audio-Kit V2.2

## Usage

Prepare the audio board:

- Connect speakers or headphones to the board. 

Configure the example:

- Select compatible audio board in `menuconfig` > `Audio HAL` > `ESP32-AiThinker-audio V2.2`.

Load and run the example. Use buttons to control how audio is played:

- Use Key4 [Play] to start, pause/resume or restart playback.
- Adjust sound volume with Key5 [Vol+] or Key6 [Vol-].
- To stop the pipeline press Key3 [Set].
