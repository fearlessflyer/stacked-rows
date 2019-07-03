# ARCHIVED / DISCONTINUED
I've decided to discontinue the development of this plugin to concentrate my efforts on other projects.

# stacked-rows
A short and simple jQuery plugin that will fix your tables in mobile view. New rows of your original data is created and displayed through media queries

![alt tag](http://michaelsoriano.com/wp-content/uploads/2015/07/stacked-rows1.jpg)

<h3>How to use:</h3>

Just like a regular jQuery plugin, you need to have jQuery included in page to use. Then simply call inside a document .ready() with your selectors and options included. 

<h3>Options</h3>

You can pass several options when calling the plugin. Check the table below for an explanation of how the options work. 

<table class="table table-bordered table-striped responsive-utilities" style="margin-top:25px; margin-bottom:30px;">
<thead>
<tr>
<th>Option</th>
<th>Type</th>
<th>Description</th>
<th class="hidden-xs">Default Value</th>
</tr>
</thead>
<tbody>
<tr>
<th><code>classPrefix</code></th>
<td class="is-visible">string</td>
<td>class prefix for CSS styling</td>
<td class="is-hidden hidden-xs">sr</td>
</tr>
<tr>
<th><code>firstRowHeader</code></th>
<td class="is-hidden">bool</td>
<td>does first row of table a heading?</td>
<td class="is-visible hidden-xs">true</td>
</tr>
<tr>
<th><code>showLabels</code></th>
<td class="is-hidden">bool</td>
<td>show labels (column names) in mobile?</td>
<td class="is-hidden hidden-xs">true</td>
</tr> 
<th><code>altRowStyle</code></th>
<td class="is-hidden">bool</td>
<td>add a class for alternating rows</td>
<td class="is-hidden hidden-xs">true</td>
</tr> 
</tbody>
</table>

For more details, read my post here: http://michaelsoriano.com/better-html-table-responsive-view-jquery-plugin/
