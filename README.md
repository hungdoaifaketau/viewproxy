Claude AI generated viewer for tiktok videos

=====
Prompt:
```
Write an html page that has the following things and behaviors
* has an input box for an tiktok url with a placeholder text "enter tiktok url"
* has a button that  says "preview tiktok"
* has a button that says "copy url"

When a user enters a tiktok url and presses the preview button the following must happen 
* parse the url and extract the relevant information, that we need to generate an embed code
* generate an embed code similar to the example
* change the current brower url to contain the relevant parts of the embed, so when a user opens the borwser with the new url, it will display the embed code

When the user clicks the "copy url" button
* the button should copy the current browser url into the clipboard

Example embed code : 
<blockquote class="tiktok-embed" cite="https://www.tiktok.com/@nimay.ndolo/video/7411856614183030062" data-video-id="7411856614183030062" style="max-width: 605px;min-width: 325px;" > <section> <a target="_blank" title="@nimay.ndolo" href="https://www.tiktok.com/@nimay.ndolo?refer=embed">@nimay.ndolo</a> <p>Its an epid*mic, but they cant go into lockdown 😬</p> <a target="_blank" title="♬ original sound - NIMAY NDOLO" href="https://www.tiktok.com/music/original-sound-7411856553495644970?refer=embed">♬ original sound - NIMAY NDOLO</a> </section> </blockquote> <script async src="https://www.tiktok.com/embed.js"></script>
```

Prompt 2:

```
There's a slight problem, you need to insert the generated embed into the DOM, and not as text
```

Prompt 3:

```
Ok, so we need couple of more tweaks
* remove the "embed code" box in the html, we don't need it
* we don't need the "embed preview" text as well.
```
