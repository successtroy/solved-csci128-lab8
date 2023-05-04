Download Link: https://assignmentchef.com/product/solved-csci128-lab8
<br>
<strong>Initial Setup: </strong>Create​ a directory to store the code of this lab exercise. Follow the instructions below to start a web server at the newly created directory.

Running web server on <strong>Mac</strong>​ using command:​

python3 -m http.server [port-number] -d [web-directory]

For example, to run on port 50000 and directory /Users/jsmith/Desktop/myweb

python3 -m http.server 50000 -d “/Users/jsmith/Desktop/myweb”

The website will be at the address: http://localhost:50000/​

Running web server on <strong>Windows</strong>​ using command:​

python -m http.server [port-number] -d [web-directory]

For example, to run on port 8000 and directory “C:UsersjsmithDesktopmy web”

python -m http.server 8000 -d “C:UsersjsmithDesktopmy web”

<h1>The website will be at the address: http://localhost:8000/​</h1>




Here is a sample of XML code with stylesheet:

&lt;?xml version=”1.0″ ?&gt;

&lt;?xml-stylesheet type=”text/xsl” href=”FILE-NAME-HERE.xsl”?&gt; …XML code here…

Here is a sample of XSLT code:




<table width="624">

 <tbody>

  <tr>

   <td width="624">&lt;?xml version=”1.0″ ?&gt; &lt;xsl:stylesheet   version=”1.0″   xmlns:xsl=”http://www.w3.org/1999/XSL/Transform”   xmlns=”http://www.w3.org/1999/xhtml”&gt; &lt;xsl:output method=”xml” indent=”yes” encoding=”UTF-8″/&gt; &lt;xsl:template match=”/PUT-THE-ROOT-ELEMENT-HERE”&gt; &lt;html&gt;&lt;head&gt;&lt;title&gt;XSLT example&lt;/title&gt;&lt;/head&gt; &lt;body&gt;HELLO WORLD&lt;/body&gt;&lt;/html&gt; &lt;/xsl:template&gt;&lt;/xsl:stylesheet&gt;</td>

  </tr>

 </tbody>

</table>

<strong>            </strong>

<strong>Question 1.</strong> Given the following XML code containing an exam result:​

&lt;?xml version=”1.0″?&gt;

&lt;result ref=”10007629P”&gt;

&lt;contestantId&gt;00025142&lt;/contestantId&gt;

&lt;examId&gt;KB253DG&lt;/examId&gt;

&lt;score&gt;156&lt;/score&gt;

&lt;band&gt;C&lt;/band&gt;

&lt;digitalSignature&gt;a720cf8e23bc1256bce2&lt;/digitalSignature&gt; &lt;/result&gt;

Write the XML code into the file question1.xml​ and use the stylesheet question1.xsl​ to produce the following output:<strong>        </strong>

<strong>Question 2.</strong> Similar to question 1, write the XML code into the file question2.xml​ and use the stylesheet question2.xsl​ to produce the following output:​<strong>        </strong>

<strong>Question 3.</strong> Given the following XML code containing subject enrolment statistics:​

&lt;?xml version=”1.0″?&gt;

&lt;audit campus=”Woolloomooloo” year=”2000″ session=”A”&gt;




&lt;subject sid=”0769642″&gt;

&lt;code&gt;MATH101&lt;/code&gt;

&lt;title&gt;Calculus&lt;/title&gt;

&lt;statistics&gt;

&lt;enrol&gt;170&lt;/enrol&gt;

&lt;withdrawn&gt;31&lt;/withdrawn&gt;

&lt;/statistics&gt;

&lt;/subject&gt;




&lt;subject sid=”1734231″&gt;

&lt;code&gt;MATH234&lt;/code&gt;

&lt;title&gt;Abstract Algebra&lt;/title&gt;

&lt;statistics&gt;

&lt;enrol&gt;40&lt;/enrol&gt;

&lt;withdrawn&gt;15&lt;/withdrawn&gt;

&lt;/statistics&gt;

&lt;/subject&gt;

&lt;/audit&gt;

Write the XML code into the file question3.xml​ and add a few more subject data. Use the stylesheet question3.xsl​ to produce the following output:​