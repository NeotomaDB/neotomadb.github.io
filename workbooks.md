---
layout: default
title: Workbooks
weight: 4
---

# Workbooks

<span style="text-align:full;">
A collection of instructional or informational resources for working with the Neotoma Paleoecological Database. All of these documents are licensed under an MIT license and are free to use.  You may also consider contributing through the [GitHub repository](https://github.com/neotomadb/Workbooks) for this site.  It's also worth noting that many of these linked documents also have their own GitHub repositories, indicated within the document and you are always welcome to contribute there too.</span>
<p><br>
<h2>Pages</h2>
<hr style="color:gray;margin-bottom:25px">
    
{% assign items = site.workbooks | sort: 'res_class' %}

{% for resources in items %}
  <div class="col-lg-3 col-md-6 text-center">
    <div class="resource-box">
	  <span style="font-variant:small-caps;font-size:110%;font-weight:500;"><big>{{ resources.title }}</big></span> [<a href="{{resources.url}}">Link</a>]<br>
      <span style = "display:inline-block;width:80%;color:gray;">{{ resources.concept }}</span><span style="float:right;color:green;"><small>{{ resources.res_class }}</small></span>
      <br><p></p>
	</div>
  </div>
{% endfor %}
