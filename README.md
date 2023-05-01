Download Link: https://assignmentchef.com/product/solved-cinf362-week-2-wireframes-and-intro-to-html
<br>
<strong>Agenda</strong>

<ul>

 <li>Wireframes

  <ul>

   <li>What are they?</li>

   <li>How do we create them?</li>

   <li>Wireframes Exercise</li>

  </ul></li>

 <li>Introduction to HTML

  <ul>

   <li>What is HTML?</li>

   <li>Creating/Viewing our first page</li>

   <li>HTML Exercise</li>

  </ul></li>

 <li>Next Week</li>

</ul>







<h2>Wireframes</h2>

<strong>What are they?</strong>

Wireframes are used to assist with the planning and development of websites, applications, etc. Rather than beginning with coding, a developer might use a wireframe to plan out the different components and how they will interact. For web development, wireframes are used to provide a visual structure of the website’s layout. Wireframes allow us to do this by separating content from styles. We can then focus on content and where it’s placed rather than worry about aesthetics like color.




<u>Additional Reading</u>

<ul>

 <li><a href="https://www.webopedia.com/TERM/W/wireframe.html">https://www.webopedia.com/TERM/W/wireframe.html</a></li>

 <li><a href="https://webdesign.tutsplus.com/articles/a-beginners-guide-to-wireframing--webdesign-7399">https://webdesign.tutsplus.com/articles/a-beginners-guide-to-wireframing–webdesign-7399</a></li>

 <li><a href="https://www.slideshare.net/folletto/introduction-to-building-wireframes/68-Lets_sketch_Wordpresscom_homepage">https://www.slideshare.net/folletto/introduction-to-building-wireframes/68-Lets_sketch_Wordpresscom_homepage</a> (Only slides 1-28)</li>

</ul>




<strong>How do we create them?</strong>

Wireframes are created by drawing out the structure of the product you intend to build. This can be done on paper, markerboard, online, and even in a local image editor. I’ve listed some tools that should be a good start if you don’t know where to begin. There are many others out there are free or cost money, but the ones below don’t require logins and are capable enough for our purposes.




<u>Online Editors</u>

<ul>

 <li><a href="https://wireframe.cc/">https://wireframe.cc/</a></li>

 <li><a href="https://www.gliffy.com/examples/wireframes">https://www.gliffy.com/examples/wireframes</a></li>

</ul>




<u>Draw/Print</u>

<ul>

 <li><a href="http://media.konigi.com/tools/graphpaper/pdf/konigi-wireframe-gray.pdf">http://media.konigi.com/tools/graphpaper/pdf/konigi-wireframe-gray.pdf</a></li>

 <li><a href="http://gridzzly.com/">http://gridzzly.com/</a></li>

 <li><a href="https://sneakpeekit.com/">https://sneakpeekit.com/</a></li>

</ul>

<u> </u>

<u>Image Editors</u>

<ul>

 <li><a href="https://www.getpaint.net/index.html">https://www.getpaint.net/index.html</a></li>

 <li><a href="https://www.gimp.org/">https://www.gimp.org/</a></li>

</ul>




<strong>Wireframes Exercise</strong>

Look at the list of potential websites listed below. Think about the kind of content you might find on those websites. Based on your thoughts and some light research, create a wireframe for one page from each website. This might include the home page, about page, blog post/listing page, contact page, etc. Use your creativity and the tools listed above (others are cool too) to create 3 separate wireframes. If you choose to draw your wireframe, take a picture and submit it to Blackboard. Links or direct file uploads are fine for this assignment. Just attach them with your submission.

If you need to explain anything in the wireframe, feel free to add a little paragraph along with your submission. Make sure to let me know which wireframe your writeup refers to so I don’t misunderstand anything. Submit all 3 of your links/files to Blackboard under this week’s lecture notes or in the Assignments folder. It will be called “Wireframes Exercise.”

<ol>

 <li>Personal resume website</li>

 <li>Bakery website</li>

 <li>Wildlife conservation/blogging website</li>

</ol>




<u>Tips</u>

<ul>

 <li>Find similar websites for inspiration</li>

 <li>Use <a href="https://www.wirify.com/">https://www.wirify.com/</a> to see how potential wireframes would look</li>

 <li>Label your boxes, write an x to signify an image, don’t write too much text</li>

 <li>No colors except black, white, or greys</li>

 <li>Explain things as needed</li>

 <li>Don’t worry about perfection, this is mostly a thinking/planning exercise</li>

 <li>Submit only 1 wireframe for each one</li>

</ul>




<h2>Introduction to HTML</h2>

<strong>What is HTML?</strong>

There are three major components of front-end web development:




<ol>

 <li>Structure</li>

 <li>Style</li>

 <li>Interactivity</li>

</ol>




HTML represents the structure of the page. It is based on the concept of tags that “markup” the document. Those tags allow the browser to interpret .html files and present them correctly to users on the page. Each tag begins and ends with an angled bracket.




<strong>&lt;p class=“para”&gt;This is a paragraph.&lt;/p&gt;</strong>




The bold text directly above is an HTML element. Elements are made up of tags, attributes, values, and content. The &lt;p&gt; and &lt;/p&gt; part are the starting and ending tags. “class” is the attribute name and “para” is the value you are providing to the attribute. Everything between the tags is the content.




