Advanced-Pagination
===================

<p>Advanced Pagination content is divided into subareas and creates a pagination in order to control. The script is based on jQuery and brings a handful of options and callbacks with, so that it can be adapted to the custom needs.</p>

Usage
=====

<p>The plugin Advanced Pagination requires jQuery and must be included after the library..</p>
      
<pre><code>&lt;!DOCTYPE html>
&lt;html>
&lt;head>
  ...
&lt;/head>
&lt;body>
  ...
  &lt;div id="paginaNav">&lt;/div>
  &lt;div id="pagesWrap">
    
    &lt;div class="page">
      &lt;!-- content page 1 -->
    &lt;/div>

    &lt;div class="page">
      &lt;!-- content page 2 -->
    &lt;/div>

  &lt;/div>
  ...
  &lt;script src="libs/jquery.min.js">&lt;/script>
  &lt;script src="plugins/advanced-pagination.min.js">&lt;/script>
&lt;/body>
&lt;/html>
</code></pre>
      
<p>Here is just the bare minimum markup. Other possibilities there in the demo. The plugin must be called in (document). ready function.</p>

<pre><code>...
&lt;script>
  $(document).ready(function(){
  	$('#pagesWrap').advancedPagination();
  });
&lt;/script>
...
</code></pre>

CSS
===

<p>Advanced Pagination does not require any CSS styles. The finished appearance will you leave - have fun when styling!</p>
			

Options
=======

<table class="Table">
<thead>
<tr>
    <th scope="col">Key</th>
    <th scope="col">Default value</th>
    <th scope="col">Description</th>
</tr> 
</thead>
        <tbody>
        	<tr>
          	<td>pageClass</td>
            <td>'page'</td>
            <td>CSS class of the container, which divided the sections ("pages"). (String)</td>
          </tr>
          <tr>
          	<td>paginaContainer</td>
            <td>'#paginaNav'</td>
            <td>In this HTML element, the page navigation (pagination or pagina) is generated. The child elements created are a tags. (String).</td>
          </tr>
          <tr>
          	<td>paginaAnchText</td>
            <td>false</td>
            <td>If set to true, the pagina links contain text instead of numbers. The title text is passed to the respective page (.page) with the attribute data-text. (Boolean)</td>
          </tr>
          <tr>
          	<td>pageAnnimation</td>
            <td>'fade'</td>
            <td>The option changes the animation of the page transitions. Possible are the information "fade" or "slide". (String).</td>
          </tr>
          <tr>
          	<td>animationSpeed</td>
            <td>250</td>
            <td>Specifies the animation speed of the page transitions. (Number)</td>
          </tr>
          <tr>
          	<td>easing</td>
            <td>'easeOutBounce'</td>
            <td>Adds the page changes an easing effect. (String)</td>
          </tr>
          <tr>
          	<td>prevLink</td>
            <td>'.prevPage'</td>
            <td>You can add links to the previous page. The script responds to the specified class or ID. (String)</td>
          </tr>
          <tr>
        <td>nextLink</td>
        <td>'.nextPage'</td>
       <td>Similar to prevLink, only it goes to the next page here. (String)</td>
</tr>
<tr>
        <td>onPrev</td>
        <td>&nbsp;</td>
        <td>You can overwrite the change to the previous page with your own function. (Function)</td>
</tr>
<tr>
        <td>onNext</td>
        <td>&nbsp;</td>
	<td>Overrides the switch to the next page with a custom function. (Function)</td>
</tr>
<tr>
	<td>onSwitch</td>
	<td>&nbsp;</td>
	<td>A separate function that is executed between page flipping. (Function)</td>
</tr>
<tr>
     <td>afterSwitch</td>
     <td>&nbsp;</td>
     <td>A Custom function that is run after the page switch. (Function)</td>
</tr>
</tbody>
</table>
      
change log
==========

<table class="Table">
<thead>
<tr>
     <th scope="col">Version</th>
     <th scope="col">Änderung</th>
     <th scope="col">Erklärung</th>
</tr>
</thead>
<tbody>
<tr>
	<th scope="row">Version 1.0</th>
	<td>Finale Version</td>
	<td>Es liegt ein funktionierendes Plugin vor.</td>
</tr>
</tbody>
</table>

      
Licence
=======

<p>The plugin Advanced Pagination is under <a href="http://opensource.org/licenses/MIT" title="Opensource.org" target="_blank">MIT licence</a> and <a href="http://www.gnu.org/licenses/gpl.txt" target="_blank" title="GNU GENERAL PUBLIC LICENSE Version 3">GNU licence</a>.</p>
<p>Copyright &#169; 2014 Konrad Rolof</p>
