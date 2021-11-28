# 2021-22-Term1-Fairness-in-Socio-technical-Systems

This repository is for archiving course materials for IS457: Fairness in Socio-technial Systems (AY2021-22 Term1), School of Computing and Information Systems, Singapore Management University.

Instructor: [Associate Professor. KWAK Haewoon](https://soda-labo.github.io/) [(@haewoon)](https://twitter.com/haewoon)

# Synopsis
We interact with a variety of services and systems in our daily lives. While manual labors still take some part in those systems, some other parts become more and more automated by artificial intelligence (AI). In general, we might expect that those systems treat users fairly. If the system uses AI that is built on big data and complex algorithms, such expectation would be strengthened. Compared to human labor that might involve subjective decision-making, algorithmic systems are expected to objectively work and treat users fairly. However, in recent years, there are raising concerns about the potential harms of those systems, which are rooted in biases embedded in socio-technical systems. The inherent opaque nature of AI systems makes the problem worse.

For example, YouTube recommends next videos when a video is finished playing. Those recommendations, on the one hand, are helpful to find interesting videos from a tremendous number of YouTube videos, but on the other hand, it is often unclear how or why the video is recommended. What happens if some biases exist in the recommendation algorithm, such as favoring videos with a specific (political) view? No matter whether those biases are intentional or unintentional, users would be exposed to a certain set of videos and are likely to be influenced by them.  

YouTube is only one out of many examples because AI systems are becoming pervasive these days. In various areas, including healthcare, hiring, financial service, ads, policymaking, and internet services, AI systems are actively used. Thus, it is crucial to ensure that those systems are working fairly without any potential biases. It might be overlooked that the biases are embedded not only in the AI systems but also in established processes or human operators within the systems.

The goal of this course is to provide students with an extensive understanding of diverse concepts of fairness and bias in socio-technical systems through examples across diverse domains, from healthcare to internet search. Then, students will learn how to audit practical systems in terms of fairness and bias through recent case studies. The course also aims to understand public concerns related to AI systems and help students to deeply think about ethical AI within multiple social contexts.



# Prerequisite
- IS111 Intro to Programming / CS101 Programming Fundamentals
- IS217 Analytics Foundations / MGMT108 Intro to Business Analytics / CS105 Statistical Thinking for Data Science



# Topics to be Covered
| Week | Description | Slides | Group activity |
| --- | --- | :---: | --- |
| **W1** | Introduction<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/blob/main/Week%201%20-%20Introduction.png?raw=true" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%201%20-%20Introduction.pdf) | 1. [Colab - Twitter's image cropping algorithm](https://github.com/haewoon/lab-image-crop-analysis) <br/> 2. Algorithmic curations in your favorite apps |
| **W2** | Case studies of measuring fairness and biase (I)<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/blob/main/Week%202%20-%20Case%20studies%20of%20measuring%20fairness%20and%20bias%20(I).png?raw=true" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%202%20-%20Case%20studies%20of%20measuring%20fairness%20and%20bias%20(I).pdf) | 1. Google Teachable Machine <br/>2. High- and low-resource hospitals' EHRs|
| **W3** | Case studies of measuring fairness and biase (II)<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/blob/main/Week%203%20-%20Case%20studies%20of%20measuring%20fairness%20and%20bias%20(II).png?raw=true" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%203%20-%20Case%20studies%20of%20measuring%20fairness%20and%20bias%20(II).pdf) | 1. WooClap: Ethical considerations in AI Healthcare <br/>2. Gender and racial stereotypes in image search|
| **W4** | Auditing algorithms<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/blob/main/Week%204%20-%20Auditing%20algorithms.png?raw=true" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%204%20-%20Auditing%20algorithms.pdf) | 1. Design your audit study |
| **W5** | Bias in data and machine learning models (I)<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/blob/main/Week%205%20-%20Bias%20in%20data%20and%20machine%20learning%20models%20(I).png?raw=true" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%205%20-%20Bias%20in%20data%20and%20machine%20learning%20models%20(I).pdf) | 1. Sharing your story about various cognitive biases|
| **W6** | Project consultation | | |
| **W7** | Project idea pitching | | |
| **W8** | Recess week | | |
| **W9** | Bias in data and machine learning models (II) <br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/blob/main/Week%209%20-%20Bias%20in%20data%20and%20machine%20learning%20models%20(II).png?raw=true" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%209%20-%20Bias%20in%20data%20and%20machine%20learning%20models%20(II).pdf) | [1. Inappropriate synsets in ImageNet](https://github.com/haewoon/lab-imagenet-synsets)<br/>[2. Bias in word embeddings](https://github.com/haewoon/lab-bias-in-word-embeddings) |
| **W10** | Interpretability of algorithmic systems <br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%2010%20-%20Interpretability%20of%20algorithmic%20systems.png" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%2010%20-%20Interpretability%20of%20algorithmic%20systems.pdf) | [1. Colab - Interpretable machine learning](https://github.com/haewoon/lab-interpretable-machine-learning) |
| **W11** | Fairness mechanisms<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%2011%20-%20Fairness%20mechanisms.png" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%2011%20-%20Fairness%20mechanisms.pdf) | 1. Error metrics in context<br/>2. WooClap: Is this algorithm fair? |
| **W12** | HCI perspective of fairness + Project consultation<br/><img src="https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%2012%20-%20HCI%20perspective%20of%20fairness.png" width="480"> | [PDF](https://github.com/haewoon/2021-22-Term1-Fairness-in-Socio-technical-Systems/raw/main/Week%2012%20-%20HCI%20perspective%20of%20fairness.pdf) | 1. Fairness metric in skin cancer prediction<br/>2. WooClap: Trade-off between accuracy and fairness | 
| **W13** | Project presentation | | |
| **W14** | Study week | | |
| **W15** | Final exam | | |



# (!Optional!🙏) References
Reading is completely **optional**. The main findings of the below papers are summarized during the lecture.   
If you are interested in more, please check the papers. 

For your convenience, I mark reading materials as one of three levels: I (Introductory), M (interMediate), and A (Advanced).  
- I: Introductory materials are typically news articles, YouTube videos, or technical blog articles that are easy to follow.  They introduce a new concept or a case for those who are not familiar with this domain. 
- M: Intermediate materials are typically research papers but (I guess) most of the students can understand without much difficulties. 
- A: Advanced materials are research papers that I can recommend you reading introduction and discussion. For example, papers that are theory-drive, use many jargons (e.g., medical or legal terms), are based on some advanced concepts (language models), fall in this category. It would be great if you can understand a whole, but it might not be easy for junior undergrads.

And some materials are marked as R (recommended). 

Note that SMU students can access to many news websites (e.g., The New York Times, Wall Street Journal, etc.) for free through the library website.  
A detailed registration process will be available on the library website.

**W1: Introduction**
- (I) [Friedman, Batya, and Helen Nissenbaum. "Bias in computer systems." ACM Transactions on Information Systems (TOIS) 14.3 (1996): 330-347.](https://dl.acm.org/doi/10.1145/230538.230561)
- (R/I) [Amazon Changed Search Algorithm in Ways That Boost Its Own Products, WSJ, 2019](https://www.wsj.com/articles/amazon-changed-search-algorithm-in-ways-that-boost-its-own-products-11568645345)
- (I) [Else, Holly. "How to banish manels and manferences from scientific meetings." Nature 573.7773 (2019): 184-187.](https://www.nature.com/articles/d41586-019-02658-6)
- (I) [Speedy Neural Networks for Smart Auto-Cropping of Images, Twitter Engineering blog, 2018](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2018/Smart-Auto-Cropping-of-Images)
- (R/I) [Sharing learnings about our image cropping algorithm, Twitter Engineering blog, 2021](https://blog.twitter.com/engineering/en_us/topics/insights/2021/sharing-learnings-about-our-image-cropping-algorithm)
- (I) [Facebook Apologizes After A.I. Puts ‘Primates’ Label on Video of Black Men, The New York Times, 2021](https://www.nytimes.com/2021/09/03/technology/facebook-ai-race-primates.html)

**W2: Case studies of measuring fairness and biase (I) - Healthcare, Criminal system**
- (M) [Price, I. I., and W. Nicholson. "Medical AI and contextual bias." (2019).](https://papers.ssrn.com/sol3/Papers.cfm?abstract_id=3347890)
- (R/I) [IDx-DR - How It Works, IDx (YouTube)](https://www.youtube.com/watch?v=dWiF8THxf7Q)
- (M) [Cirillo, Davide, et al. "Sex and gender differences and biases in artificial intelligence for biomedicine and healthcare." NPJ digital medicine 3.1 (2020): 1-11.](https://www.nature.com/articles/s41746-020-0288-5)
- (A) [Martin, Lisa A., Harold W. Neighbors, and Derek M. Griffith. "The experience of symptoms of depression in men vs women: analysis of the National Comorbidity Survey Replication." JAMA psychiatry 70.10 (2013): 1100-1106.](https://jamanetwork.com/journals/jamapsychiatry/fullarticle/1733742)
- (A) [Feiner, John R., John W. Severinghaus, and Philip E. Bickler. "Dark skin decreases the accuracy of pulse oximeters at low oxygen saturation: the effects of oximeter probe type and gender." Anesthesia & Analgesia 105.6 (2007): S18-S23.](https://pubmed.ncbi.nlm.nih.gov/18048893/)
- (R/I) [Obermeyer, Ziad, et al. "Dissecting racial bias in an algorithm used to manage the health of populations." Science 366.6464 (2019): 447-453.](https://www.science.org/doi/10.1126/science.aax2342)
- (A) [Larrazabal, Agostina J., et al. "Gender imbalance in medical imaging datasets produces biased classifiers for computer-aided diagnosis." Proceedings of the National Academy of Sciences 117.23 (2020): 12592-12594.](https://www.pnas.org/content/117/23/12592)
- (I) [Machine Bias, ProPublica, 2016](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
- (R/I) [How predictive policing software works, The Verge, 2016 (YouTube)](https://www.youtube.com/watch?v=YxvyeaL7NEM)
- (I) [Lum, Kristian, and William Isaac. "To predict and serve?." Significance 13.5 (2016): 14-19.](https://rss.onlinelibrary.wiley.com/doi/full/10.1111/j.1740-9713.2016.00960.x)

**W3: Case studies of measuring fairness and biase (II) - Hiring, Urban mobility, Immigration system, Web search, Wikipedia**
- (M) [Peng, Andi, et al. "What you see is what you get? the impact of representation criteria on human bias in hiring." Proceedings of the AAAI Conference on Human Computation and Crowdsourcing. Vol. 7. No. 1. 2019.](https://ojs.aaai.org/index.php/HCOMP/article/view/5281)
- (R/I) [Amazon scraps secret AI recruiting tool that showed bias against women, Reuters, 2018](https://www.reuters.com/article/us-amazon-com-jobs-automation-insight-idUSKCN1MK08G)
- (M) [Lambrecht, Anja, and Catherine Tucker. "Algorithmic bias? An empirical study of apparent gender-based discrimination in the display of STEM career ads." Management science 65.7 (2019): 2966-2981.](https://pubsonline.informs.org/doi/abs/10.1287/mnsc.2018.3093)
- (R/I) [We tried the AI software companies like Goldman Sachs and Unilever use to analyze job applicants, Business Insider, 2017 (YouTube)](https://www.youtube.com/watch?v=QfuGRCmXmCs)
- (I) [A face-scanning algorithm increasingly decides whether you deserve the job, The Washington Post, 2019](https://www.washingtonpost.com/technology/2019/10/22/ai-hiring-face-scanning-algorithm-increasingly-decides-whether-you-deserve-job/)
- (I) [Heaven, Douglas. "Why Faces Don't Always Tell the Truth About Feelings." Nature 578.7796 (2020): 502-504.](https://www.nature.com/articles/d41586-020-00507-5)
- (I) [Buolamwini, Joy, and Timnit Gebru. "Gender shades: Intersectional accuracy disparities in commercial gender classification." Conference on fairness, accountability and transparency. PMLR, 2018.](http://proceedings.mlr.press/v81/buolamwini18a.html?mod=article_inline)
- (A) [Hutchinson, Ben, et al. "Social Biases in NLP Models as Barriers for Persons with Disabilities." Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics. 2020.](https://aclanthology.org/2020.acl-main.487/)
- (I) [Illinois says you should know if AI is grading your online job interviews, Vox, 2020](https://www.vox.com/recode/2020/1/1/21043000/artificial-intelligence-job-applications-illinios-video-interivew-act)
- (I) [Uber seems to offer better service in areas with more white people. That raises some tough questions. The Washington Post, 2016](https://www.washingtonpost.com/news/wonk/wp/2016/03/10/uber-seems-to-offer-better-service-in-areas-with-more-white-people-that-raises-some-tough-questions/)
- (M) [Ge, Yanbo, et al. Racial and gender discrimination in transportation network companies. No. w22776. National Bureau of Economic Research, 2016.](https://www.nber.org/papers/w22776)
- (I) [Amazon Doesn’t Consider the Race of Its Customers. Should It?, Bloomberg, 2016](https://www.bloomberg.com/graphics/2016-amazon-same-day/)
- (I) [We won! Home Office to stop using racist visa algorithm, JCWI, 2020](https://www.jcwi.org.uk/news/we-won-home-office-to-stop-using-racist-visa-algorithm)
- (R/I) ['Highly concerning': picture books bias worsens as female characters stay silent, The Guardian, 2019](https://www.theguardian.com/books/2019/jun/13/highly-concerning-picture-books-bias-worsens-as-female-characters-stay-silent)
- (R/I) [Kay, Matthew, Cynthia Matuszek, and Sean A. Munson. "Unequal representation and gender stereotypes in image search results for occupations." Proceedings of the 33rd Annual ACM Conference on Human Factors in Computing Systems. 2015.](https://dl.acm.org/doi/10.1145/2702123.2702520)
- (I) [Wagner, Claudia, et al. "It's a man's Wikipedia? Assessing gender inequality in an online encyclopedia." Ninth international AAAI conference on web and social media. 2015.](https://arxiv.org/abs/1501.06307)
- (I) [Wade, Jess, and Maryam Zaringhalam. "Why we’re editing women scientists onto Wikipedia." Nature 14 (2018).](https://www.nature.com/articles/d41586-018-05947-8)
- (A) [Sun, Jiao, and Nanyun Peng. "Men Are Elected, Women Are Married: Events Gender Bias on Wikipedia." Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 2: Short Papers). 2021.](https://aclanthology.org/2021.acl-short.45/)
- (I) [Koenecke, Allison, et al. "Racial disparities in automated speech recognition." Proceedings of the National Academy of Sciences 117.14 (2020): 7684-7689.](https://www.pnas.org/content/117/14/7684)
- (I) [Jisun An and Haewoon Kwak. "Gender and racial diversity in commercial brands’ advertising images on social media." International Conference on Social Informatics. Springer, Cham, 2019.](https://arxiv.org/abs/1908.01352)

**W4: Auditing algorithms**
- (R/I) [Sandvig, Christian, et al. "Auditing algorithms: Research methods for detecting discrimination on internet platforms." Data and discrimination: converting critical concerns into productive inquiry 22 (2014): 4349-4357.](https://social.cs.uiuc.edu/papers/pdfs/ICA2014-Sandvig.pdf)
- (I) [Forget the Booze. The Mad Men's Best Friend Was SABRE, Wired, 2012](https://www.wired.com/2012/07/sabre/)
- (A) ["The Legal and Regulatory Implications of Airline Computer Reservation Systems." Harvard Law Review 103, no. 8 (1990): 1930-950. Accessed August 8, 2021.](https://www.jstor.org/stable/1341325?origin=crossref)
- (I) [Bertrand, Marianne, and Sendhil Mullainathan. "Are Emily and Greg more employable than Lakisha and Jamal? A field experiment on labor market discrimination." American economic review 94.4 (2004): 991-1013.](https://www.aeaweb.org/articles?id=10.1257/0002828042002561)
- (A) [The Belmont Report](https://www.hhs.gov/ohrp/regulations-and-policy/belmont-report/index.html)
- (M) [SMU’s Institutional Review Board](https://smu.sharepoint.com/sites/irb/)
- (I) [Scholar Sets Off Gastronomic False Alarm, The New York Times, 2001](https://www.nytimes.com/2001/09/08/nyregion/scholar-sets-off-gastronomic-false-alarm.html)
- (A) [Data Scraping Survives! (At Least for Now) Key Takeaways from 9th Circuit Ruling on the HIQ vs. Linkedin Case, The National Law Review, 2019](https://www.natlawreview.com/article/data-scraping-survives-least-now-key-takeaways-9th-circuit-ruling-hiq-vs-linkedin)
- (R/I) [How TikTok's Algorithm Figures You Out | WSJ (YouTube)](https://www.youtube.com/watch?v=nfczi2cI6Cs)
- (I) [Mikians, Jakub, et al. "Detecting price and search discrimination on the internet." Proceedings of the 11th ACM workshop on hot topics in networks. 2012.](https://dl.acm.org/doi/10.1145/2390231.2390245)
- (I) [On Orbitz, Mac Users Steered to Pricier Hotels, The Wall Street Journal](https://www.wsj.com/articles/SB10001424052702304458604577488822667325882)
- (I) [YouTube Regrets, Mozilla Foundation, 2021](https://foundation.mozilla.org/en/campaigns/regrets-reporter/findings/)
- (I) [Algorithms and Amplification: How Social Media Platforms’ Design Choices Shape Our Discourse and Our Minds, Subcommittee hearing (Fun to watch, 2:15:15~2:17:21)](https://www.judiciary.senate.gov/meetings/algorithms-and-amplification-how-social-media-platforms-design-choices-shape-our-discourse-and-our-minds)
- (M) [Ribeiro, Manoel Horta, et al. "Auditing radicalization pathways on YouTube." Proceedings of the 2020 conference on fairness, accountability, and transparency. 2020.](https://arxiv.org/abs/1908.08313)

**W5: Bias in data and machine learning models (I)**
- (I) [Tversky, Amos, and Daniel Kahneman. "Judgment under uncertainty: Heuristics and biases." science 185.4157 (1974): 1124-1131.](https://www.science.org/doi/10.1126/science.185.4157.1124)
- (I) [Want Less-Biased Decisions? Use Algorithms. Harvard Business Review, 2018](https://hbr.org/2018/07/want-less-biased-decisions-use-algorithms)
- (M) [Breiman, Leo. "Statistical modeling: The two cultures (with comments and a rejoinder by the author)." Statistical science 16.3 (2001): 199-231.](https://projecteuclid.org/journals/statistical-science/volume-16/issue-3/Statistical-Modeling--The-Two-Cultures-with-comments-and-a/10.1214/ss/1009213726.full)
- (R/A) [Barocas, Solon, and Andrew D. Selbst. "Big data's disparate impact." Calif. L. Rev. 104 (2016): 671. (Introduction and Chapter I)](https://www.californialawreview.org/wp-content/uploads/2016/06/2Barocas-Selbst.pdf)
- (I) [Untold History of AI: Algorithmic Bias Was Born in the 1980s, IEEE Spectrum, 2019](https://spectrum.ieee.org/untold-history-of-ai-the-birth-of-machine-bias)
- (I) [Bump App Detects Potholes, Alerts City Officials, Associated Press (YouTube)](https://www.youtube.com/watch?v=yxAYLA405pU)
- (I) [A 'Forgotten History' Of How The U.S. Government Segregated America, NPR](https://www.npr.org/2017/05/03/526655831/a-forgotten-history-of-how-the-u-s-government-segregated-america)

**W9: Bias in data and machine learning models (II)**
- (I) [The data that transformed AI research—and possibly the world, Quartz, 2017](https://qz.com/1034972/the-data-that-changed-the-direction-of-ai-research-and-possibly-the-world/)
- (R/I) [Yang, Kaiyu, et al. "Towards fairer datasets: Filtering and balancing the distribution of the people subtree in the imagenet hierarchy." Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency. 2020.](https://dl.acm.org/doi/abs/10.1145/3351095.3375709)
- (I) [The viral selfie app ImageNet Roulette seemed fun – until it called me a racist slur, The Guardian, 2019](https://www.theguardian.com/technology/2019/sep/17/imagenet-roulette-asian-racist-slur-selfie)
- (M) [Caliskan, Aylin, Joanna J. Bryson, and Arvind Narayanan. "Semantics derived automatically from language corpora contain human-like biases." Science 356.6334 (2017): 183-186.](https://www.science.org/doi/10.1126/science.aal4230)
- (I) [A robot wrote this entire article. Are you scared yet, human?, The Guardian, 2020](https://www.theguardian.com/commentisfree/2020/sep/08/robot-wrote-this-article-gpt-3)
- (A) [Mikolov, Tomas, et al. "Efficient estimation of word representations in vector space." arXiv preprint arXiv:1301.3781 (2013).](https://arxiv.org/abs/1301.3781)
- (A) [Bolukbasi, Tolga, et al. "Man is to computer programmer as woman is to homemaker? debiasing word embeddings." Advances in neural information processing systems 29 (2016): 4349-4357.](https://papers.nips.cc/paper/2016/hash/a486cd07e4ac3d270571622f4f316ec5-Abstract.html)
- (R/M) [Kiritchenko, Svetlana, and Saif Mohammad. "Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems." Proceedings of the Seventh Joint Conference on Lexical and Computational Semantics. 2018.](https://aclanthology.org/S18-2005/)
- (M) [Prabhu, Vinay Uday, and Abeba Birhane. "Large image datasets: A pyrrhic win for computer vision?." arXiv preprint arXiv:2006.16923 (2020).](https://arxiv.org/abs/2006.16923)

**W10: Interpretability of algorithmic systems**
- (M) [Miller, Tim. "Explanation in artificial intelligence: Insights from the social sciences." Artificial intelligence 267 (2019): 1-38.](https://www.sciencedirect.com/science/article/pii/S0004370218305988)
- (I) [Goodman, Bryce, and Seth Flaxman. "European Union regulations on algorithmic decision-making and a “right to explanation”." AI magazine 38.3 (2017): 50-57.](https://ojs.aaai.org/index.php/aimagazine/article/view/2741)
- (R/I) [Lipton, Zachary C. "The Mythos of Model Interpretability: In machine learning, the concept of interpretability is both important and slippery." Queue 16.3 (2018): 31-57.](https://dl.acm.org/doi/pdf/10.1145/3236386.3241340)
- (M) [Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. "" Why should i trust you?" Explaining the predictions of any classifier." Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining. 2016.](https://dl.acm.org/doi/abs/10.1145/2939672.2939778)
- (A) [Lundberg, Scott M., et al. "From local explanations to global understanding with explainable AI for trees." Nature machine intelligence 2.1 (2020): 56-67.](https://www.nature.com/articles/s42256-019-0138-9)
- (M) [Babic, Boris, et al. "Beware explanations from AI in health care." Science 373.6552 (2021): 284-286.](https://www.science.org/doi/abs/10.1126/science.abg1834)
- (A) [Wachter, Sandra, Brent Mittelstadt, and Chris Russell. "Counterfactual explanations without opening the black box: Automated decisions and the GDPR." Harv. JL & Tech. 31 (2017): 841.](https://arxiv.org/pdf/1711.00399.pdf)
- (M) [Lage, Isaac, et al. "Human evaluation of models built for interpretability." Proceedings of the AAAI Conference on Human Computation and Crowdsourcing. Vol. 7. No. 1. 2019.](https://ojs.aaai.org/index.php/HCOMP/article/download/5280/5132/8381)

**W11: Fairness mechanisms**
- (R/A) [Barocas, Solon, and Andrew D. Selbst. "Big data's disparate impact." Calif. L. Rev. 104 (2016): 671. (Chapter II)](https://www.californialawreview.org/wp-content/uploads/2016/06/2Barocas-Selbst.pdf)
- (M) [Mitchell, Margaret, et al. "Model cards for model reporting." Proceedings of the conference on fairness, accountability, and transparency. 2019.](https://arxiv.org/abs/1810.03993)
- (M) [Ian Foster, Rayid Ghani, Ron S. Jarmin, Frauke Kreuter and Julia Lane, "Big Data and Social Science: Data Science Methods and Tools for Research and Practice" (Chapter 11)](https://textbook.coleridgeinitiative.org/chap-bias.html)

**W12: HCI perspective of fairness**
- (I) [Burrell, Jenna, et al. "When users control the algorithms: values expressed in practices on twitter." Proceedings of the ACM on Human-Computer Interaction 3.CSCW (2019): 1-20.](https://dl.acm.org/doi/10.1145/3359240)
- (I) [Saha, Debjani, et al. "Measuring non-expert comprehension of machine learning fairness metrics." International Conference on Machine Learning. PMLR, 2020.](http://proceedings.mlr.press/v119/saha20c/saha20c.pdf)
- (R/I) [Srivastava, Megha, Hoda Heidari, and Andreas Krause. "Mathematical notions vs. human perception of fairness: A descriptive approach to fairness for machine learning." Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 2019.](https://dl.acm.org/doi/10.1145/3292500.3330664)
- (M) [Dodge, Jonathan, et al. "Explaining models: an empirical study of how explanations impact fairness judgment." Proceedings of the 24th international conference on intelligent user interfaces. 2019.](https://arxiv.org/abs/1901.07694)
- (M) [Lee, Michelle Seng Ah, and Jat Singh. "The landscape and gaps in open source fairness toolkits." Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems. 2021.](https://dl.acm.org/doi/10.1145/3411764.3445261)
- (M) [Veale, Michael, Max Van Kleek, and Reuben Binns. "Fairness and accountability design needs for algorithmic support in high-stakes public sector decision-making." Proceedings of the 2018 chi conference on human factors in computing systems. 2018.](https://dl.acm.org/doi/10.1145/3173574.3174014)

**WX: Re-imagning fairness**
- (M) [Parolin, Zachary, and Emma K. Lee. "Large socio-economic, geographic and demographic disparities exist in exposure to school closures." Nature human behaviour 5.4 (2021): 522-528.](https://www.nature.com/articles/s41562-021-01087-8)
- (R/I) [Sambasivan, Nithya, et al. "Re-imagining algorithmic fairness in india and beyond." Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency. 2021.](https://dl.acm.org/doi/10.1145/3442188.3445896)
- (M) [Krafft, P. M., et al. "Defining AI in policy versus practice." Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society. 2020.](https://dl.acm.org/doi/10.1145/3375627.3375835)
- (I) [Kalluri, Pratyusha. "Don't ask if artificial intelligence is good or fair, ask how it shifts power." Nature 583.7815 (2020): 169-169.](https://www.nature.com/articles/d41586-020-02003-2)
- (M) [Responses to Critiques on Machine Learning of Criminality Perceptions (Addendum of arXiv:1611.04135)](https://arxiv.org/abs/1611.04135)
- (M) [Horvitz, Eric, and Deirdre Mulligan. "Data, privacy, and the greater good." Science 349.6245 (2015): 253-255.](https://www.science.org/doi/10.1126/science.aac4520)
- (M) [Green, Ben. "Good” isn’t good enough." Proceedings of the AI for Social Good workshop at NeurIPS. 2019.](http://ai.ethicsworkshop.org/Library/LibContentAcademic/GoodNotGoodEnough.pdf)
