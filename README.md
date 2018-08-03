<p><strong>1. Add Gradle dependency:</strong></p>
<pre style="padding-left: 30px;">implementation group: 'org.apache.commons', name: 'commons-text', version: '1.4'</pre>

<p><strong>2. Convert</strong></p>
<pre style="padding-left: 30px;">String <span style="color: #000080;">city</span> = "A\\u011fr\\u0131";<br /><br />String <span style="color: #000080;">fixedCity</span> = StringEscapeUtils.unescapeJava(city);<br /><br /><span style="color: #808080;"><em>fixedCity = Ağrı</em></span></pre>
<p>&nbsp;</p>
