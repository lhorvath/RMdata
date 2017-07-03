
# Repository of data sets and scripts
------------
- candidate-level data set for UK elections 2010, 2015, 2017
- constituency-level data set UK elections 2010, 2015, 2017

CANDIDATE-LEVEL DATA SET
------------

<table class="table table-striped">
<thead>
<tr>
<th>variable</th>
<th>description</th>
<th>source</th>
<th>provisional?</th>
</tr>
</thead>
<tbody>
<tr>
<td>ons_id</td>
<td></td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>Party</td>
<td></td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>Candidate Name</td>
<td></td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>fname</td>
<td>C's first name(s)</td>
<td></td>
<td></td>
</tr>
<tr>
<td>lname</td>
<td>C's last name</td>
<td></td>
<td>NO</td>
</tr>
<tr>
<td>Constituency</td>
<td></td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>Votes</td>
<td></td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>Share</td>
<td>C's vote share</td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>Position</td>
<td>C's result in race</td>
<td>gov.uk</td>
<td>NO</td>
</tr>
<tr>
<td>year</td>
<td>Election year</td>
<td></td>
<td></td>
</tr>
<tr>
<td>woman</td>
<td>C is a woman</td>
<td>various sources*</td>
<td>2010: YES;<BR> 2015: NO;<BR> 2017: YES</td>
</tr>
<tr>
<td>former_mp</td>
<td>C is incumbent</td>
<td>2010: missing**;<BR> 2015: <a href="http://www.data.parliament.uk/dataset/general-election-2015">http://www.data.parliament.uk/</a>; <BR> 2017: based on 2015 Position</td>
<td>NO</td>
</tr>
</tbody>
</table>

```
# variables
-variables-----|-description-|-source-|-provisional?-|
 ons_id        |                | gov.uk | NO           |
 Party         |                | gov.uk | NO           |
 Candidate Name|                | gov.uk | NO           |
 fname         | First name     |        |              |
 lname         | Last  name     |        |              |
 Constituency  | Press associ.  | BES    | NO           |
 Votes         |                | gov.uk | NO           |
 Share         | C's vote share | gov.uk | NO           |
 Position      | C pos.in race  | gov.uk | NO           |
 year          | Election year  | gov.uk | NO           |
 woman         | C is a woman   | gov.uk | NO           |
 former_mp     | C is incumbent | gov.uk | NO           |
 inc           |                | gov.uk | NO           |
 
 
# methodology
```
