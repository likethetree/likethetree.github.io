---
# The homepage has been modified to show static text instead of posts.
# To return to the original homepage change "layout: home" and remove all other content.

layout: home
title: Home
nav_order: 1
---
<style>
 a:link {
  color: mediumSeaGreen;
  background-color: transparent;
  text-decoration: none;
}
  a:visited {
  color: darkSeaGreen;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: darkSeaGreen;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
</style> 

<p>This project has three primary objectives. Firstly, it aims to establish a comprehensive reference index dedicated to archiving historical or less common terminology found within the texts. These terms may be unfamiliar to readers due to their historical contexts or regional disparities in language usage. Secondly, the project endeavours to meticulously map out all the locations referenced in the texts (mapping hopefully coming soon). Thirdly, it seeks to construct a dynamic timeline encompassing the events depicted in the books. To accomplish these goals, I employed a range of digital humanities methodologies, spanning from XML text encoding to HTML website design.</p>

<p>I utilized a text-encoding web-program named <a href="https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> to annotate all keywords, dates, and locations within the text. Subsequently, I linked each of the keywords to a comprehensive reference list, ensuring accessibility and clarity for all readers. Ultimately, my objective with this project is to encode all 33 books in the Dear Canada series, furnishing them with links to the <a href="https://likethetree.github.io/reference/">reference list</a>. This will facilitate effortless access to unfamiliar terms, thereby aiding individuals in expanding their knowledge and understanding.</p>

<p>XML and other text encoding languages play a crucial role in enhancing textual information by leveraging the way computers read and store data. While dealing with a vast amount of physical text poses significant challenges, digital tools offer numerous possibilities for textual analysis and manipulation. With these tools, intricate tasks that were once daunting become more manageable, opening up new avenues for exploring and understanding text on a deeper level. XML files can also easily be converted into spreadsheets using programs like Excel or other similar software. This conversion process facilitates further exploration and analysis of the data contained within the XML files. By converting XML data into a spreadsheet format, users can manipulate and analyze the information more intuitively, allowing for deeper insights and uncovering patterns that might not be immediately apparent from the raw XML data. This flexibility enhances the usability and accessibility of the data, making it easier to extract valuable insights and information.</p>

<img src="/images/Twenty-First Century Woman.jpg"> 

<h3>February 14th, 2024</h3>

<p>Happy Valentine’s Day!</p>

<p>I have an idea.</p>

<p>In class we’re learning about various ways to do computational analysis and data visualisation. Most of the examples we’ve looked at involve fictional books and now I’m wondering what I could do with the Dear Canada books. First I’ll need digital copies of all of them. I have all the physical books but unfortunately they are at home in Calgary. Dad can probably help me with digital copies, I’ll ask him. </p>

<h3>Later</h3>

<p>Success. I have all the epubs and I converted them all to plain-text with a <a href="https://pypi.org/project/epub2txt/">python script</a> dad found. Now I can use them for pretty much anything. Cool!</p>

<h3>March 6th, 2024</h3>

<p>We learned about xml text-encoding and the Data-Sitters Club a while ago and I think I wanna try something similar. Basically, what they’ve done, is gone through the Baby-Sitters Club series and done computational-text-analysis to pull data from the stories — pretty cool stuff. I wonder if it’s possible to do the same with the Dear Canada books. It would be so neat to do some sort of computational analysis on them and figure out a way to visualise and map them out.</p>

<p>Since I now have all the books as plain-text files, it shouldn’t be that complicated, right?</p>

<h3>March 20th, 2024</h3>

<p>It is, perhaps, more complicated than I thought but I’m learning as I go! I don’t think I’ll be able to do what I want with all the books within the time I have left but I can definitely start with one. I think “A Prairie as Wide as the Sea” may be one of the very first Dear Canada books I read. It is at least the one I am most familiar with as it is set in the same general location and time period as the museum I used to work at. Just prairie things.</p>

<p>I have a slightly different plan now. I would like to go through the books to tag all the dates, locations, and keywords. With the dates I’ll be able to plot the books onto a timeline. With the locations I’ll be able to map them out, and with the keywords I can create a reference list with definitions that offer more context.</p>

<p>Based on what we learned in class and what I’ve been reading so far about text encoding I’ll want to use XML and there was a web-program we looked at in class called <a href="https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> that should simplify the tagging process for me.</p> 

<p>XML will allow me to add more data to the texts. I should be able to pull all that data and use it for further analysis. I will need to follow the <a href="https://tei-c.org/">Text Encoding Initiative Guidelines</a>(TEI) in order to open any XML files in <a href="https://leaf-writer.leaf-vre.org/">Leaf-Writer</a>.</p>

<h3>March 22nd, 2024</h3>

<p>So after a fairly frustrating couple of days, I have finally properly formatted my XML to open in <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a>. There was likely a better way to do this but there is something fun about trial and error.</p>

<p>I just copied a TEI header from the example we used in class and plugged in the information for my project. The next part to figure out was how best to format the Plain-Text into something more organised. I opted to divide the book into diary entries and then paragraphs. This was fairly straightforward, although, once again there was likely a better way than manually copying and pasting each paragraph into its own tag…</p>

<p>Let’s just all remember that I am a beginner here.</p>

<p>By the end of the day, after several painful hours of troubleshooting, I have finally, successfully managed to open my XML of a Prairie as Wide as the Sea in <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a>.</p>

<h3>March 23rd, 2024</h3>

<p>I guess tagging in <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> is pretty fun. Their tools make it super easy to add all the dates, locations, and keywords. All I have to do is reread a good book and tag all the important bits I want to be able to use. <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> also has access to several databases with contextual information.</p>

<p>Now I kind of want to see if I can make my own database and link to definitions of some of the more specific keywords there rather than using Wikidata, VIAF, or DBPEDIA. <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> allows users to add their own reference links. Guess I am now building a website…</p> 

<h3>March 24th, 2024</h3>

<p>I've been playing around with the github website we built in class a couple weeks ago. I think I'll use that as the source for my reference list. Now time to learn how to build something more comprehensive for this project. <a href=https://www.w3schools.com/html/default.asp>W3Schools</a> has a lot of tutorials that were very helpful.</p>

<p>As I go through the text and add more tags, I'm thinking about how I want to format a reference list. It should have an index and photos to make it easier to navigate. Also, these books are technically meant for kids so I will need to make all the definitions accessible and understandale for them.</p>

<h3>March 28th, 2024</h3>

<p>My <a href="https://likethetree.github.io/reference/">reference list</a> is coming along well! By following the <a href=https://www.w3schools.com/html/default.asp>W3Schools</a> tutorials, I've been able to curate and format a reference list. I've just been pulling photos from google, and explanations and definitions from wikipedia which I feed into chatgpt to reword them for children. I try to find photos of items from the 20s since "A Prairie as Wide as the Sea" is set in 1926. I then plug that into the github website builder with some HTML tags and it's starting to look pretty good!</p>

<p>I finished up with the tagging in <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> and went back to replace some of the reference links with links to my new website. I'll still use some of the Wikidata links for some of the more common and still modernly used terms.</p>

<h3>Bibliography</h3>

<p>Fitzpatrick, Kathleen. “The Humanities, Done Digitally.” Debates in the Digital Humanities, 2012. https://dhdebates.gc.cuny.edu/read/untitled-88c11800-9446-469b-a3be-3fdb36bfbd1e/section/65e208fc-a5e6-479f-9a47-d51cd9c35e84#ch02.</p>  

<p>Schriebman, Susan. “Digital Scholarly Editing” | Literary Studies in the Digital Age.” MLACommons, 2013. https://dlsanthology.mla.hcommons.org/digital-scholarly-editing/.</p>