In HTML, some tags require ending tags and others do not. &lt;p&gt;, &lt;div&gt;, &lt;span&gt;, &lt;strong&gt;, &lt;em&gt;, and many others require a closing tag which looks like the following “&lt;/tag&gt;” where tag is replaced by the name of the tag. &lt;br&gt;, &lt;hr&gt;, and &lt;img&gt; are examples of tags that don’t require a closing tag and can be written without any slashes.




Tags in HTML are often nested within each other. An example is &lt;ul&gt; and &lt;li&gt;. &lt;ul&gt; is unordered list and &lt;li&gt; is list item and they appear together as shown below.




&lt;ul&gt;

&lt;li&gt;Item 1&lt;/li&gt;

&lt;li&gt;Item 2&lt;/li&gt;

&lt;/ul&gt;




Tags can be nested over and over but ideally, you want your HTML to be tidy and should code in a way that allows you to keep your code uncluttered. If you open a tag inside of another one, you MUST close that tag before close the tag it is inside.




You can view a page’s HTML at any time by right-clicking the page and selecting view source. F12 (on PCs) also opens up that browser’s Inspect Element feature which allows you to select individual parts on the page and see what kind of CSS has been applied.




<u>Additional Reading</u>

Tutorials

<a href="https://www.htmldog.com/guides/html/">https://www.htmldog.com/guides/html/</a>

<a href="https://html.com/">https://html.com/</a> (Read up until “Our Other HTML Tutorials” and that should suffice)

<a href="https://www.codecademy.com/learn/learn-html">https://www.codecademy.com/learn/learn-html</a> (Interactive, full-blown tutorial – you DO NOT have to complete this but if you want to learn on the side, it helps)

<u> </u>

Reference Guides

<a href="https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5">https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5</a>

<a href="http://html5doctor.com/element-index/">http://html5doctor.com/element-index/</a>




I’ve also included a PowerPoint file on Blackboard which will help further explain HTML and demonstrate some best practices you should adopt moving forward.




<strong>Creating/Viewing our first page</strong>

Go to Blackboard and download the html-materials.zip file. Open index.html with a text editor of your choice. I personally prefer brackets.io since it is free and has many useful extensions but use whatever you are most comfortable with. Review the code inside, I have placed comments in the code to explain what each line does.




Between the body tags, add the following line of code:




&lt;p&gt;Hello World! My name is name.&lt;/p&gt;




Replace “name” with your actual name. After you are done, double-click the file to open it in your default web browser. You should see “Hello World! My name is Chris.” except my name will be replaced by yours. HTML doesn’t display the tags on the page, so we only see the text content between the tags. With this, you’ve successfully opened and edited a web page to include info about yourself. HTML is straight forward, only requiring that you learn which tag is used for what content.




<strong>HTML Exercise</strong>

Your task is to build a webpage based on requirements given to you. To get started, use the previously downloaded html-exercise.html file from Blackboard (also inside the html-materials.zip file) and open it up in a text editor. Add code to it as mentioned in the list below. Also, complete the research portion of it below the list. All code should be submitted as one file to Blackboard for credit. Go under today’s lecture notes or the Assignments folder. The submission area will be titled “HTML Exercise,” you can upload your .html file there.




<ol>

 <li>Add an h1 tag with “HTML Exercise” between it</li>

 <li>Add a p tag beneath that with a sentence or two about a place you would like to go to for vacation. When you mention the name of the place, wrap it in a strong tag so that it appears bold on the page.</li>

 <li>Create an <strong>unordered list</strong> with 5 foods you like. Use em tags to make two of the items on that list appear italicized on the page.</li>

 <li>Create an <strong>ordered list</strong> with your three favorite websites. Use the a tag to hyperlink those websites so I can visit them.</li>

 <li>Add an hr tag beneath the ordered list so that a line appears next</li>

 <li>Follow the next set of instructions for a table</li>

</ol>




Look up the tags listed below and build a table based on them. The table will contain three columns in it. The first column should have the name of the tag, the second column will explain the purpose of the tag, and the third column will let us know if it is still in use. The possible values for the third column are Yes or NO with one of the following: “Not in use”, “Use CSS instead”, “New to HTML5”, “Not supported in HTML5”, or Replaced by &lt;tagname&gt;. A tag can have any number of these designations and I’ve provided an example below.




<table>

 <tbody>

  <tr>

   <td width="208"><strong>Name</strong></td>

   <td width="208"><strong>Purpose</strong></td>

   <td width="208"><strong>Still in Use?</strong></td>

  </tr>

  <tr>

   <td width="208">Center</td>

   <td width="208">A tag used to center align items it is wrapped around.</td>

   <td width="208">No – Use CSS</td>

  </tr>

  <tr>

   <td width="208">Embed</td>

   <td width="208">Defines a container for external applications (video, etc.)</td>

   <td width="208">Yes – New to HTML5</td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Font</li>

 <li>Aside</li>

 <li>Footer</li>

 <li>Strike</li>

 <li>Acronym</li>

 <li>Canvas</li>

 <li>Dir</li>

 <li>Applet</li>

 <li>Nav</li>

 <li>B</li>

 <li>Header</li>

 <li>Section</li>

 <li>Div</li>

</ul>




<h2>Next Week</h2>

We will learn more about HTML including validation, semantic markup, and how to make our web pages “live” so that users across the internet can access them.