---
layout: "v2_fluid/docs_base"
version: "2.0.0-alpha.53"
versionHref: "/docs/v2/2.0.0-alpha.53"
path: ""
category: api
id: "textarea"
title: "TextArea"
header_sub_title: "Class in module "
doc: "TextArea"
docType: "class"

---









<h1 class="api-title">


TextArea






</h1>

<a class="improve-v2-docs" href='http://github.com/driftyco/ionic/edit/2.0/ionic/components/input/input.ts#L91'>
Improve this doc
</a>






<p><code>ion-textarea</code> is is used for multi-line text inputs. Ionic still
uses an actual <code>&lt;textarea&gt;</code> HTML element within the component,
however, with Ionic wrapping the native HTML textarea element then
Ionic is able to better handle the user experience and interactivity.</p>
<p>Not that <code>&lt;ion-textarea&gt;</code> must load its value from the <code>value</code> or
<code>[(ngModel)]</code> attribute. Unlike the native <code>&lt;textarea&gt;</code> element,
<code>&lt;ion-textarea&gt;</code> does not support loading its value from the
textarea&#39;s inner content.</p>
<p>When requiring only a single-line text input it&#39;s recommended
to use <code>&lt;ion-input&gt;</code> instead.</p>


<h2>Component</h2>
<h3>selector: <code>ion-textarea</code></h3>
<!-- @usage tag -->

<h2>Usage</h2>

<pre><code class="lang-html">&lt;ion-item&gt;
  &lt;ion-label&gt;Comments&lt;/ion-label&gt;
  &lt;ion-textarea&gt;&lt;/ion-textarea&gt;
&lt;/ion-item&gt;

&lt;ion-item&gt;
  &lt;ion-labe stacked&gt;Message&lt;/ion-label&gt;
  &lt;ion-textarea [(ngModel)]=&quot;msg&quot;&gt;&lt;/ion-textarea&gt;
&lt;/ion-item&gt;

&lt;ion-item&gt;
  &lt;ion-labe floating&gt;Description&lt;/ion-label&gt;
  &lt;ion-textarea&gt;&lt;/ion-textarea&gt;
&lt;/ion-item&gt;
</code></pre>




<!-- @property tags -->

<h2>Attributes:</h2>
<table class="table" style="margin:0;">
<thead>
<tr>
<th>Attribute</th>







<th>Description</th>
</tr>
</thead>
<tbody>

<tr>
<td>
inset
</td>



<td>
The textarea will be inset

</td>
</tr>

</tbody>
</table>


<!-- methods on the class -->

<h2>Methods</h2>

<div id="ngOnInit"></div>

<h3>
<code>ngOnInit()</code>


</h3>










<!-- related link --><!-- end content block -->


<!-- end body block -->
