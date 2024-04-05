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

<p>I utilized a text-encoding web-program named Leaf-Writer to annotate all potentially perplexing terms within the text. Subsequently, I linked each of these annotations to my comprehensive reference list, ensuring accessibility and clarity for all readers. Ultimately, my objective with this project is to encode all 33 books in the Dear Canada series, furnishing them with links to this reference list. This will facilitate effortless access to unfamiliar terms, thereby aiding individuals in expanding their knowledge and understanding.</p>

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

<p>Based on what we learned in class and what I’ve been reading so far about text encoding I’ll want to use XML and there was a web-program we looked at in class called <a href="https://leaf-writer.leaf-vre.org/">Leaf-Writer</a> that should simplify the tagging.</p> 

<p>XML will allow me to add more data to the texts. I should be able to pull all that data and use it for further analysis. I will need to follow the <a href="https://tei-c.org/">Text Encoding Initiative Guidelines</a>(TEI) in order to open any XML files in <a href="https://leaf-writer.leaf-vre.org/">Leaf-Writer</a>.</p>

<h3>March 22nd, 2024</h3>

<p>So after a fairly frustrating couple of days, I have finally properly formatted my XML to open in <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a>. There was likely a better way to do this but there is something fun about trial and error.</p>

<p>I just copied a TEI header from the example we used in class and plugged in the information for my project. The next part to figure out was how best to format the Plain-Text into something more organised. I opted to divide the book into diary entries and then paragraphs. This was fairly straightforward, although, once again there was likely a better way than manually copying and pasting each paragraph into its own tag…</p>

<p>Let’s just all remember that I am a beginner here.</p>

<p>By the end of the day, after several painful hours of troubleshooting, I have finally, successfully managed to open my XML of a Prairie as Wide as the Sea in <a href=“https://leaf-writer.leaf-vre.org/">Leaf-Writer</a>.</p>
