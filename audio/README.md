# Audio

`let-me-go.mp3` is the user-supplied 大肥鱼《Let Me Go》original (124.464s, 48kHz stereo). Rebuild using `npm run prepare:audio`; dev/build run that step automatically. Binary source parts and checksum are under `assets/audio`. No re-encoding is applied. This track is not licensed as part of the game's code.

Music loops after the first pointer or keyboard gesture. Independent music/SFX volume and mute controls appear in home settings and pause. Web Audio gain supports mobile volume control; media playback is the fallback. Settings persist locally. Background tabs pause audio. The generic V2 AudioPort remains a placeholder; this is the browser preview host integration.
