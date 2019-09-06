# vlogger

Records a log of video entries using your webcam.

## Setup

```
git clone https://github.com/binarymason/vlogger.git ~/.vlogger
cd ~/.vlogger
bash script/install
```


## Usage:

```
vlog <emotion> [emotion]
```

Example:

```
vlog happy grateful excited
```

ffmpeg will start recording you.  When you are finished recording, press "q" and your video will be played back to you.  Press "q" again to quit the playback. All of your videos will be saved in ~/vlog directory.
