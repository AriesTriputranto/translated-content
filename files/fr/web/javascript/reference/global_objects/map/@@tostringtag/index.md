---
title: Map.prototype[@@toStringTag]()
slug: Web/JavaScript/Reference/Global_Objects/Map/@@toStringTag
tags:
  - ECMAScript 2015
  - JavaScript
  - Map
  - Méthode
  - Prototype
  - Reference
translation_of: Web/JavaScript/Reference/Global_Objects/Map/@@toStringTag
original_slug: Web/JavaScript/Reference/Global_Objects/Map/@@toStringTag
---
<div>{{JSRef}}</div>

<p>La propriété <strong><code>Map[@@toStringTag]</code></strong> vaut "Map" initialement.</p>

<div>{{EmbedInteractiveExample("pages/js/map-prototype-@@tostringtag.html")}}</div>

<div>{{js_property_attributes(0,0,1)}}</div>

<h2 id="Syntaxe">Syntaxe</h2>

<pre class="syntaxbox">Map[Symbol.toStringTag]</pre>

<h2 id="Exemple">Exemple</h2>

<pre class="brush:js">Object.prototype.toString.call(new Map()) // "[object Map]"</pre>

<h2 id="Spécifications">Spécifications</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Spécification</th>
   <th scope="col">État</th>
   <th scope="col">Commentaires</th>
  </tr>
  <tr>
   <td>{{SpecName('ES2015', '#sec-map.prototype-@@tostringtag', 'Map.prototype[@@toStringTag]')}}</td>
   <td>{{Spec2('ES2015')}}</td>
   <td>Définition initiale.</td>
  </tr>
  <tr>
   <td>{{SpecName('ESDraft', '#sec-map.prototype-@@tostringtag', 'Map.prototype[@@toStringTag]')}}</td>
   <td>{{Spec2('ESDraft')}}</td>
   <td> </td>
  </tr>
 </tbody>
</table>

<h2 id="Compatibilité_des_navigateurs">Compatibilité des navigateurs</h2>

<p>{{Compat("javascript.builtins.Map.@@toStringTag")}}</p>