<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="" xml:lang="">
<head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <title>test</title>
  <style>
    html {
      line-height: 1.5;
      font-family: Georgia, serif;
      font-size: 20px;
      color: #1a1a1a;
      background-color: #fdfdfd;
    }
    body {
      margin: 0 auto;
      max-width: 36em;
      padding-left: 50px;
      padding-right: 50px;
      padding-top: 50px;
      padding-bottom: 50px;
      hyphens: auto;
      overflow-wrap: break-word;
      text-rendering: optimizeLegibility;
      font-kerning: normal;
    }
    @media (max-width: 600px) {
      body {
        font-size: 0.9em;
        padding: 1em;
      }
    }
    @media print {
      body {
        background-color: transparent;
        color: black;
        font-size: 12pt;
      }
      p, h2, h3 {
        orphans: 3;
        widows: 3;
      }
      h2, h3, h4 {
        page-break-after: avoid;
      }
    }
    p {
      margin: 1em 0;
    }
    a {
      color: #1a1a1a;
    }
    a:visited {
      color: #1a1a1a;
    }
    img {
      max-width: 100%;
    }
    h1, h2, h3, h4, h5, h6 {
      margin-top: 1.4em;
    }
    h5, h6 {
      font-size: 1em;
      font-style: italic;
    }
    h6 {
      font-weight: normal;
    }
    ol, ul {
      padding-left: 1.7em;
      margin-top: 1em;
    }
    li > ol, li > ul {
      margin-top: 0;
    }
    blockquote {
      margin: 1em 0 1em 1.7em;
      padding-left: 1em;
      border-left: 2px solid #e6e6e6;
      color: #606060;
    }
    code {
      font-family: Menlo, Monaco, 'Lucida Console', Consolas, monospace;
      font-size: 85%;
      margin: 0;
    }
    pre {
      margin: 1em 0;
      overflow: auto;
    }
    pre code {
      padding: 0;
      overflow: visible;
      overflow-wrap: normal;
    }
    .sourceCode {
     background-color: transparent;
     overflow: visible;
    }
    hr {
      background-color: #1a1a1a;
      border: none;
      height: 1px;
      margin: 1em 0;
    }
    table {
      margin: 1em 0;
      border-collapse: collapse;
      width: 100%;
      overflow-x: auto;
      display: block;
      font-variant-numeric: lining-nums tabular-nums;
    }
    table caption {
      margin-bottom: 0.75em;
    }
    tbody {
      margin-top: 0.5em;
      border-top: 1px solid #1a1a1a;
      border-bottom: 1px solid #1a1a1a;
    }
    th {
      border-top: 1px solid #1a1a1a;
      padding: 0.25em 0.5em 0.25em 0.5em;
    }
    td {
      padding: 0.125em 0.5em 0.25em 0.5em;
    }
    header {
      margin-bottom: 4em;
      text-align: center;
    }
    #TOC li {
      list-style: none;
    }
    #TOC a:not(:hover) {
      text-decoration: none;
    }
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    span.underline{text-decoration: underline;}
    div.column{display: inline-block; vertical-align: top; width: 50%;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
  </style>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
&lt;!DOCTYPE html&gt;
<html xmlns="http://www.w3.org/1999/xhtml" lang xml:lang>
<head>
<meta charset="utf-8" />
<meta name="generator" content="pandoc" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
<title>
lec1
</title>
<style>
    html {
      line-height: 1.5;
      font-family: Georgia, serif;
      font-size: 20px;
      color: #1a1a1a;
      background-color: #fdfdfd;
    }
    body {
      margin: 0 auto;
      max-width: 36em;
      padding-left: 50px;
      padding-right: 50px;
      padding-top: 50px;
      padding-bottom: 50px;
      hyphens: auto;
      overflow-wrap: break-word;
      text-rendering: optimizeLegibility;
      font-kerning: normal;
    }
    @media (max-width: 600px) {
      body {
        font-size: 0.9em;
        padding: 1em;
      }
    }
    @media print {
      body {
        background-color: transparent;
        color: black;
        font-size: 12pt;
      }
      p, h2, h3 {
        orphans: 3;
        widows: 3;
      }
      h2, h3, h4 {
        page-break-after: avoid;
      }
    }
    p {
      margin: 1em 0;
    }
    a {
      color: #1a1a1a;
    }
    a:visited {
      color: #1a1a1a;
    }
    img {
      max-width: 100%;
    }
    h1, h2, h3, h4, h5, h6 {
      margin-top: 1.4em;
    }
    h5, h6 {
      font-size: 1em;
      font-style: italic;
    }
    h6 {
      font-weight: normal;
    }
    ol, ul {
      padding-left: 1.7em;
      margin-top: 1em;
    }
    li > ol, li > ul {
      margin-top: 0;
    }
    blockquote {
      margin: 1em 0 1em 1.7em;
      padding-left: 1em;
      border-left: 2px solid #e6e6e6;
      color: #606060;
    }
    code {
      font-family: Menlo, Monaco, 'Lucida Console', Consolas, monospace;
      font-size: 85%;
      margin: 0;
    }
    pre {
      margin: 1em 0;
      overflow: auto;
    }
    pre code {
      padding: 0;
      overflow: visible;
      overflow-wrap: normal;
    }
    .sourceCode {
     background-color: transparent;
     overflow: visible;
    }
    hr {
      background-color: #1a1a1a;
      border: none;
      height: 1px;
      margin: 1em 0;
    }
    table {
      margin: 1em 0;
      border-collapse: collapse;
      width: 100%;
      overflow-x: auto;
      display: block;
      font-variant-numeric: lining-nums tabular-nums;
    }
    table caption {
      margin-bottom: 0.75em;
    }
    tbody {
      margin-top: 0.5em;
      border-top: 1px solid #1a1a1a;
      border-bottom: 1px solid #1a1a1a;
    }
    th {
      border-top: 1px solid #1a1a1a;
      padding: 0.25em 0.5em 0.25em 0.5em;
    }
    td {
      padding: 0.125em 0.5em 0.25em 0.5em;
    }
    header {
      margin-bottom: 4em;
      text-align: center;
    }
    #TOC li {
      list-style: none;
    }
    #TOC a:not(:hover) {
      text-decoration: none;
    }
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    span.underline{text-decoration: underline;}
    div.column{display: inline-block; vertical-align: top; width: 50%;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
  </style>
<script
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml-full.js"
  type="text/javascript"></script>
<!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
<nav id="TOC" role="doc-toc">
<ul>
<li>
<a href="#first-real-lecture">First Real Lecture</a>
<ul>
<li>
<a href="#direction">Direction</a>
</li>
<li>
<a href="#dot-product-vecv-cdot-vecw-scalar-product">Dot Product: <span
class="math inline">( )</span> (Scalar Product)</a>
<ul>
<li>
<a href="#properties">Properties</a>
</li>
<li>
<a href="#finding-the-angle-between-two-vectors">Finding the angle
between two vectors:</a>
</li>
<li>
<a href="#section"><span class="math inline">(90^0)</span></a>
</li>
<li>
<a href="#projections">Projections</a>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</nav>
<h1 id="first-real-lecture">
First Real Lecture
</h1>
<ins>
from last time:
</ins>
<ul>
<li>
defined vectors and scalars in <span class="math inline">(^2)</span> and
<span class="math inline">(^3)</span>
</li>
<li>
defined how to add/subtract/scale vectors
</li>
<li>
defined the magnitude(length) of a vector <span class="math display">[
|a,b | = ]</span> <span class="math display">[ |a,b,c | = ]</span> <span
class="math display">[ + = + ]</span>
</li>
</ul>
<h2 id="direction">
Direction
</h2>
<ul>
<li>
A unit vector is a vector with magnitude 1
<ul>
<li>
a unit vector in the direction of <span class="math inline">()</span>
would be <span class="math inline">( ||)</span>
</li>
<li>
ex: <span class="math inline">(,1,4 )</span> has a magnituse $ = $, so
the vector points in the direction <span class="math inline">(1 )</span>
<span class="math inline">(,1,4 )</span>
</li>
</ul>
</li>
<li>
In <span class="math inline">(^2)</span>, we describe a direction by its
angle
<ul>
<li>
<span class="math inline">( = rcos, rsin )</span>
</li>
</ul>
</li>
</ul>
<h2 id="dot-product-vecv-cdot-vecw-scalar-product">
Dot Product: <span class="math inline">( )</span> (Scalar Product)
</h2>
<ol type="a">
<li>
<span class="math inline">( = ||||cos)</span> where <span
class="math inline">()</span> is the angle between <span
class="math inline">()</span> and <span class="math inline">()</span>
</li>
</ol>
<p>
<span class="math inline">()</span>
</p>
<ol start="2" type="a">
<li>
<span class="math inline">(a_1,b_1 a_2,b_2 = a_1 a_2 + b_1b_2)</span>
</li>
</ol>
<h3 id="properties">
Properties
</h3>
<ul>
<li>
<span class="math inline">( = ||^2)</span>
<ul>
<li>
<span class="math inline">(a,b,c a,b,c = a^2 + b^2 + c^2 = ()^2)</span>
</li>
</ul>
</li>
<li>
<span class="math inline">( = )</span>
</li>
<li>
<span class="math inline">( ( + ) = + )</span>
</li>
<li>
<span class="math inline">(c( ) = (c) = (c ))</span>
</li>
</ul>
<h3 id="finding-the-angle-between-two-vectors">
Finding the angle between two vectors:
</h3>
<ul>
<li>
<span class="math inline">( = |||||cos)</span> <span
class="math display">[ cos= ]</span> <span class="math display">[ =
arccos() ]</span>
</li>
<li>
the range of arccos is 0-<span class="math inline">()</span>
</li>
<li>
<span class="math inline">(,2,3 ,5,6 )</span>
</li>
<li>
<span class="math inline">(= arccos())</span>
</li>
</ul>
<h3 id="section">
<span class="math inline">(90^0)</span>
</h3>
<ul>
<li>
if two vectors have an angle of <span class="math inline">(90^0)</span>
between them, we call them orthogonal
</li>
<li>
because <span class="math inline">(cos(90^0) = 0)</span>, the dot
product of orthogonal vectors is 0
</li>
<li>
<span class="math inline">(,)</span> are orthogonal <span
class="math inline">()</span> <span class="math inline">( = 0)</span>
</li>
</ul>
<h3 id="projections">
Projections
</h3>
<p>
How much of one vector points in the direction of the other?
</p>
<p>
Scalar projection: length of indicated vector in direction of other
vector
</p>
<p>
vector projection: split the vector into parallel and perpendicular
component
</p>
</body>
</html>
</body>
</html>
