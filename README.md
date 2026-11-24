# Levend haardvuur

Een kersthaard die fullscreen in je browser brandt. Het vuur wordt live met WebGL gerenderd en reageert op je webcam: hoe drukker je beweegt, hoe hoger en wilder de vlammen.

## Gebruik

Open `index.html` in Chrome, Edge of Firefox en geef toestemming voor de webcam. Zonder webcam stuurt je muisbeweging het vuur aan.

| Toets / actie | Wat het doet |
| --- | --- |
| `F` of dubbelklik | Volledig scherm |
| `Z` | Wisselen tussen schermvullend en de hele haard |
| Camerabeeld tonen | Laat zien wat de webcam ziet |

De knoppen en de cursor verdwijnen na een paar seconden vanzelf.

## Hoe het werkt

- De vlammen uit de foto worden met noise omhoog vervormd, de bakstenen erachter blijven stil.
- Daarbovenop komt een procedurele vlammenlaag, met de houtblokken ervoor.
- Vonken, pulserende kooltjes, flakkerende kaarsen en een kamergloed die met het vuur meebeweegt.
- De webcam wordt verkleind tot 64×48 en elk beeld wordt met het vorige vergeleken. Sensorruis wordt automatisch weggefilterd. Het vuur reageert snel op beweging en dooft rustig uit als je stilzit.

Alles zit in één bestand, inclusief de afbeelding. Er zijn geen externe afhankelijkheden.
