<!DOCTYPE html>
<!-- saved from url=(0125)https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html -->
<html lang="en-US"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>The Fellowship Companion - Artifact II: Decisions | The-FellowShip-of-the-Code-2026</title>
<meta name="generator" content="Jekyll v3.10.0">
<meta property="og:title" content="The Fellowship Companion - Artifact II: Decisions">
<meta property="og:locale" content="en_US">
<meta name="description" content="Application Design &amp; Development 2026">
<meta property="og:description" content="Application Design &amp; Development 2026">
<link rel="canonical" href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html">
<meta property="og:url" content="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html">
<meta property="og:site_name" content="The-FellowShip-of-the-Code-2026">
<meta property="og:type" content="website">
<meta name="twitter:card" content="summary">
<meta property="twitter:title" content="The Fellowship Companion - Artifact II: Decisions">
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebPage","description":"Application Design &amp; Development 2026","headline":"The Fellowship Companion - Artifact II: Decisions","url":"https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html"}</script>
<!-- End Jekyll SEO tag -->

    <style class="anchorjs"></style><link rel="stylesheet" href="./The Fellowship Companion - Artifact II_ Decisions _ The-FellowShip-of-the-Code-2026_files/style.css">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/The-FellowShip-of-the-Code-2026/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/">The-FellowShip-of-the-Code-2026</a></h1>
      

      <h1 id="the-fellowship-companion---artifact-ii-decisions">The Fellowship Companion - Artifact II: Decisions</h1>

<p><em><code class="language-plaintext highlighter-rouge">(For demonstration purposes only)</code></em></p>

<h2 id="system-capability">System Capability<a class="anchorjs-link " href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html#system-capability" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>

<p><strong>Support decision-making for the Fellowship.</strong></p>

<p>I chose this because decisions are important in the journey.</p>

<h2 id="flow">Flow<a class="anchorjs-link " href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html#flow" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>

<p><code class="language-plaintext highlighter-rouge">[Flow](/src/flowchart.mermaid.md)</code></p>

<blockquote>
  <p>For this example see <a href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/src/flowchart.weak.mermaid.html">flowchart.weak.mermaid.md</a></p>
</blockquote>

<h2 id="wireframe">Wireframe<a class="anchorjs-link " href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html#wireframe" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>

<p><code class="language-plaintext highlighter-rouge">[Wireframe](/src/wireframe.png)</code></p>

<blockquote>
  <p>For this example see <a href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/src/wireframe.weak.png">wireframe.weak.png</a></p>
</blockquote>

<h2 id="design-rationale">Design Rationale<a class="anchorjs-link " href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html#design-rationale" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>

<p>This design supports the intent because it helps the Fellowship make decisions. The flow is straightforward and easy to understand.</p>

<p>I did not include too many details because that would make it complicated. The system should stay simple.</p>

<p><strong>Assumption:</strong> The user knows what decision they want to make.</p>

<hr>
<hr>

<h2 id="why-this-is-weak">Why this is weak<a class="anchorjs-link " href="https://estebanthewhite.github.io/The-FellowShip-of-the-Code-2026/examples/artifacts/artifact-2/artifact-2-deciding.weak.html#why-this-is-weak" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>

<ul>
  <li>Capability is too vague (<em>“Support decision-making”</em> is not narrowed down)
    <ul>
      <li>What kind of decision?</li>
      <li>Route?</li>
      <li>Risk?</li>
      <li>Resource allocation?</li>
      <li>Timing?
        <ul>
          <li><em>No concrete scenario = no meaningful slice.</em></li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Flow is superficial
    <ul>
      <li>No decision branches</li>
      <li>No alternative paths</li>
      <li>No error states</li>
      <li>No real system logic</li>
      <li>Could apply to any app in the world
        <ul>
          <li><em>It shows steps, but not reasoning.</em></li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Wireframe is generic
    <ul>
      <li>No structure explained</li>
      <li>No prioritization of information</li>
      <li>No indication of constraints</li>
      <li>No connection to the journey context
        <ul>
          <li><em>It describes a page with a text field and button.</em></li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Design rationale lacks thinking
    <ul>
      <li>No reference to Assignment 1 intent/value</li>
      <li>No trade-offs discussed</li>
      <li><em>“Keep it simple”</em> is not a design argument</li>
      <li>Assumptions are trivial and unexamined</li>
    </ul>
  </li>
  <li>No visible narrowing of scope
    <ul>
      <li>Why this slice matters?</li>
      <li>What was intentionally excluded?</li>
      <li>How this prepares future implementation?</li>
    </ul>
  </li>
</ul>

<p><em><code class="language-plaintext highlighter-rouge">This example is not entirely wrong, but it is very generic and would be very hard to build on in later assignments.</code></em></p>


      
      <div class="footer border-top border-gray-light mt-5 pt-3 text-right text-gray">
        This site is open source. <a href="https://github.com/EstebanTheWhite/The-FellowShip-of-the-Code-2026/edit/main/examples/artifacts/artifact-2/artifact-2-deciding.weak.md">Improve this page</a>.
      </div>
      
    </div>
    <script src="./The Fellowship Companion - Artifact II_ Decisions _ The-FellowShip-of-the-Code-2026_files/anchor.min.js.Herunterladen" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  

</body></html>