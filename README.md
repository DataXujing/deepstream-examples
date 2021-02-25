# Deepstream + Gstreamer Jetson Examples

**Author:**\
Frank Sepulveda\
socieboy@gmail.com

This repository contains examples of gstreamer + deepstream pipelines in python.
Some of the exaples are:

- Display live video on screen using overlaysink
- Display live video on screen using Nvidia EGL plugin
- Display on screen and read inferance config file with nvinfer plugin
- Setup a RTSP Streaming Server
- Setup a RTSP Streaming Server and read inferance
- Publish live video stream to RTMP Server
- Publish live video stream to RTMP Server and read inferance
- Record mp4 video
- Record mp4 video and split on chunks
- Threading and Queues, Streaming and Recording in the same time plus read inferance
- Decode any HTTP Live Source to a Pipeline
- Multi CSI camera as source


Reset Json Clocks
```
sudo nvpmodel -m 0
sudo jetson_clocks
```

Clear Cache
```
rm ${HOME}/.cache/gstreamer-1.0/registry.aarch64.bin
```