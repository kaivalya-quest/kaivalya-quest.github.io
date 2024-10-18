---
permalink: /meetings/
title: Meetings
---
<div class="responsive-wrap" markdown="0">
  <script>
  navigator.mediaDevices.getUserMedia({ audio: true })
      .then(function(stream) {
        console.log('You let me use your mic!')
      })
      .catch(function(err) {
        console.log('No mic for you!')
      });
  </script>
  <script src='https://meet.jit.si/external_api.js'></script>
  <script>
    const domain = 'meet.jit.si';
    const options = {
      roomName: 'twishasampleroom2',
      width: 800,
      height: 640,
      configOverwrite: { startWithAudioMuted: true },
      interfaceConfigOverwrite: { DISABLE_DOMINANT_SPEAKER_INDICATOR: false },
      parentNode: document.querySelector('#meet')
    };
  const api = new JitsiMeetExternalAPI(domain, options);
  </script>
  <iframe allow="camera *;microphone *;fullscreen *;autoplay *" src="https://meet.jit.si/Kaivalya.QuestLivea975c295ddeab5b1a5323df92f61c4cc9fc88207" width="800" height="640" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
</div>

