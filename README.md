<div align="center">

## Beginners guide to ASP filled with examples\!


</div>

### Description

This is example for anyone who is just starting ASP. These are easy examples to understand. A live example of this can be found here:

http://www.irideforlife.com/go?x=view

If you like it the please vote!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[snowboardr](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/snowboardr.md)
**Level**          |Beginner
**User Rating**    |4.5 (86 globes from 19 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__4-33.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/snowboardr-beginners-guide-to-asp-filled-with-examples__4-7323/archive/master.zip)





### Source Code

<html>
<head>
<title>Jason's Tutorial..</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
</head>
<body bgcolor="#CCCCCC" text="#000000">
<table width="43%" border="0" cellspacing="0" cellpadding="0" height="25" align="center">
 <tr>
  <td height="13"><font face="Verdana, Arial, Helvetica, sans-serif"><b>ASP
   - Active Server Pages </b></font></td>
 </tr>
</table>
<table width="73%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Outputing
   text</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="69">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
    &quot;Hello World&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> Hello World</td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="71%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Outputing
   text a second way</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="69">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
    (&quot;Hello World&quot;)</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> Hello World</td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="74%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>&lt;html&gt;
   &amp; ASP</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="69">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
    (&quot;&lt;b&gt;Hello World&lt;b&gt;&quot;)</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> <b>Hello World</b></td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="73%" border="1" cellspacing="0" cellpadding="0" height="107" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Writing
   Date / Time</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
    NOW</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> 3/9/2002 8:15:19 PM </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="74%" border="1" cellspacing="0" cellpadding="0" height="107" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Comenting
   your code:</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
    &quot;Hello World&quot;</font> <font color="#339933">'Outputes &quot;Hello
    world&quot; </font></p>
   <p><font color="#339933"> Note: A comment has a single quote in front of
    it. (')</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> Hello World </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="75%" border="1" cellspacing="0" cellpadding="0" height="107" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b><i>If
   </i>Statement</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">If &quot;2&quot;
    = &quot;2&quot; Then</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&quot;True&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">End if</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> True</td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="76%" border="1" cellspacing="0" cellpadding="0" height="107" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b><i>If
   </i>...Else </b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">If &quot;2&quot;
    = &quot;3&quot; Then</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&quot;True&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">Else</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&quot;Its
    2!&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">End if</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> Its 2!</td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="77%" border="1" cellspacing="0" cellpadding="0" height="107" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b><a name="Q"></a>Request.QueryString</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font color="#009933"> '<font face="Verdana, Arial, Helvetica, sans-serif" size="2">If
    our QueryString matches what we want then we can show what we want</font></font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">If Request.QueryString(&quot;display&quot;)
    = &quot;message&quot; then</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
    &quot;My message&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">End if</font></p>
   <p>&nbsp;</p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> My message </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="78%" border="1" cellspacing="0" cellpadding="0" height="107" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b><a name="Q2"></a>More
   then 1 Request.QueryString</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font color="#009933"> '<font face="Verdana, Arial, Helvetica, sans-serif" size="2">If
    our QueryString matches what we want then we can show what we want</font></font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">If Request.QueryString(&quot;display&quot;)
    = &quot;test&quot; then</font></p>
   <blockquote>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
     &quot;QueryString &quot;test&quot; worked!&quot;</font></p>
   </blockquote>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">End if</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">If Request.QueryString(&quot;show&quot;)
    = &quot;test&quot; then<br>
    </font></p>
   <blockquote>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
     &quot;QueryString &quot;test2&quot; worked!&quot;</font></p>
   </blockquote>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">End if</font></p>
   <p><b><font face="Verdana, Arial, Helvetica, sans-serif" size="2">Note:</font></b></p>
   <p>'<font face="Verdana, Arial, Helvetica, sans-serif" size="2"> Your linke
    will look something like this when clicked:</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">' default.asp?display=test&amp;show=&quot;test&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">' &amp; Seperates
    QueryStrings in a link.</font></p>
   <p>&nbsp;</p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF"> QueryString test worked!QueryString test2 worked! </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="79%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Include
   file </b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="69">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p>&lt;!--#include file=&quot;myfile.asp&quot;--&gt;</p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="35">
   <blockquote>
    <p>Includes a file into your page. This makes it easy to have a bunch
     of code that you use all the time on one page, but yet you don't have
     to have a big long page of it. You can also just update the file with
     all your code, and then each page that has the include will have the
     update as well.</p>
   </blockquote>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="80%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Write
   a form in ASP.</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="69">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;form name=&quot;&quot;form1&quot;&quot; method=&quot;&quot;post&quot;&quot;
    action=&quot;&quot;default.asp&quot;&quot;&gt;&quot;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;input type=&quot;&quot;text&quot;&quot; name=&quot;&quot;textfield&quot;&quot;&gt;&quot;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;input type=&quot;&quot;submit&quot;&quot; name=&quot;&quot;Submit&quot;&quot;
    value=&quot;&quot;Submit&quot;&quot;&gt;&quot;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;/form&gt;&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#009933">'Note:
    Each quote inside the Response.write quotes must have double quotes!</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#009933">'Example:
    Response.write &quot;Hello there &quot;&quot;Welcome&quot;&quot; to my
    site!&quot; </font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="35">
   <blockquote>
    <p> Live Examples Here : <a href="http://www.irideforlife.com/go?x=view">http://www.irideforlife.com/go?x=view</a></p>
   </blockquote>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="82%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b><a name="FM"></a>Show
   your form results on the same page..</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="69">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;form name=&quot;&quot;form<b>2</b>&quot;&quot; method=&quot;&quot;post&quot;&quot;
    action=&quot;&quot;default.asp<font color="#FF0000"><b><font color="#0033CC">?display=formresults</font></b></font>&quot;&quot;&gt;&quot;&quot;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;input type=&quot;<font color="#FF0000"><font color="#000000">text</font></font>&quot;&quot;
    name=&quot;&quot;<font color="#FF0000"><b>areform</b></font>&quot;&quot;&gt;&quot;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;input type=&quot;&quot;submit&quot;&quot; name=&quot;&quot;Submit&quot;&quot;
    value=&quot;&quot;Submit&quot;&quot;&gt;&quot;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">
    &quot;&lt;/form&gt;&quot;</font></p>
   <p><font size="2" face="Verdana, Arial, Helvetica, sans-serif">If Request.QueryString(&quot;display&quot;)
    = &quot;formresults&quot; then</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">(Request.Form(&quot;<font color="#FF0000"><b>areform</b></font>&quot;))</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">End if</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt; </font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="35">
   <blockquote>
    <p>Live Examples Here : <a href="http://www.irideforlife.com/go?x=view">http://www.irideforlife.com/go?x=view</a></p>
    </blockquote>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="80%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b><a name="form"></a>Dim
   to memory</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="161">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#009933">'
    Use this to store anything you want for use later also known as a <b><font color="#000000">string</font></b></font></p>
   <p><font size="2" face="Verdana, Arial, Helvetica, sans-serif">MyText =
    &quot;Hello World!&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font size="2" face="Verdana, Arial, Helvetica, sans-serif">(MyText)</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt; </font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="1">
   <p> Hello World!</p>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="82%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><b><font face="Verdana, Arial, Helvetica, sans-serif" size="2">Replace
   something in a string</font></b></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="161">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">MyString
    = &quot;Jason is the best programmer in the world!&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">NewString
    = Replace(MyString, &quot;best&quot;,&quot;&lt;b&gt;worst&lt;/b&gt;&quot;)</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#009933">'<b><font color="#000000">Notes:</font></b>
    <b>YourNewString</b> = Replace(<b>String to look in</b>, &quot;<b>Word
    that you want to look for</b>&quot;, &quot;<b>Repalce with this</b>&quot;
    ) </font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2">(NewString)</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt; </font></p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="1">
   <p> Jason is the <b>worst</b> programmer in the world! </p>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="88%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><b><font face="Verdana, Arial, Helvetica, sans-serif" size="2">Select
   Combo <a name="combo"></a></font></b></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="161">
   <p>&nbsp;</p>
   <p><font color="#009933" size="2">'This shows how to have the right one
    in the combo selected, depending on which they slected so even if the
    refresh it will stay on the right combo. </font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;form
    name=&quot;form1&quot;&gt;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">&lt;select
    name=&quot;jumpmenu&quot; onChange=&quot;MM_jumpMenu('parent',this,0)&quot;&gt;<br>
    &lt;option value=&quot;default.asp?link=test1&quot; <font color="#FF0000">&lt;%
    If <font color="#990000">Request.QueryString</font>(&quot;link&quot;)
    = &quot;test1&quot; then Response.write &quot;selected&quot; %&gt;</font>&gt;test1&lt;/option&gt;<br>
    &lt;option value=&quot;default.asp?link=test2&quot;<font color="#FF0000">&lt;%
    If <font color="#990000">Request.QueryString</font>(&quot;link&quot;)
    = &quot;test2&quot; then Response.write &quot;selected&quot; %&gt;</font>&gt;test2&lt;/option&gt;<br>
    &lt;option value=&quot;default.asp?link=test3&quot; <font color="#FF0000">&lt;%
    If <font color="#990000">Request.QueryString</font>(&quot;link&quot;)
    = &quot;test3&quot; then Response.write &quot;selected&quot; %&gt;</font>&gt;test3&lt;/option&gt;<br>
    &lt;/select&gt;<br>
    &lt;/form&gt;</font><br>
   </p>
   <p>&nbsp;</p>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="77%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Math:</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="161">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">a
    = &quot;1&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">b
    = &quot;2&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">c
    = a * b <font color="#009933">' Multiplication</font></font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">(c)</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">
    &quot;&lt;br&gt;&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">a
    = &quot;1&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">b
    = &quot;2&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">If
    a &lt; b Then </font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#993333">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">
    &quot;yes b is greater then a&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">End
    if</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
   <p>&nbsp;</p>
  </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="1">
   <p> 2<br>
    yes b is greater then a <br>
   </p>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="77%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>Aray:</b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="215">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">&lt;%</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">MyArayString
    = &quot;a b c | d | e f | g h i j | k l m n | o p | q r s | t u v | w
    y x z&quot;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">sAray
    = Split(MyArayString, &quot;|&quot;) <font color="#009933">'Split up our
    data in between | |</font></font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#0000FF">For
    each</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">
    x <font color="#0000FF">in sAray</font></font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#CC0000">Response.write</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">
    x</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#0000FF">Next</font><font face="Verdana, Arial, Helvetica, sans-serif" size="2" color="#000000">
    <font color="#009933">'Goto next one until it there are no more</font></font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">%&gt;</font></p>
   </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="2">
   <p> <br>
    a b c d e f g h i j k l m n o p q r s t u v w y x z <br>
   </p>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<table width="43%" border="1" cellspacing="0" cellpadding="0" height="94" align="center" bordercolor="#999999" bgcolor="#CCCCCC">
 <tr>
  <td bgcolor="#CCCCCC" height="23"><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b></b></font></td>
 </tr>
 <tr>
  <td bgcolor="#eeeeee" height="161">
   <p align="center"><font size="2" face="Verdana, Arial, Helvetica, sans-serif">Leave
    comments below.</font></p>
   <p align="center"><font face="Verdana, Arial, Helvetica, sans-serif" size="2">Ill
    probably continue on ths lesson if someone wants me to.</font></p>
   </td>
 </tr>
 <tr>
  <td bgcolor="#FFFFFF" height="1">
   <p>&nbsp; </p>
  </td>
 </tr>
</table>
<p>&nbsp;</p>
<p>&nbsp;</p>
</body>
</html>

