# How to change call speakerphone? (Firefox | Safari)

Firefox and Safari still don't implement [HTMLMediaElement.setSinkId()](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/setSinkId) method and due to that web sites can't change the OS defined audio output device programmatically.

That is why if you want to use Firefox or Safari with specific headphones or speakers you need to set them to be default in OS before (re)loading the Meet page.

Luckily doing that is quite a trivial task in both Windows on macOS

## How to change audio output device on Windows?

![alt text](https://meet-cdn.azureedge.net/assets/help/en/help-windows-speaker.png?v=1 "Changing audio output device on Windows")

## How to change audio output device on macOS?

![alt text](https://meet-cdn.azureedge.net/assets/help/en/help-mac-speaker.png?v=1 "Changing audio output device on Mac")