---
title: "Typography"
description: "Type, figures and glyphs"
lead: "Type, Figures and glyphs"
date: 2020-10-06T08:49:31+00:00
lastmod: 2020-10-06T08:49:31+00:00
draft: false
images: []
menu:
  docs:
    parent: "components"
weight: 200
toc: true
---



# Typeface
{{< figure src="../../../images/type-hierachy.png" class="img-fluid shadow p-3 mb-5 bg-body rounded" >}}
<h2>Serif / Museo. </h2>
<p>Museo is used for headlines (8 words or less) and Helvetica is used for supporting and subsequent copy.</p>
<hr>


## Links 

Inline links, use sparingly. Where possible add a call to action after text to provide better context.

Founded in 1887 by Francis Ormond, RMIT began as a night school offering classes in art, science, and technology, in response to the industrial revolution in Australia. To learn more about RMIT visit its <a href="https://rmit.edu.au" title="Links to the RMIT website">website</a>.
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;a href=&quot;https://rmit.edu.au&quot; title=&quot;Links to the RMIT website&quot;&gt;website&lt;/a&gt;</span></code></pre></div>

<h4>Better</h4>
Founded in 1887 by Francis Ormond, RMIT began as a night school offering classes in art, science, and technology, in response to the industrial revolution in Australia. To learn more about RMIT visit its website.
<br>
<a class="more" href="https://rmit.edu.au" title="Links to the RMIT website">Find out more</a>

<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;a class=&quot;more&quot; href=&quot;https://rmit.edu.au&quot; title=&quot;Links to the RMIT website&quot;&gt;Find out more&lt;/a&gt;
</span></code></pre></div>



## Headings

<p>Sans Serif option (Museo)</p>
<h1 class="museo">Heading 1</h1>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h1 class=&quot;museo&quot;&gt;Heading 1&lt;/h1&gt;</span></code></pre></div>

<h2 class="museo">Heading 2</h2>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h2 class=&quot;museo&quot;&gt;Heading 2&lt;/h2&gt;</span></code></pre></div>
<h3 class="museo">Heading 3</h3>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h3 class=&quot;museo&quot;&gt;Heading 3&lt;/h3&gt;</span></code></pre></div>
<h4 class="museo">Heading 4</h4>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h4 class=&quot;museo&quot;&gt;Heading 4&lt;/h4&gt;</span></code></pre></div>
<h5 class="museo">Heading 5</h5>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h5 class=&quot;museo&quot;&gt;Heading 5&lt;/h5&gt;</span></code></pre></div>

<p>Sans Serif option</p>
<hr>
<h1>Heading 1</h1>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h1&gt;Heading 1&lt;/h1&gt;</span></code></pre></div>
<h2>Heading 2</h2>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h2&gt;Heading 2&lt;/h2&gt;</span></code></pre></div>

<h3>Heading 3</h3>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h3&gt;Heading 3&lt;/h3&gt;</span></code></pre></div>

<h4>Heading 4</h4>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h4&gt;Heading 4&lt;/h4&gt;</span></code></pre></div>

<h5>Heading 5</h5>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h5&gt;Heading 5&lt;/h5&gt;</span></code></pre></div>
<hr> 

### Headings with a line

{{< figure src="../../../images/the-line.png" class="img-fluid shadow p-3 mb-5 bg-body rounded" >}}
<hr>
<h1 class="line">Heading 1</h1>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h1 class=&quot;line&quot;&gt;Heading 1&lt;/h1&gt;</span></code></pre></div>
<h2 class="line">Heading 2</h2>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h2 class=&quot;line&quot;&gt;Heading 2&lt;/h2&gt;</span></code></pre></div>

<h3 class="line">Heading 3</h3>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h3 class=&quot;line&quot;&gt;Heading 3&lt;/h3&gt;</span></code></pre></div>

<h4 class="line">Heading 4</h4>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h4 class=&quot;line&quot;&gt;Heading 4&lt;/h4&gt;</span></code></pre></div>

<h5 class="line">Heading 5</h5>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h5 class=&quot;line&quot;&gt;Heading 5 class=&quot;museo&quot; &lt;/h5&gt;</span></code></pre></div>


<hr>

### Display Headings - Red band / Text Boxes
{{< figure src="../../../images/text-boxes.png" class="img-fluid shadow p-3 mb-5 bg-body rounded" >}}
<p>Note this format has <a href="https://webaim.org/resources/contrastchecker/?fcolor=E61E2A&bcolor=000054">accessibility issues</a>, So use sparingly, in large text or avoid completely.</p>
<hr>
<h1 class="display-1">Display 1</h1>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h1 class=&quot;display-1&quot;&gt;Display 1&lt;/h1&gt;</span></code></pre></div>
<h2 class="display-2">Display 2</h2>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h2 class=&quot;display-2&quot;&gt;Display 2&lt;/h1&gt;</span></code></pre></div>
<h3 class="display-3">Display 3</h3>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h2 class=&quot;display-3&quot;&gt;Display 3&lt;/h1&gt;</span></code></pre></div>
<h4 class="display-4">Display 4</h4>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h2 class=&quot;display-4&quot;&gt;Display 4&lt;/h1&gt;</span></code></pre></div>
<h5 class="display-5">Display 5</h5>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h4 class=&quot;display-5&quot;&gt;Display 5&lt;/h1&gt;</span></code></pre></div>
<h6 class="display-6">Display 6</h6>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;h5 class=&quot;display-6&quot;&gt;Display 6&lt;/h1&gt;</span></code></pre></div>


## Paragraphs

<p>All text content</p>
<h3>Lead text</h3>
<p class="lead">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris mollis magna cursus nunc condimentum, a porttitor mauris sodales. Interdum et malesuada fames ac ante ipsum primis in faucibus. </p>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;p class=&quot;lead&quot;&gt;
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris mollis magna cursus nunc condimentum, a porttitor mauris sodales. Interdum et malesuada fames ac ante ipsum primis in faucibus. &lt;/p&gt;</span></code></pre></div>
<h3>Normal text</h3>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris mollis magna cursus nunc condimentum, a porttitor mauris sodales. Interdum et malesuada fames ac ante ipsum primis in faucibus. Sed vehicula purus ut mi hendrerit, ut tempor sem elementum. Mauris id hendrerit lacus. Aliquam ut ex dui. Duis pharetra leo quis porta pharetra. Nunc vel libero nisi. Phasellus metus enim, consequat a imperdiet eu, pretium non massa. Mauris mauris mauris, luctus eu mi ut, condimentum auctor mauris.</p>
<p>
Ut eu tempus ex. Duis molestie diam porta sodales laoreet. Curabitur tempus, dolor at accumsan tincidunt, augue tortor malesuada arcu, eu feugiat ipsum nisi sed nulla. Ut nec risus quis nibh molestie congue. Aliquam eu tortor semper, mattis erat in, porttitor massa. Maecenas nibh tortor, viverra id lectus eu, eleifend iaculis tellus. Cras nec congue ex. Etiam ante nulla, sodales at justo non, hendrerit porta turpis. Donec ut lorem lobortis, luctus massa eu, accumsan nibh. Morbi tristique, nibh ac bibendum vehicula, erat odio tincidunt libero, sit amet egestas nibh eros ut arcu.
</p>

<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;p&gt;
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris mollis magna cursus nunc condimentum, a porttitor mauris sodales. Interdum et malesuada fames ac ante ipsum primis in faucibus. &lt;/p&gt;</span></code></pre></div>


