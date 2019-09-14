# vlogger

Records a log of video entries using your webcam.

## Setup

```
git clone https://github.com/binarymason/vlogger.git ~/.vlogger
cd ~/.vlogger
bash script/install
```


## Usage:

Just type `vlog` and ffmpeg will start recording you.  When you are finished recording, press "q" and your video will be played back to you.  Press "q" again to quit the playback. All of your videos will be saved in ~/vlog directory.

## Transcript

Transcripts are automatically generating using Mozilla's `deepspeech` pretrained English model. A markdown file of your video's transcript is created at the end of each recording. The transcription is admittedly not perfect with roughly 70-80% accuracy, but at least it makes your videos more searchable for reference in the future.

## Search

You can achieve a poor-man's search through your vlog entries like this:

```
vlog --search <your-search-term>
```

## Reviewing entries

```
vlog -l
```
