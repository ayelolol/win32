﻿---
title: JET_INDEXLIST members (Microsoft.Isam.Esent.Interop)
TOCTitle: JET_INDEXLIST members
ms:assetid: AllMembers.T:Microsoft.Isam.Esent.Interop.JET_INDEXLIST
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.jet_indexlist_members(v=EXCHG.10)
ms:contentKeyID: 55103660
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
---

# JET\_INDEXLIST members

Include protected members  
Include inherited members  

Information about a temporary table containing information about all indexes for a given table.

The [JET\_INDEXLIST](dn335123\(v=exchg.10\).md) type exposes the following members.

## Constructors

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn335166(v=exchg.10).md">JET_INDEXLIST</a></td>
<td></td>
</tr>
</tbody>
</table>


Top

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335125(v=exchg.10).md">columnidcColumn</a></td>
<td>Gets the columnid of the column in the temporary table which stores the number of columns in the index key. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335126(v=exchg.10).md">columnidcEntry</a></td>
<td>Gets the columnid of the column in the temporary table which stores the number of entries in the index. This value is not current and is only is updated by &quot;Api.JetComputeStats&quot;. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335127(v=exchg.10).md">columnidcKey</a></td>
<td>Gets the columnid of the column in the temporary table which stores the number of unique keys in the index. This value is not current and is only is updated by &quot;Api.JetComputeStats&quot;. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335129(v=exchg.10).md">columnidcoltyp</a></td>
<td>Gets the columnid of the column in the temporary table which stores the column type of the column being indexed. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335130(v=exchg.10).md">columnidcolumnid</a></td>
<td>Gets the columnid of the column in the temporary table which stores the columnid of the column being indexed. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335167(v=exchg.10).md">columnidcolumnname</a></td>
<td>Gets the columnid of the column in the temporary table which stores the grbit that apply to the indexed column. See <a href="hh579266(v=exchg.10).md">IndexKeyGrbit</a>. The column is of type <a href="hh577895(v=exchg.10).md">Text</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335168(v=exchg.10).md">columnidCp</a></td>
<td>Gets the columnid of the column in the temporary table which stores the code page of the indexed column. The column is of type <a href="hh577895(v=exchg.10).md">Short</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335136(v=exchg.10).md">columnidcPage</a></td>
<td>Gets the columnid of the column in the temporary table which stores the number of pages in the index. This value is not current and is only is updated by &quot;Api.JetComputeStats&quot;. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335169(v=exchg.10).md">columnidgrbitColumn</a></td>
<td>Gets the columnid of the column in the temporary table which stores the grbit that apply to the indexed column. See <a href="hh579266(v=exchg.10).md">IndexKeyGrbit</a>. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335134(v=exchg.10).md">columnidgrbitIndex</a></td>
<td>Gets the columnid of the column in the temporary table which stores the the grbits used on the index. See <a href="hh578433(v=exchg.10).md">CreateIndexGrbit</a>. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335170(v=exchg.10).md">columnidiColumn</a></td>
<td>Gets the columnid of the column in the temporary table which stores the index of of this column in the index key. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335138(v=exchg.10).md">columnidindexname</a></td>
<td>Gets the columnid of the column in the temporary table which stores the name of the index. The column is of type <a href="hh577895(v=exchg.10).md">Text</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335171(v=exchg.10).md">columnidLangid</a></td>
<td>Gets the columnid of the column in the temporary table which stores the language id (LCID) of the index. The column is of type <a href="hh577895(v=exchg.10).md">Short</a>.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335172(v=exchg.10).md">columnidLCMapFlags</a></td>
<td>Gets the columnid of the column in the temporary table which stores the unicode normalization flags for the index. The column is of type <a href="hh577895(v=exchg.10).md">Long</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335173(v=exchg.10).md">cRecord</a></td>
<td>Gets the number of records in the temporary table.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292128.pubproperty(EXCHG.10).gif" title="Public property" alt="Public property" /></td>
<td><a href="dn335174(v=exchg.10).md">tableid</a></td>
<td>Gets tableid of the temporary table. This should be closed when the table is no longer needed.</td>
</tr>
</tbody>
</table>


Top

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn335165(v=exchg.10).md">ToString</a></td>
<td>Returns a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf">String</a> that represents the current <a href="dn335123(v=exchg.10).md">JET_INDEXLIST</a>. (Overrides <a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">Object.ToString()</a>.)</td>
</tr>
</tbody>
</table>


Top

## See also

#### Reference

[JET\_INDEXLIST class](dn335123\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
