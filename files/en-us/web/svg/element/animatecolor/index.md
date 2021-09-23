---
title: <animateColor>
slug: Web/SVG/Element/animateColor
tags:
  - Deprecated
  - Element
  - SVG
  - SVG Animation
browser-compat: svg.elements.animateColor
---
<div>{{SVGRef}}{{deprecated_header}}</div>

<div class="warning">
<p><strong>Warning:</strong> This element has been deprecated in SVG 1.1 Second Edition and may be removed in a future version of SVG. It provides no features not already available by using the {{SVGElement("animate")}} element. So, authors should use the <code>&lt;animate&gt;</code> element instead.</p>
</div>

<p>The <strong><code>&lt;animateColor&gt;</code></strong> <a href="/en-US/docs/Web/SVG">SVG</a> element specifies a color transformation over time.</p>

<h2 id="Usage_context">Usage context</h2>

<p>{{svginfo}}</p>

<h2 id="Attributes">Attributes</h2>

<h3 id="Global_attributes">Global attributes</h3>

<ul>
 <li><a href="/en-US/docs/Web/SVG/Attribute#conditional_processing_attributes">Conditional processing attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#core_attributes">Core attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#animation_event_attributes">Animation event attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#xlink_attributes">Xlink attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#animation_attribute_target_attributes">Animation attribute target attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#animation_timing_attributes">Animation timing attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#animation_value_attributes">Animation value attributes</a></li>
 <li><a href="/en-US/docs/Web/SVG/Attribute#animation_addition_attributes">Animation addition attributes</a></li>
</ul>

<h3 id="Specific_attributes">Specific attributes</h3>

<ul>
 <li>{{SVGAttr("by")}}</li>
 <li>{{SVGAttr("from")}}</li>
 <li>{{SVGAttr("to")}}</li>
</ul>

<h2 id="DOM_Interface">DOM Interface</h2>

<p>This element implements the {{domxref("SVGAnimateColorElement")}} interface.</p>

<h2 id="Example">Example</h2>

<h3 id="SVG">SVG</h3>

<pre class="brush:html">&lt;svg width="120" height="120" xmlns="http://www.w3.org/2000/svg"&gt;
  &lt;circle cx="60" cy="60" r="50"&gt;
    &lt;animateColor attributeName="fill" attributeType="XML"
        from="black" to="red" dur="6s" repeatCount="indefinite"/&gt;
  &lt;/circle&gt;
&lt;/svg&gt;
</pre>

<h3 id="Result">Result</h3>

<p>{{EmbedLiveSample("Example", 120, 120)}}</p>

<h2 id="Specifications">Specifications</h2>

{{Specifications}}

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>

<h2 id="See_also">See also</h2>

<ul>
 <li>{{SVGElement("animate")}}</li>
</ul>