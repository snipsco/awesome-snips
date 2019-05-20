# Awesome Snips [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [apps](#apps), [customisations](#customisations), [tools](#tools) and [resources](#resources) for the [Snips Voice Platform](https://www.snips.ai/).

### Contents

- [Apps](#apps)
  - [Home Automation](#home-automation)
  - [Entertainment](#entertainment)
- [Tools](#tools)
- [Customisations](#customisations)
- [Resources](#resources)
  - [Community Projects](#community-projects)
  - [Guides](#guides)
  - [Videos](#videos)
  - [Community](#community)
- [Contributing](#contributing)
- [License](#license)

## Apps

### Home Automation

- [snipshue](https://github.com/snipsco/snips-skill-hue-pro) - Control for Philips Hue lights
- [Yeelight](https://github.com/thomas-bouvier/snips-action-yeelight) - Control for Xiaomi Yeelight lights
- [Yeelight](https://github.com/Martin1887/snips-skill-yeelight) - Control for Xiaomi Yeelight ligts (Spanish and English)
- [Mozilla Gateway add-on](https://github.com/andrenatal/voice-addon/) - Integrates Snips with Mozilla's smart home software
- [Home Assistant component](https://home-assistant.io/components/snips/)

### Entertainment

- [snipssonos](https://github.com/snipsco/snips-skill-sonos) - Stream Spotify music on a Sonos system
- [mopidy-mqtt](https://github.com/acolytec3/mopidy-mqtt) - Play music from Spotify, Soundcloud, Google Play and more using Mopidy
- [Bebop](https://github.com/trancept/snips_bebop/) - Voice controlled Parrot Bebop drone
- [Karaoke](https://medium.com/snips-ai/sing-your-heart-out-with-this-voice-controlled-karaoke-app-for-raspberry-pi-f8727e405f02) - Sing your heart out with this voice-controlled Karaoke App for Raspberry Pi!
- [TV Remote](https://medium.com/snips-ai/read-this-if-you-want-to-talk-to-your-tv-280e66333726) - Talk to your TV

### Informational

- [snipsowm](https://github.com/snipsco/snips-skill-owm) - Weather conditions and forecasts using the OpenWeatherMap API
- [snipsfakeweather](https://github.com/snipsco/snips-skill-fakeweather) - We got fake news. Now let's get fake weather forecasts
- [overhead](https://github.com/hcooper/overhead) - What's flying overhead? Retrieve information about nearby aircraft, via flightradar24.com

## Tools

- [snipsmanager](https://github.com/snipsco/snipsmanager) - The Snips Manager
- [satConnect](https://github.com/Psychokiller1888/satConnect) - To easily add satellites to your main unit
- [PySnipsBatch](https://github.com/KiboOst/SNIPS-Tips/tree/master/pySnipsBatch) - Test your training sentences in batch rather than one by one on the console
- [SnipsOrbit](https://github.com/jr-k/snips-orbit) - Track, manage, configure satellites and hub remotely with a nice GUI

## Customisations

- [Home Assistant component](https://home-assistant.io/components/snips/)
- [Enable feedback sounds at boot](https://github.com/uchagani/snips-enable-sounds)
- Alternative text-to-speech:
  - [Amazon Polly TTS](https://github.com/tschmidty69/homeassistant-config/blob/master/snips/jarvis_says.sh) using a bash script.
  - [Amazon Polly TTS](https://github.com/hcooper/snips-tts-polly) as a systemd service, replacing `snips-tts`.
  - [Google WaveNet TTS](https://gist.github.com/Psychokiller1888/7c4783c645d0a580aa595e7823bf3da1) using a shell script for snips.toml
  - [SnipsSuperTTS](https://gist.github.com/Psychokiller1888/cf10af3220b5cd6d9c92c709c6af92c2) One script to rule them all. Enjoy Amazon, Google WaveNet, Mycroft Mimic all in one script! The script provides file caching and fallback to offline TTS in case of connectivity issues!
- [Custom hotwords](https://github.com/Psychokiller1888/snips-custom-hotword)
- [Snips leds control](https://github.com/Psychokiller1888/snipsLedControl) Automatic script with custom animations to control your leds on Snips. Support ReSpeaker, MATRIX Voice, NeoPixels and other!
- [Snips React Satellite](https://github.com/syntithenai/opensnips/tree/master/snips-react-satellite) - a React component providing a microphone that works with Snips

## Resources

### Community Projects
- [Project Alice](https://laurentchervet.wordpress.com/category/project-alice/)
  - [Velux control](https://laurentchervet.wordpress.com/2018/02/11/project-alice-raspberry-voice-controlled-velux/): Raspberry voice controlled Velux ([source code](https://github.com/Psychokiller1888/snipsvelux))
  - [Where is my Phone?](https://laurentchervet.wordpress.com/2018/03/01/alice-wheres-my-phone/): Ask your assistant to find your phone, using [IFTTT](https://ifttt.com)
  - [Language Hotswap](https://laurentchervet.wordpress.com/2018/03/04/project-alice-language-hotswap/): Change the language of your voice assistant just by asking it ([source code](https://github.com/Psychokiller1888/snipslanghotswap))
  - [Multi slots support](https://laurentchervet.wordpress.com/2018/04/01/project-alice-multi-slots-support/): Easy way for Snips to understand more than once the same slot
  - [Arbitrary text support](https://laurentchervet.wordpress.com/2018/03/08/project-alice-arbitrary-text/): Capturing arbitrary text made easy ([source code](https://github.com/Psychokiller1888/SnipsArbitraryTextCapture))
  - [Custom Hotword support](https://laurentchervet.wordpress.com/2018/02/28/project-alice-born-from-the-ashes-of-jarvis/): Another way to change the wake word of Snips ([source code](https://github.com/Psychokiller1888/snips-custom-hotword))
- [Tapsterbot](https://github.com/pylapp/tapsterbot) - Open-source and open-hardware robot for automated mobile app testing

### Guides

- [Microphone Array Benchmark](https://medium.com/snips-ai/benchmarking-microphone-arrays-respeaker-conexant-microsemi-acuedge-matrix-creator-minidsp-950de8876fda) - A guide and thorough benchmark of microphone arrays
- [Spkr](https://medium.com/snips-ai/how-to-build-a-voice-controlled-speaker-that-protects-your-privacy-ec6429a2c673) - Build your own voice-controller speaker which is Private By Design
- [Snips Sonos](https://medium.com/snips-ai/building-a-voice-controlled-home-sound-system-using-snips-and-sonos-2aaf16523ce9) - Building a voice-controlled home sound system using Snips and Sonos
- [Home Assistant](https://medium.com/snips-ai/integrating-snips-with-home-assistant-314723645c77) - Integrating Snips with Home Assistant
- [Sonos Invader](https://github.com/Psychokiller1888/SnipsSonosInvader) - Use your existing sound hardware to have the best Snips audio quality while keeping offline and protecting your privacy
- [SamLess train and download](https://github.com/Psychokiller1888/snipsSamless) - List, train and download your assistants through Python code

### Videos

- [The Snips Voice Platform](https://vimeo.com/221451347)
- [Sonos demo](https://vimeo.com/237742054)
- [Velux demo](https://www.youtube.com/watch?v=ukkOLqcm2CY)
- [Parrot Bebop](https://www.youtube.com/watch?v=GNpz7S0B6Gs)
- [Game of Zork](https://www.youtube.com/watch?v=5RX4Dm9TmCY)
- [Cook with Snips](https://www.youtube.com/watch?v=xH_JE4mj9vI)

### Community

- [Snips Forum](https://forum.snips.ai)
- [Snips Makers](https://makers.snips.ai)
- [Twitter](https://twitter.com/snips)
- [Github](https://github.com/snipsco)

## Contributing

Contribution guidelines can be found [here](/CONTRIBUTING.md).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
