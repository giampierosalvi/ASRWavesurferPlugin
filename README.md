ASRWavesurferPlugin
===================

Automatic Speech Recognition Plugin for Wavesurfer

## Reference
**The WaveSurfer Automatic Speech Recognition Plugin**  
*Giampiero Salvi and Niklas Vanhainen*  
Proceedings of the Ninth International Conference on Language Resources and Evaluation (LREC'14), May 2014, Reykjavik, Iceland.

## Additional Resources

You can find the acoustic and language models required for the plugin to work at this address:

http://www.speech.kth.se/asr/

## Installation

### Preliminaries (all platforms):
* Install WaveSurfer from http://wavesurfer.sourceforge.net/
* Run WaveSurfer once and then close the program (this creates the preference directory)

### Installation Linux/Mac OS X:
* unpack `v1.0.2.tar.gz` into `~/.wavesurfer/1.8/plugins/` with:
```
tar xvfz v1.0.2.tar.gz -C ~/.wavesurfer/1.8/plugins/
```
* unpack at least one of the language packs (from http://www.speech.kth.se/asr/) into `~/.wavesurfer/1.8/plugins/asr/` with:
```
tar xvfz wavesurfer_asr_plugin_Swedish_models_0.1.tgz -C ~/.wavesurfer/1.8/plugins/asr/
tar xvfz wavesurfer_asr_plugin_English_models_0.1.tgz -C ~/.wavesurfer/1.8/plugins/asr/
```

### Installation MS Windows:
* unpack `v1.0.2.tar.gz` into `${HOME}\.wavesurfer\1.8\plugins\`
* unpack at least one of the language packs into `${HOME}\.wavesurfer\1.8\plugins\asr\`
