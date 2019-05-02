---
title: Reverse300
description: Reverse playback plugin
layout: default
---
<style>
.download-link {
  display: inline-block;
  width: 128px;
  color: #FFF;
  background-color: #928C36;
  border-radius: 4px;
}
.download-link-platform {
  font-size: 20px;
  font-weight: bold;
  text-align: center;
  margin: 0;
  padding-top: 24px;
}
.download-link-text {
  font-size: 11px;
  text-align: center;
  margin: 0;
  padding-top: 16px;
}

.download-link-version {
  font-size: 10px;
  font-weight: bold;
  opacity: 0.75;
  text-align: center;
  margin: 0;
  padding-top: 4px;
  padding-bottom: 8px;
}

.columns {
  display: flex;
}
.column {
  flex: 1;
}
@media only screen and (max-width: 768px) {
  .columns {
    display: block;
  }
  .column {
    display: block;
  margin-right: 0;
  }
}
</style>
<div id="download-area">
  <div class="columns">
    <div class="column">
      <img alt="Snapshot of the Reverse300" src="https://tqaudio.github.io/img/reverse300.png" width="320px">
    </div>
    <section class="column">
      <h1>Reverse300</h1>
      <p>Reverse playback plugin</p>
      <a class="download-link" href="https://github.com/tqaudio/reverse300/releases/download/v0.2.0/reverse300_v0.2.0_mac.zip">
        <p class="download-link-platform">Mac</p>
        <p class="download-link-text">DOWNLOAD</p>
        <p class="download-link-version">v0.2.0</p>
      </a>
      <a class="download-link" href="https://github.com/tqaudio/reverse300/releases/download/v0.2.0/reverse300_v0.2.0_win.zip">
        <p class="download-link-platform">Windows</p>
        <p class="download-link-text">DOWNLOAD</p>
        <p class="download-link-version">v0.2.0</p>

      </a>
    </section>
  </div>
</div>

# Description

The Reverse300 is a reverse playback plugin. Available for VST3 / AUv2. This plugin is controlled by MIDI note on and note off, so that you can use this plugin like the instrument.

For example, press and hold down any key on your MIDI keyboard, the recording will start. After 1 sec past, release the pressed key, recorded 1 sec of the reversed playbak will start.

Note: This plugin should be loaded as the send effect. You need create a track for this plugin, and send the signal to that track.

This plugin has these parameters, and the parameters can be controlled by the automation:

- Wet and dry
- MIDI note and channel number

Enjoy!

# Download and Install

Click the download link in this page, the zip file will be downloaded.

Next, unzip the downloaded file and check the folder contains the correct plugin for each platforms. The Reverse300 v0.2.0 is distributed as the following types of the plugin:

- Mac
  - (AUv2) `.component`
  - (VST3) `.vst3`
- Windows
  - (VST3) `.vst3`

Copy the plugin to the location where is read by the hosts. The common locations are:

- Mac
  - `/Library/Audio/Plug-ins/Components`
  - `/Library/Audio/Plug-ins/VST3`
- Windows
  - `C:\Program Files\Common Files\VST3`

Finally, launch the host application and check the plugin can be loaded.

Note: The AAX support is added future version.

# Compatibility

This plugin supports only 64 bit host applications.

# Develop

Let's fork and start developing your plugin today. For more details, see the [README](https://github.com/tqaudio/reverse300).

# Version

Reverse300 v0.2.0 (Released 2019-05-01)

# LICENSE

This plugin is licensed under the GPLv3.

--------

- VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.
- Audio Unit is a trademark of Apple Inc.
- AAX is a trademark of Avid Technology.
