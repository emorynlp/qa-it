# qa-it
<h2>Non-referential It for Question Answer Pairs</h2>

<li> This is a corpus created for 
<a href="http://aclweb.org/anthology/P/P16/P16-3020.pdf">
<em> QA-It: Classifying Non-Referential It for Question Answer Pairs </em><strong>In Proceedings of the ACL Student Research Workshop (ACL-SRW'16)</strong>
</a> </li>
<li>
	The corpus is in CSV format.
</li>

<hr>
<h3> Format </h3>
<ul>
	<li> One document size represents 10 word tokens. </li>
	<li> The Question &amp Answer Pair is delimited by <strong> &gt&gt&gt&gt&gt </strong> </li>
	<li> Each instance of <em>it</em> is wrapped by <strong> [[ it_# ]] </strong> </li>
	<li> Column(s) after <strong> Question & Answer Pair </strong> is the classification of <em>it</em> using the following rules. </li>
</ul>
<h4> Rules </h4>
<ol>
	<li> Non-Referential (Pleonastic) </li>
	<li> Referential - Nominal </li>
	<li> Referential - Noun </li>
	<li> Error </li>
</ol>

<table>
	<tr>
		<th> Corpus Type </th>
		<th> Genre </th>
		<th> Document Size</th>
		<th> Total count of <em>it</em> instances in this pair</th>
		<th> Question & Answer Pair </th>
		<th> Classification </th>
	</tr>
	
</table>


