---
title: "Test markdown"
order: 8
in_menu: true
---
---
title: Layout Test 1
theme: monolith
layout: base
robots: 
---

# Markdown Cheat Sheet 

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax/) and [extended syntax](https://www.markdownguide.org/extended-syntax/).

## Basic Syntax

Voici un exemple de fichier Markdown qui inclut plusieurs cas d'utilisation de la syntaxe classique :

# Titre niveau 1
## Titre niveau 2
### Titre niveau 3
#### Titre niveau 4

*Italique*

**Gras**

~~Barré~~

`Code en ligne`

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

> Bloc de citation


[Markdown Guide](https://www.markdownguide.org)

![alt text](https://www.markdownguide.org/assets/images/tux.png)

![alt text](https://lahminewski-lab.net/files/Photo/IR/IR-10.jpg)

Liste :

1. First item
2. Second item
2. Third item

Unordered List

- First item
    - un autre item
    - un autre item
        - un autre item
- Second item
- Third item

| Colonne 1 | Colonne 2 |
| --------- | --------- |
| Cellule 1 | Cellule 2 |
| Cellule 1 | Cellule 2 |

Autre taleaux

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

---

## Extended Syntax

[TOC]

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

Here's a sentence with a footnote. [^2]

[^2]: Une autre

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Super & Subscript

H~2~O

X^2^

## Gallery
{{Gallery ./content/img/test2}}


##Test 2 
Test [^a] [^a]: [x] C'est *en* ==cours== de **dev**.
{{Gallery ./themes/monolith/img}} 


### Math 

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

mathML
<math display="block" class="tml-display" style="display:block math;">
  <mrow>
    <msub>
      <mo movablelimits="false">∮</mo>
      <mi>C</mi>
    </msub>
    <mrow>
      <mover>
        <mi>B</mi>
        <mo stretchy="false" style="transform:scale(0.75) translate(10%, 30%);">→</mo>
      </mover>
      <mo>∘</mo>
    </mrow>
    <mrow>
      <mi mathvariant="normal">d</mi>
    </mrow>
    <mover>
      <mi>l</mi>
      <mo stretchy="false" style="transform:scale(0.75) translate(10%, 30%);">→</mo>
    </mover>
    <mo>=</mo>
    <msub>
      <mi>μ</mi>
      <mn>0</mn>
    </msub>
    <mrow>
      <mo fence="true" form="prefix">(</mo>
      <msub>
        <mi>I</mi>
        <mtext>enc</mtext>
      </msub>
      <mo>+</mo>
      <msub>
        <mi>ε</mi>
        <mn>0</mn>
      </msub>
      <mfrac>
        <mrow>
          <mi mathvariant="normal">d</mi>
        </mrow>
        <mrow>
          <mrow>
            <mi mathvariant="normal">d</mi>
          </mrow>
          <mi>t</mi>
        </mrow>
      </mfrac>
      <msub>
        <mo movablelimits="false">∫</mo>
        <mi>S</mi>
      </msub>
      <mrow>
        <mover>
          <mi>E</mi>
          <mo stretchy="false" style="transform:scale(0.75) translate(10%, 30%);">→</mo>
        </mover>
        <mo>∘</mo>
        <mover>
          <mi>n</mi>
          <mo stretchy="false" class="tml-xshift" style="math-style:normal;math-depth:0;">^</mo>
        </mover>
      </mrow>
      <mspace width="0.2778em"></mspace>
      <mrow>
        <mi mathvariant="normal">d</mi>
      </mrow>
      <mi>a</mi>
      <mo fence="true" form="postfix">)</mo>
    </mrow>
  </mrow>
</math>


## Notice Framalibre
  <article class="framalibre-notice">
    <div>
      <img src="https://framalibre.org/images/logo/Scribouilli.png">
    </div>
    <div>
      <h2>Scribouilli</h2>
      <p>Créer votre petit site facilement !</p>
      <div>
        <a href="https://framalibre.org/notices/scribouilli.html">Vers la notice Framalibre</a>
        <a href="https://scribouilli.org/">Vers le site</a>
      </div>
    </div>
  </article>

  <article class="framalibre-notice">
    <div>
      <img src="https://framalibre.org/images/logo/Element.io%20(ex%20Riot.im).png">
    </div>
    <div>
      <h2>Element (ex Riot)</h2>
      <p>Element rassemble toutes vos conversations et intégrations applicatives en une seule application.</p>
      <div>
        <a href="https://framalibre.org/notices/element-ex-riot.html">Vers la notice Framalibre</a>
        <a href="https://element.io">Vers le site</a>
      </div>
    </div>
  </article>

  <article class="framalibre-notice">
    <div>
      <img src="https://framalibre.org/images/logo/BEEP%20app.png">
    </div>
    <div>
      <h2>BEEP app</h2>
      <p>BEEP est une application de gestion et de surveillance de rucher pour les apiculteurs.</p>
      <div>
        <a href="https://framalibre.org/notices/beep-app.html">Vers la notice Framalibre</a>
        <a href="https://beep.nl/beep-app">Vers le site</a>
      </div>
    </div>
  </article>
## Test video

<div style="position: relative; padding-top: 56.25%;"><iframe title="Filtre photo infrarouge fait maison avec une disquette." src="https://peertube.ch/videos/embed/8d19d7b9-f029-4f77-bb17-ff73be0c7f70?title=0&amp;warningTitle=0" allowfullscreen="" sandbox="allow-same-origin allow-scripts allow-popups" style="position: absolute; inset: 0px;" width="100%" height="100%" frameborder="0"></iframe></div>
  
## Test Son
<div id="waveform">
  <!-- the waveform will be rendered here -->
</div>

<script type="module">
import WaveSurfer from 'https://unpkg.com/wavesurfer.js@7/dist/wavesurfer.esm.js'

const wavesurfer = WaveSurfer.create({
  container: '#waveform',
  waveColor: '#68a15e',
  progressColor: '#2a6442',
  mediaControls: true,
  url: 'https://peertube.ch/download/streaming-playlists/hls/videos/7bd5b9f5-de5d-4faa-ab8a-62549b2daa44-0-fragmented.mp4',
  barWidth: 1,
  barGap: 2,
  barRadius: 3,
})

wavesurfer.on('interaction', () => {
  wavesurfer.play()
})
</script>

## Test Son 2
<div id="waveform2">
  <!-- the waveform will be rendered here -->
</div>

<script type="module">
import WaveSurfer from 'https://unpkg.com/wavesurfer.js@7/dist/wavesurfer.esm.js'

const wavesurfer = WaveSurfer.create({
  container: '#waveform2',
  waveColor: '#68a15e',
  progressColor: '#2a6442',
  mediaControls: true,
  url: 'https://peertube.ch/download/streaming-playlists/hls/videos/ffdd9fde-4fe4-4c3d-815f-71a798d1cb93-0-fragmented.mp4',
  barWidth: 2,
  barGap: 1,
  barRadius: 2,
})

wavesurfer.on('interaction', () => {
  wavesurfer.play()
})
</script>

## Mape

<iframe width="100%" height="500" src="https://www.openstreetmap.org/export/embed.html?bbox=25.18002033233643%2C0.49030182377938913%2C25.200276374816898%2C0.5091194864261668&amp;layer=mapnik&amp;marker=0.49971066184068763%2C25.19014835357666" style="border: 1px solid black"></iframe><br/><small><a href="https://www.openstreetmap.org/?mlat=0.4997&amp;mlon=25.1901#map=16/0.4997/25.1901&amp;layers=N">Afficher une carte plus grande</a></small> 