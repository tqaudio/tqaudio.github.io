---
title: Karaoke271
description: Adjusting the mid-side of the stereo input
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
      <img alt="Snapshot of the Karaoke271" src="https://tqaudio.github.io/img/karaoke271.png" width="320px">
    </div>
    <section class="column">
      <h1>Karaoke271</h1>
      <p>Adjusting the mid-side of the stereo input</p>
      <a class="download-link" href="https://github.com/tqaudio/karaoke271/releases/download/v0.2.0/karaoke271_v0.2.0_mac.zip">
        <p class="download-link-platform">Mac</p>
        <p class="download-link-text">DOWNLOAD</p>
        <p class="download-link-version">v0.2.0</p>
      </a>
      <a class="download-link" href="https://github.com/tqaudio/karaoke271/releases/download/v0.2.0/karaoke271_v0.2.0_win.zip">
        <p class="download-link-platform">Windows</p>
        <p class="download-link-text">DOWNLOAD</p>
        <p class="download-link-version">v0.2.0</p>

      </a>
    </section>
  </div>
</div>

# Description

The Karaoke271 is a plugin for adjusting the mid and side balance of the stereo input. Available for VST3 / AUv2. This plugin is useful for mixing the sound of the stereo synth, reverb effects, etc.

Also, you can change the routing of the channel. For example, it's possible to swap the left and right channels, create mono output (left-left or right-right), and so on.

This plugin has these parameters, and the parameters can be controlled by the automation:

- Mid / Side Balance
- Left signal of the left channel output
- Right signal of the left channel output
- Left signal of the right channel output
- Right signal of the right channel output

Enjoy!

# Download and Install

Click the download link in this page, the zip file will be downloaded.

Next, unzip the downloaded file and check the folder contains the correct plugin for each platforms. The Karaoke271 v0.2.0 is distributed as the following types of the plugin:

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

Let's fork and start developing your plugin today. For more details, see the [README](https://github.com/tqaudio/karaoke271).

# Version

Karaoke271 v0.2.0 (Released 2019-05-01)

# LICENSE

This plugin is licensed under the GPLv3.

--------

- VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.
- Audio Unit is a trademark of Apple Inc.
- AAX is a trademark of Avid Technology.
