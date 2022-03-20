---
title: "Navbar"
description: "Info on the Navbar and use"
lead: "Info on the Navbar and use"
date: 2020-11-12T13:26:54+01:00
lastmod: 2020-11-12T13:26:54+01:00
draft: true
images: []
menu:
  docs:
    parent: "components"
weight: 610
toc: true
---

<h2>Top Navbar</h2>
<p>Example</p>


{{< figure src="../../../images/top-navbar.png" class="img-fluid shadow p-3 mb-5 bg-body rounded" >}}
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
<a href="https://rmit.edu.au" aria-label="Royal Melbourne Institute of Technology University Logo" class="rmit-logo navbar-brand">
                  </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
      <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            RMIT Australia   <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chevron-down" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"/>
</svg>
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">RMIT Europe</a></li>
            <li><a class="dropdown-item" href="#">RMIT Vietname</a></li>
            <li><a class="dropdown-item" href="#">RMIT Global</a></li>
            <li><a class="dropdown-item" href="#">RMIT Online</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Students</a>
        </li>
              <li class="nav-item">
          <a class="nav-link" href="#">Staff</a>
        </li>
              <li class="nav-item">
          <a class="nav-link" href="#">Library</a>
        </li>
              <li class="nav-item">
          <a class="nav-link" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-heart" viewBox="0 0 16 16">
  <path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"/>
</svg></i></a>
        </li>
                <li class="nav-item">
          <a class="nav-link" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
  <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
</svg></a>
        </li>
      </ul>
  </div>
</nav>
<div class="highlight"><pre class="chroma"><code class="language-html" data-lang="html"><span class="p">&lt;nav class=&quot;navbar navbar-expand-lg navbar-dark bg-dark&quot;&gt;
  &lt;div class=&quot;container-fluid&quot;&gt;
&lt;a href=&quot;https://rmit.edu.au&quot; aria-label=&quot;Royal Melbourne Institute of Technology University Logo&quot; class=&quot;rmit-logo navbar-brand&quot;&gt;
                  &lt;/a&gt;
    &lt;button class=&quot;navbar-toggler&quot; type=&quot;button&quot; data-bs-toggle=&quot;collapse&quot; data-bs-target=&quot;#navbarSupportedContent&quot; aria-controls=&quot;navbarSupportedContent&quot; aria-expanded=&quot;false&quot; aria-label=&quot;Toggle navigation&quot;&gt;
      &lt;span class=&quot;navbar-toggler-icon&quot;&gt;&lt;/span&gt;
    &lt;/button&gt;
    &lt;div class=&quot;collapse navbar-collapse&quot; id=&quot;navbarSupportedContent&quot;&gt;
      &lt;ul class=&quot;navbar-nav me-auto mb-2 mb-lg-0&quot;&gt;
      &lt;li class=&quot;nav-item dropdown&quot;&gt;
          &lt;a class=&quot;nav-link dropdown-toggle&quot; href=&quot;#&quot; id=&quot;navbarDropdown&quot; role=&quot;button&quot; data-bs-toggle=&quot;dropdown&quot; aria-expanded=&quot;false&quot;&gt;
            RMIT Australia   &lt;svg xmlns=&quot;http://www.w3.org/2000/svg&quot; width=&quot;16&quot; height=&quot;16&quot; fill=&quot;currentColor&quot; class=&quot;bi bi-chevron-down&quot; viewBox=&quot;0 0 16 16&quot;&gt;
  &lt;path fill-rule=&quot;evenodd&quot; d=&quot;M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z&quot;/&gt;
&lt;/svg&gt;
          &lt;/a&gt;
          &lt;ul class=&quot;dropdown-menu&quot; aria-labelledby=&quot;navbarDropdown&quot;&gt;
            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;RMIT Europe&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;RMIT Vietname&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;RMIT Global&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;RMIT Online&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li class=&quot;nav-item&quot;&gt;
          &lt;a class=&quot;nav-link&quot; href=&quot;#&quot;&gt;Students&lt;/a&gt;
        &lt;/li&gt;
              &lt;li class=&quot;nav-item&quot;&gt;
          &lt;a class=&quot;nav-link&quot; href=&quot;#&quot;&gt;Staff&lt;/a&gt;
        &lt;/li&gt;
              &lt;li class=&quot;nav-item&quot;&gt;
          &lt;a class=&quot;nav-link&quot; href=&quot;#&quot;&gt;Library&lt;/a&gt;
        &lt;/li&gt;
              &lt;li class=&quot;nav-item&quot;&gt;
          &lt;a class=&quot;nav-link&quot; href=&quot;#&quot;&gt;&lt;svg xmlns=&quot;http://www.w3.org/2000/svg&quot; width=&quot;16&quot; height=&quot;16&quot; fill=&quot;currentColor&quot; class=&quot;bi bi-heart&quot; viewBox=&quot;0 0 16 16&quot;&gt;
  &lt;path d=&quot;m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z&quot;/&gt;
&lt;/svg&gt;&lt;/i&gt;&lt;/a&gt;
        &lt;/li&gt;
                &lt;li class=&quot;nav-item&quot;&gt;
          &lt;a class=&quot;nav-link&quot; href=&quot;#&quot;&gt;&lt;svg xmlns=&quot;http://www.w3.org/2000/svg&quot; width=&quot;16&quot; height=&quot;16&quot; fill=&quot;currentColor&quot; class=&quot;bi bi-search&quot; viewBox=&quot;0 0 16 16&quot;&gt;
  &lt;path d=&quot;M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z&quot;/&gt;
&lt;/svg&gt;&lt;/a&gt;
        &lt;/li&gt;
      &lt;/ul&gt;
  &lt;/div&gt;
&lt;/nav&gt;</span></code></pre></div>



<h2>Secondary Nav (tabs)</h2>
<p>Example</p>
{{< figure src="../../../images/tab-navs.png" class="img-fluid shadow p-3 mb-5 bg-body rounded" >}}
<nav>
  <div class="nav nav-tabs" id="nav-tab" role="tablist">
    <button class="nav-link active" id="nav-home-tab" data-bs-toggle="tab" data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home" aria-selected="true">Home</button>
    <button class="nav-link" id="nav-profile-tab" data-bs-toggle="tab" data-bs-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile" aria-selected="false">Profile</button>
    <button class="nav-link" id="nav-contact-tab" data-bs-toggle="tab" data-bs-target="#nav-contact" type="button" role="tab" aria-controls="nav-contact" aria-selected="false">Contact</button>
  </div>
</nav>
<div class="tab-content" id="nav-tabContent">
  <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab">The antecedent of RMIT, the Working Men's College of Melbourne, was founded by the Scottish-born grazier and politician The Hon. Francis Ormond in the 1880s. </div>
  <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab">Planning began in 1881, with Ormond basing his model for the college on the Birkbeck Literary and Scientific Institution (now a constituent college of the University of London), Brighton College of Art (now the University of Brighton), Royal College of Art, and the Working Men's College of London</div>
  <div class="tab-pane fade" id="nav-contact" role="tabpanel" aria-labelledby="nav-contact-tab">Ormond donated the sum of £5000 toward the foundation of the college. He was supported in the Victorian Parliament by Charles Pearson and in the Melbourne Trades Hall by William Emmett Murphy.</div>
</div>