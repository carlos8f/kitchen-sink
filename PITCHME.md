#HSLIDE

## The Kitchen Sink
##### <span style="font-family:Helvetica Neue; font-weight:bold">A <span style="color:#e49436">Git</span>Pitch Feature Tour</span>

#HSLIDE
## Slideshow Theme Switcher
<span style="font-size:0.6em; color:gray">Available bottom-left of screen.</span> |
<span style="font-size:0.6em; color:gray">Start switching themes right now!</span>

#HSLIDE

## Tip!
For best viewing experience press **F** key to go fullscreen.

#HSLIDE

## Markdown Slides
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slide-Markdown" target="_blank">GitPitch Wiki</a> for details.</span>


#VSLIDE

#### Use GitHub Flavored Markdown
#### For Slide Content Creation

<br>

The same tool you use to create project **READMEs** and **Wikis** for your GitHub repos.

#HSLIDE

## Code Slides
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Code-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Use Markdown Code Blocks

<br>

And enjoy code syntax highlighting powered by <a target="_blank" href="highlight.js](https://highlightjs.org">highlight.js</a>.

#VSLIDE

```JavaScript
// JavaScript Code Block

$('button').click(function(){
    $('h1, h2, p').addClass('blue')
    $('div').removeClass('important')
    $('h3').toggleClass('error')
    $('#foo').attr('alt', 'Lorem Ipsum')
});
```

#VSLIDE

```Scala
// Scala Code Block

HashMap params = HashMap(n -> 10, mean -> 5)

// Define executable for R stats#rnorm function call.
OCPUTask task = OCPU.R()
                    .pkg("stats")
                    .function("rnorm")
                    .input(params.asJava)
                    .library()
```

#VSLIDE

```Go
// Go Code Block

package main

import "fmt"

func swap(x, y string) (string, string) {
    return y, x
}

func main() {
    a, b := swap("hello", "world")
    fmt.Println(a, b)
}
```

#HSLIDE

## GIST Slides
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/GIST-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### GitHub GIST
#### Building Blocks For Any Presentation

<br>

Enjoy 100% reusable code snippets, excellent syntax highlighting, code indentation and styling. 

#VSLIDE?gist=8da53731fd54bab9d5c6

#VSLIDE?gist=28ee3d19ddef9d51b15adbdfe9ed48da

#HSLIDE

## Image Slides
## [ Inline ]
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Image-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Make A Visual Statement

<br>

Use inline images to lend a *visual punch* to your slideshow presentations.


#VSLIDE

<span style="color:gray; font-size:0.7em">Inline Image at <b>Absolute URL</b></span>

