Download Link: https://assignmentchef.com/product/solved-cmsc409-project-4-feature-vector
<br>



<ol>

 <li>Download and unzip “Project4_sentences.zip” and “Project4_code.zip” files.</li>

</ol>

A set of sentences is given in the file “<em>sentences.txt</em>”. Each sentence is a line in the file. Create the feature vector by writing a program that applies the following text mining techniques to this set of sentences.

<ol>

 <li>Tokenize sentences</li>

 <li>Remove punctuation and special characters</li>

 <li>Remove numbers</li>

 <li>Convert upper-case to lower-case</li>

 <li>Remove stop words. A set of stop words is provided in the file “<em>txt</em>”</li>

 <li>Perform stemming. Use the Porter stemming code provided in the file “<em>txt</em>”</li>

 <li>Combine stemmed words.</li>

 <li>Extract most frequent words.</li>

</ol>

<strong>Provide the feature vector in your report.</strong>

<strong>Note</strong>:

The feature vector contains unique sets of words that appear in the set of sentences provided.

The file “<em>Project4_code.zip</em>” contains implementations of the Porter Stemmer in several languages. You can use any version of the code provided (provided versions of the code are Java, Matlab, Python, and C). Make sure you rename your file accordingly. More source code for the Porter Stemmer can be found here: <a href="https://tartarus.org/martin/PorterStemmer/">http://tartarus.org/martin/PorterStemmer/</a>

Page 1 of 2

<strong>CMSC 409: Artificial Intelligence</strong>

<h1>Project 4</h1>

<ol start="2">

 <li>Using the feature vector generated in first task, write a program that generates the Term Document Matrix (TDM) for ALL the sentences in “<em>txt</em>”, similar to TDM below. Example TDM</li>

</ol>

<table width="629">

 <tbody>

  <tr>

   <td width="102"><strong>Keyword set</strong></td>

   <td width="122">anonymous</td>

   <td width="141">identify</td>

   <td width="136">car</td>

   <td width="129"><strong>…</strong></td>

  </tr>

  <tr>

   <td width="102"><strong>Sentence 1</strong></td>

   <td width="122">1</td>

   <td width="141">4</td>

   <td width="136">3</td>

   <td width="129">…</td>

  </tr>

  <tr>

   <td width="102"><strong>Sentence 2</strong></td>

   <td width="122">2</td>

   <td width="141">0</td>

   <td width="136">1</td>

   <td width="129">…</td>

  </tr>

  <tr>

   <td width="102">…..</td>

   <td width="122">…</td>

   <td width="141">…</td>

   <td width="136">…</td>

   <td width="129">…</td>

  </tr>

  <tr>

   <td width="102"><strong>Sentence 20</strong></td>

   <td width="122">2</td>

   <td width="141">0</td>

   <td width="136">0</td>

   <td width="129">…</td>

  </tr>

 </tbody>

</table>




<ol>

 <li><strong>Provide the TDM in your report.</strong></li>

 <li>For each of the text mining steps (A to H), explain why they are used, and what sort of information is lost while applying each of the text-mining steps.</li>

 <li>Write a program implementing the clustering algorithm of your choice (WTA or FCAN). Apply that algorithm to TDM to group similar sentences together.

  <ol>

   <li>How many clusters/topics have you identified?</li>

   <li>What drives the dimensionality of TDM? What can you do to reduce that dimensionality? Does the order of data being fed to algorithm matter?</li>

   <li>Show and comment the results.</li>

  </ol></li>

</ol>


