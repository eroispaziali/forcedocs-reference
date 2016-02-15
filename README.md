# Forcedocs Reference Sheet
This is reference sheet for [Forcedocs](https://www.forcedocs.com), a tool to generate, host and browse documentation for applications built on the Force.com platform.

## Classes and Triggers
<table>
<thead>
<tr>
<th>Tag</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>@description</code></td>
<td>Describe what your class or trigger does. The tag must be followed by a free text description.</td>
</tr>
<tr>
<td><code>@author</code></td>
<td>To specify who contributed to a class or a trigger use the <code>@author</code> tag, followed by a GitHub username. If the code is coauthored just use the tag multiple times.</td>
</tr>
<tr>
<td><code>@deprecated</code></td>
<td>You can use this tag to call out that a piece of code should no longer be used. You can add an optional comment.</td>
</tr>
</tbody>
</table>

## Methods
<table>
<thead>
<tr>
<th>Tag</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>@description</code></td>
<td>Describe what your method does. The tag must be followed by a free text description.</td>
</tr>
<tr>
<td><code>@author</code></td>
<td>To specify who contributed to this method with the <code>@author</code> tag, followed by a GitHub username. If the code is coauthored just use the tag multiple times.</td>
</tr>
<tr>
  <td><code>@return</code></td>
  <td>Describe what your method returns.</td>
</tr>
<tr>
  <td><code>@param</code></td>
  <td>Describe a parameter of a method. The <code>@param</code> tag is followed by the name of the parameter and then followed by a description.</td>
</tr>
<tr>
  <td><code>@throws</code></td>
  <td>Call out any relevant exceptions that can be thrown by the method. You can specify multiple <code>@throws</code> for each method by using the tag multiple times.</td>
</tr>
<tr>
  <td><code>@deprecated</code></td>
  <td>Note that a piece of code should no longer be used. You can add an optional comment.</td>
</tr>
</tbody>
</table>