![Image-Absolute](https://res.cloudinary.com/gitpitch/raw/upload/kitchen-sink/octocat-privateinvestocat.jpg)

<span style="color:gray; font-size: 0.5em;">the <b>Private Investocat</b> by <a href="https://github.com/jeejkang" target="_blank">jeejkang</a></span>


#VSLIDE

<span style="color:gray; font-size:0.7em">Inline Image at GitHub Repo <b>Relative URL</b></span>

![Image-Absolute](assets/octocat-de-los-muertos.jpg)

<span style="color:gray; font-size:0.5em">the <b>Octocat-De-Los-Muertos</b> by <a href="https://github.com/cameronmcefee" target="_blank">cameronmcefee</a></span>


#VSLIDE

<span style="color:gray; font-size:0.7em"><b>Animated GIFs</b> Work Too!</span>

![Image-Relative](https://res.cloudinary.com/gitpitch/raw/upload/kitchen-sink/octocat-daftpunkocat.gif)

<span style="color:gray; font-size:0.5em">the <b>Daftpunktocat-Guy</b> by <a href="https://github.com/jeejkang" target="_blank">jeejkang</a></span>

#HSLIDE

## Image Slides
## [ Background ]
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Make A Bold Visual Statement

<br>

Use high-resolution background images for maximum impact.

#VSLIDE?image=https://res.cloudinary.com/gitpitch/raw/upload/kitchen-sink/victory.jpg

#VSLIDE?image=https://res.cloudinary.com/gitpitch/raw/upload/kitchen-sink/127.jpg


#HSLIDE

## Video Slides
## [ Inline ]
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Video-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Bring Your Presentations Alive

<br>

Embed *YouTube*, *Vimeo*, *MP4* and *WebM* inline on any slide.

#VSLIDE

![YouTube Video](https://www.youtube.com/embed/mkiDkkdGGAQ)

#VSLIDE

![Vimeo Video](https://player.vimeo.com/video/111525512)

#VSLIDE

![MP4 Video](http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4)


#HSLIDE

## Video Slides
## [ Background ]
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Video-Slides#background" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Maximize The Viewer Experience

<br>

Go fullscreen with *MP4* and *WebM* videos.

#VSLIDE?video=http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4

#HSLIDE

## Math Notation Slides
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Math-Notation-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE


#### Beautiful Math Rendered Beautifully

<br>

Use *TeX*, *LaTeX* and *MathML* markup powered by <a target="_blank" href="https://www.mathjax.org/">MathJax</a>.

#VSLIDE

`$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$`

#VSLIDE

`$$\begin{array}{c|lcr} n & \text{Left} & \text{Center} & \text{Right} \\ \hline 1 & 0.24 & 1 & 125 \\ 2 & -1 & 189 & -8 \\ 3 & -20 & 2000 & 1+10i \end{array}$$`

#VSLIDE

`\begin{align}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{align}`

#VSLIDE

##### The Cauchy-Schwarz Inequality

`\[
\left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
 \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\]`

#VSLIDE

##### A Cross Product Formula

`\[
  \mathbf{V}_1 \times \mathbf{V}_2 =
   \begin{vmatrix}
    \mathbf{i} & \mathbf{j} & \mathbf{k} \\
    \frac{\partial X}{\partial u} & \frac{\partial Y}{\partial u} & 0 \\
    \frac{\partial X}{\partial v} & \frac{\partial Y}{\partial v} & 0 \\
   \end{vmatrix}
\]`

#VSLIDE

##### The probability of getting \(k\) heads when flipping \(n\) coins is:

`\[P(E) = {n \choose k} p^k (1-p)^{ n-k} \]`

#VSLIDE

##### In-line Mathematics

This expression `\(\sqrt{3x-1}+(1+x)^2\)` is an example of an inline equation.  As
you see, MathJax equations can be used without unduly disturbing the spacing between lines.

#HSLIDE

## Slide Fragments
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Fragment-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Reveal Slide Concepts Piecemeal

<br>

Step through slide content in sequence to slowly reveal the bigger picture.

#VSLIDE

- Java
- Groovy     <!-- .element: class="fragment" -->
- Kotlin     <!-- .element: class="fragment" -->
- Scala     <!-- .element: class="fragment" -->
- The JVM rocks! <!-- .element: class="fragment" -->

#VSLIDE

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr class="fragment">
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr class="fragment">
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

#HSLIDE
## <span style="text-transform: none">PITCHME.yaml</span> Settings
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slideshow-Settings" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Stamp Your Own Look and Feel

<br>

Set a default theme, custom logo, background image, and preferred code syntax highlighting style.

#VSLIDE

#### Customize Slideshow Behavior

<br>

Enable auto-slide with custom intervals, looping, and RTL.


#HSLIDE
## Slideshow Keyboard Controls
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slideshow-Fullscreen-Mode" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Try Out These Great Features Now!

<br>

| Mode | On Key | Off Key |
| ---- | :------: | :--------: |
| Fullscreen | F |  Esc |
| Overview | O |  O |
| Blackout | B |  B |
| Help | ? |  Esc |


#HSLIDE

## GitPitch Social
<span style="font-size:0.6em; color:gray">See slides below for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slideshow-GitHub-Badge" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Slideshows Designed For Sharing

<br>

- View any slideshow at its public URL
- [Promote](https://github.com/gitpitch/gitpitch/wiki/Slideshow-GitHub-Badge) any slideshow using a GitHub badge
- [Embed](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Embedding) any slideshow within a blog or website
- [Share](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Sharing) any slideshow on Twitter, LinkedIn, etc
- [Print](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Printing) any slideshow as PDF document
- [Download and present](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Offline) any slideshow offline

#HSLIDE

## GO FOR IT.
## JUST ADD <span style="color:#e49436; text-transform: none">PITCHME.md</span> ;)
