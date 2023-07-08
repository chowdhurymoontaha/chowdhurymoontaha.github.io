---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<code style="color:black;">Publication updates can be found on my <a style ="color:#800080;" href="https://scholar.google.com/citations?user=eYJP5BUAAAAJ&hl=en"><em>[Google Scholar]</em></a> profile.</code>


## 2022
---------
<!-- Paper 02 -->
📌 [<span style="color:Blue">**Automatic back transliteration of Romanized Bengali (Banglish) to Bengali**</span>](https://link.springer.com/article/10.1007/s42044-022-00122-9)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar Shibli</strong>, Md. Tanvir Rouf Shawon, Anik Hassan Nibir, Md. Zabed Miandad, and Nibir Chandra Mandal</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Journal:</strong><em> Iran Journal of Computer Science</em></font> ([Iran J Comput Sci](https://www.springer.com/journal/42044))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#iran2022_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://shahariar-shibli.github.io/files/IRAN2022/Banglish_to_Bangla.pdf)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/shahariar-shibli/Automatic-Back-Transliteration-of-Romanized-Bengali-Banglish-to-Bengali)] [<a style="color:red;" href="#" onclick="$('#iran2022_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="iran2022_bib" class="bib" style="display:none;">
	<pre>
		@article{shibli2022automatic,
		  title={Automatic back transliteration of Romanized Bengali (Banglish) to Bengali},
		  author={Shibli, GM Shahariar and Shawon, Md Tanvir Rouf and Nibir, Anik Hassan and Miandad, Md Zabed and Mandal, Nibir Chandra},
		  journal={Iran Journal of Computer Science},
		  pages={1--12},
		  year={2022},
		  publisher={Springer}
		}
	</pre>
</div>

<div id="iran2022_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			Back transliteration of Romanized Bengali to Bengali is the process of converting text written in the Latin alphabet back into the 
			Bengali script. This is often done in order to improve the readability of Bengali text for Bengali speakers using a simple rules-based 
			system, or an interactive transliteration tool. There are many ways to back transliterate from Romanized Bengali to Bengali, but most 
			of them are either grapheme or phoneme based. This paper introduces a unique pipeline that uses nine open source back transliteration 
			tools to automatically back transliterate Romanized Bengali to Bengali. The pipeline consists of seven steps: (1) processing the 
			Romanized Bengali input; (2) acquiring human transliteration for performance comparison; (3) employing transliteration tools; (4) 
			generating candidate transliterations; (5) post-processing the candidate transliterations; (6) selecting best candidate transliteration, 
			and (7) evaluating the quality of the transliterations through several performance metrics. Experimental results reveal that our approach 
			produced the highest BLEU-1 score of 81.28, BLEU-2 score of 60.75, BLEU-3 score of 44.45, BLEU-4 score of 30.46, and the lowest average 
			Word Error Rate and Word Information Lost of 29.21 and 43.68, respectively, on 1000 Romanized Bengali texts. In terms of recall, 
			we achieved a Rouge-L score of 0.7190.
		</font>
	</p>
</div>

<!-- Paper 01 -->
📌 [<span style="color:Blue">**Urgent Text Detection in Bengali Language Based on Boosting Techniques**</span>](https://link.springer.com/chapter/10.1007/978-981-19-2445-3_49)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Rafsan Rahman, Tamanna Nazmin, Noor Nafeur Rahman, Miyad Bhuiyan, <strong style="color:green">G. M. Shahariar</strong>, and Faisal Muhammad Shah</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> International Conference on Fourth Industrial Revolution and Beyond</em></font> ([ICFIRB 2022](https://link.springer.com/book/10.1007/978-981-19-2445-3))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icfirb2022_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/364138051_Urgent_Text_Detection_in_Bengali_Language_Based_on_Boosting_Techniques)] [<a style="color:red;" href="#" onclick="$('#icfirb2022_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="icfirb2022_bib" class="bib" style="display:none;">
	<pre>
		@InProceedings{10.1007/978-981-19-2445-3_49,
			author="Rahman, Rafsan
			and Nazmin, Tamanna
			and Rahman, Noor Nafeur
			and Bhuiyan, Miyad
			and Shahariar, G. M.
			and Shah, Faisal Muhammad",
			title="Urgent Text Detection in Bengali Language Based on Boosting Techniques",
			booktitle="Proceedings of International Conference on Fourth Industrial Revolution and Beyond 2021 ",
			year="2022",
			publisher="Springer Nature Singapore",
			address="Singapore",
			pages="697--709",
			isbn="978-981-19-2445-3"
		}
	</pre>
</div>

<div id="icfirb2022_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			This paper presents a learning approach on a unique dataset formulated by authors that detects urgent texts 
			from the posts on social media platforms in Bengali language. It is difficult to keep track of every information 
			we go through social media. In the collision of numerous posts, it is easy to miss information that is urgent. 
			In this advanced era of machine learning, detecting urgent texts among thousands of posts would be much easier 
			if we can implement a model that can filter the urgent text out of them. Therefore, we propose an approach that 
			can identify any type of urgent texts from public posts by leveraging a manually constructed dataset that is fully 
			human annotated. Apart from traditional machine learning classifiers, we applied boosting algorithms in our 
			proposed method in addition. Experimentally, a significant increase in accuracy has been noticed by boosting 
			weak learners. Support Vector Machine (SVM) achieved 80.9% accuracy where gradient boosting outperformed the 
			traditional approach with 82% accuracy while detecting urgent texts in Bengali language.
		</font>
	</p>
</div>


