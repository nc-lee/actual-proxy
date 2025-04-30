# Fork Info
There seems to be some regular failure in the actual-api that's causing the actual-proxy to fail and exit. That's causing the magicmirror module to stop updating. I was able to get it going again by manually launching node ./proxy.js in the terminal for my docker container, but that's not sustainable.

This version of the file adds some additional error handling procedures to avoid a failure that exits the proxy process, and instead keeps it running. There are still multiple failures happening, but this allows the program to keep on trying. This does not fix or address any of the errors, error conditions, or failures in the actual-api or in the communciation between actual-proxy and the actual-api.

This was generated with the assitance of Microsoft Copilot AI, and then proofread to the best of my ability. With that said:
- I am a novice to actual-api
- I have never programmed anything for node
- I do have a programming background, and I can pretty much understand what's going on.

License terms remain unchanged.

# All Other documentation here:
[trumpetx/actual-proxy](https://github.com/trumpetx/actual-proxy) for more information.
