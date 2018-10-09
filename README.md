<div dir="ltr" style="text-align: left;" trbidi="on">
JAVA provides excellent support and a rich set of libraries to parse, modify or inquire XML documents. This tutorial will explain various types of Java-based parsers with examples in a simple and intuitive way. We will also learn how to convert an object to/from XML using JAXB API in Java.<br>
<br>
<div class="separator" style="clear: both; text-align: center;">
<a href="https://1.bp.blogspot.com/-BHKqU1lx7SE/W7mfG6xQ4mI/AAAAAAAAEL0/LwzWPVBdkPM6h0PoDRWlYU9yu2egdyuuQCLcBGAs/s1600/java-xml-tutorial.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="201" data-original-width="671" src="https://1.bp.blogspot.com/-BHKqU1lx7SE/W7mfG6xQ4mI/AAAAAAAAEL0/LwzWPVBdkPM6h0PoDRWlYU9yu2egdyuuQCLcBGAs/s1600/java-xml-tutorial.png"></a></div>
<br>
In Java JDK, two built-in XML parsers are available – DOM and SAX, both have their pros and cons. Here are few examples to show how to create, modify and read an XML file with Java DOM, SAX, JDOM.<br>
<h2 style="text-align: left;">
DOM XML Parser</h2>
DOM Parser is the easiest Java XML parser to learn. DOM parser loads the XML file into memory and we can traverse it node by node to parse the XML. DOM Parser is good for small files but when file size increases it performs slow and consumes more memory.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-read-xml-file-in-java-dom-parser.html" target="_blank">How to read XML file in Java - DOM Parser</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; This article shows you how to create XML file in Java using DOM XML Parser<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-create-xml-file-in-java-dom-parser.html" target="_blank">How to Create XML File in Java</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;This article explains how to use DOM Parser to create and write Object data to an XML file.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-modify-or-update-xml-file-in-java-dom-parser.html" target="_blank">How to Modify or Update XML File in Java</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Check out, DOM Parser can be used to modify existing XML data as well.<br>
<h2 style="text-align: left;">
SAX Parser</h2>
<div>
SAX parser is work differently with DOM parser, it does not load any XML document into memory and create some object representation of the XML document. Instead, the SAX parser use callback function (org.xml.sax.helpers.DefaultHandler) to informs clients of the XML document structure.</div>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-read-xml-file-in-java-sax-parser.html" target="_blank">How to Read XML File in Java- SAX Parser</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Learn how to create our Callback Handler class to read XML file to list of Objects using SAX.<br>
<h2 style="text-align: left;">
JDOM Parser</h2>
<div>
JDOM provides a great Java XML parser API to read, edit and write XML documents easily. JDOM provides wrapper classes to chose your underlying implementation from SAX Parser, DOM Parser, STAX Event Parser, and STAX Stream Parser.</div>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-read-xml-file-in-java-jdom-parser.html" target="_blank">How to Read XML File in Java- JDOM Parser</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;In this post, we will learn how to read XML file to Object using JDOM XML Parser.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-update-or-modify-xml-file-in-java-jdom-parser.html" target="_blank">How to Update or Modify XML file in Java – JDOM Parser</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;In this article, we will learn how to update the existing XML file in Java using JDOM.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-create-xml-file-in-java-jdom-parser.html" target="_blank">How to Create XML File in Java – JDOM Parser</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;In this article, we will learn how to create XML file in Java using JDOM Parser.<br>
<h2 style="text-align: left;">
JAXB</h2>
<div>
<div>
Java Architecture for XML Binding (JAXB) is a Java standard that defines how Java objects are converted from and to XML. It uses a standard set of mappings. JAXB defines an API for reading and writing Java objects to and from XML documents.</div>
</div>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-convert-java-object-to-xml-jaxb-marshalling.html" target="_blank">How to Convert Java Object to XML - JAXB Marshalling</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; In this article, we will learn how to convert a Java object to XML and write to an external file.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/how-to-convert-xml-to-java-object-jaxb-unmarshalling.html" target="_blank">How to Convert XML to Java Object - JAXB Unmarshalling</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; In this article, we will learn how to convert an XML to Java object using JAXB API.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/10/jaxb-tutorial.html" target="_blank">JAXB Tutorial</a></li>
</ul>
&nbsp; &nbsp; &nbsp; &nbsp; In this tutorial, we will learn how to convert Java objects from and to XML using JAXB API.<br>
<h2 style="text-align: left;">
References</h2>
<ul style="text-align: left;">
<li><a href="https://javaee.github.io/jaxb-v2/doc/user-guide/release-documentation.html" target="_blank">JAXB User Guide(Release Doc)</a></li>
<li><a href="http://www.jdom.org/" target="_blank">JDOM Parser Doc</a></li>
<li><a href="https://docs.oracle.com/javase/1.5.0/docs/api/org/w3c/dom/package-summary.html" target="_blank">DOM XML parser documentation</a></li>
<li><a href="http://java.sun.com/j2se/1.5.0/docs/api/org/xml/sax/package-summary.html" target="_blank">SAX Parser Doc</a></li>
</ul>
<blockquote class="tr_bq">
Learn all Java/J2EE Tutorial on <a href="http://www.javaguides.net/p/top-java-tutorials.html">All Java Tutorials</a></blockquote>
</div>
</div>
