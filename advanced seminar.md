##20 Adaptive Hypermedia
_PETER BRUSILOVSKY_

__Adapting to what__

User data.
Goals/tasks, knowledge, background, and preferences were modelled and used for making adaptation decisions by many new systems.
User interests
User's individual traits is a group name for user features that together de¢ne a user as an individual.Examples are personality factors (e.g. introvert/extravert), cognitive factors, and learning styles.

*Moreover, several
experimental studies (which have aimed to evaluate the value of treating users with different individual traits differently) have concluded without ¢nding any signi¢cant differences. To progress in this area, we either need to learn more about the relation-ships between user traits and possible interface settings, or treat user traits as a blackbox and attempt to model them and adapt to them using non-symbolic technologies (Gilbert and Han, 1999).*

Usage data
Environment data
We distinguished two distinct areas of adaptation: content level adaptation or adaptive presentation and link level adaptation or adaptive navigation support.

__What can be adopted__
We distinguished two distinct areas
of adaptation: content level adaptation or adaptive presentation and link level adaptation or adaptive navigation support.

Modern adaptive hypermedia systems may have a choice of different types of media with which to present information to the user; that is, in addition to traditional text, we can also use music, video, speech, animation, and so on

Second, the rise of recommender systems makes it necessary to distinguish between two essentially different ways of adaptive navigation support: adapting the links that were present on a page at the time of hyperspace authoring, and generating new, non-authored links for a page.

Future Trends(2001).
* Integration with other applications
![fig1][Brusilovsky2001Fig1]
[Brusilovsky2001Fig1]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/brusilovski-fig1.png
"Figure 1. The updated taxonomy of adaptive hypermedia technologies."

* Open corpus adaptive hypermedia
* Handheld and mobile devices.

New technologies
Non-symbolic AI technologies.
Non-symbolic approaches are able to extract some information about the user from
the navigation trace as a whole

New Architectures
* Authoring tools.
* Component-based frameworks and user model servers


##16 Modeling Users on the World Wide Web based on Cognitive Factors, Navigation Behaviour and Clustering Techniques
__Marios Belk, Efi Papatheocharous, Panagiotis Germanakos, George Samaras__

_Abstract._ This paper focuses on modeling users’ cognitive styles based on a set of Web usage mining
techniques on user navigation patterns and clickstream data. Main aim is to investigate whether specific
clustering techniques can group users of particular cognitive style using measures obtained from psychometric
tests and content navigation behaviour. Three navigation metrics are proposed and utilized to find identifiable groups of users that have similar navigation patterns in relation to their cognitive style. The proposed work has been evaluated with two user studies which entail a psychometric-based survey for extracting the users’ cognitive styles, combined with a real usage scenario of users navigating in a controlled Web 2.0 environment. A total of 106 participants of age between 17 and 25 participated in the study providing interesting insights with respect to cognitive styles and navigation behaviour of users. Studies like the reported one can be useful for modeling users and assist adaptive Web 2.0 environments to organize and present information and functionalities in an adaptive format to diverse user groups.

_Keywords:_ User Modeling; Cognitive Styles; Web Navigation Behaviour; Web Mining

Adapting the functionality and content, of any Web-based interactive system, to
satisfy the users’ needs and increase their level of understandability and acceptability in an intuitive
manner and empower them to complete specific tasks more efficiently and effectively is a challenging
endeavor.

__The user model__ is a representation of static and dynamic information about an individual that is utilized by the adaptive interactive system aiming to provide adaptation effects (Bruilovsky and Millán, 2007)

An increasing interest, apart from research-oriented systems, has been observed during the last few
years from major commercial Web 2.0 service providers such as Google (http://www.google.com), Bing (http://www.bing.com), and Amazon (http://www.amazon.com) that provide personalized results and recommendations, by employing various user modeling and adaptation techniques.


Individuals are certainly different from each other, but which would be the underlying theories that could guideresearch endeavors in producing measurable gains?

holistic or analytic approach of navigation

Main objectives of the paper are to: 
* study the relation between users' cognitive styles and navigation behaviour
* investigate whether specific data analysis techniques can group users of particular cognitive style using measures obtained from psychometric tests, and 
* propose navigation content metrics to find identifiable groups of users that have similar navigation patterns.

### User Modeling Mechanisms
A __user model__ is created through a user modeling mechanism in which unobservable information about a user
is inferred from observable information from that user (Frias-Martinez et al., 2005), for example, using the interactions with the system (i.e., time being active on a Web-page, buying history, ratings of products, bookmarked or saved content, etc.).

User Guided Modeling.
Rely on personal information provided by the users, typically via registration forms.

Dynamic User Modeling.
Based on implicit information, such as the navigation behaviour of users.
Kelly and Teevan (2003) provide an overview of the most popular mechanisms for dynamically collecting implicit user information. Gauch et al. (2007) also summarize different approaches to implicit user information collection.

Generating User Models.
 (Nasraoui et al., 2008). Nasraoui et al. (2008) Clustering techniques are also used in order to divide users into segments containing users with similar navigation behaviour. Using a similarity metric, a clustering algorithm groups the most similar users together to form clusters.

 _Analysis of Existing Cognitive-based Adaptive Interactive Systems_
 The literature distinguishes a number of dimensions in which the users’ cognitive styles may differ: 
 * field-dependent/independent, 
 * impulsive/reflective, 
 * conceptual/inferential, 
 * thematic/relational, 
 * analytic/global (Chen and Macredie, 2002; Liu and Ginther, 1999).

![fig2][Belk_etcFig1]
[Belk_etcFig1]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc-fig1.png
"Adaptive Interactive Systems based on Individual Style Theory"

Cognitive Style Theory used in the Study
![fig3][Belk_etcFig2]
[Belk_etcFig2]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc-fig2.png
"Riding’s CSA Scale Mapping to Web 2.0 Environments"

Experimental Study I - Results and Discussion
![fig4][Belk_etcFig3]
[Belk_etcFig3]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc-fig3.png
"Clustering Results of the (a) Navigation Menu Interactions and (b) Content Link Interactions of Experimental Study I"

In sum, no safe conclusion can be drawn whether cognitive styles can relate to the navigation
behaviour of users (in regard with linear/non-linear approach). Nevertheless, our addition of two new
classes to the Riding’s CSA (i.e., users that were classified as Intermediates and their ratio of answers
was closer to the threshold of the Wholist or Analyst class, were classified as Light Wholists or Light
Analysts respectively), has shown that many Wholists and many former Intermediates (and now Light
Wholists) had linear navigation according to the metrics proposed.

Experimental Study II - Results and Discussion
Also, __results indicate that differences exist in navigation style between users (linear/non-linear),
however, no safe conclusion can be drawn whether the navigation style can be strongly related to
cognitive styles of users.__

###Conclusions
The clustering of users based on the proposed navigation metrics have shown promising results
since the clustering technique grouped consistently the users based on their navigation behaviour (i.e.,
linear/non-linear). Such results indicate that individuals navigate differently in terms of linearity
among hyperlinks that have close semantic relationship

Another future activity might include automatically predicting the cognitive style of users utilizing
their navigation behaviour using artificial intelligence techniques.

##01 User Cognitive Style and Interface Design for Personal, Adaptive Learning. What to Model?
_ELIZABETH URUCHRUTU, LACHLAN MACKINNON, ROGER RIST_

..see presentatition

##21 Towards implicit user modeling based on artificial intelligence, cognitive styles and web interaction data
_EFI PAPATHEOCHAROUS, MARIOS BELK, PANAGIOTIS GERMANAKOS, GEORGE SAMARAS_

###intro
Approaches for Web adaptation and personalization:
* cultural preferences of users, 
* adaptive spellchecker and predictor for people with dyslexia
* implicit user modeling approach that automatically adapts the layout and position of virtual keyboards based on how and where users are grasping the tablet device.

personalized services

Content-based filtering.
The weights indicate the importance of each feature to the user.

main aim is to increase our understanding about the effect of cognitive styles of users on their navigation behavior, but as well as the content representation they prefer the most and increase their overall user experience.

We investigate whether users with common cognitive characteristics have the tendency to follow exactly the same nodes in the hypermedia environment.

###User Modeling
Cognitive styles.
Verbal/Imager dimension that refers to how individuals process information and indicates their preference for representing information verbally (Verbals) or in mental pictures (Imagers)
a Wholist/Analyst dimension that refers to how individuals organize information and indicates a preference of structuring information as a whole (Wholists) or structuring the information in segmented parts (Analysts).

![fig5][Papatheocharous_etcFig1]
[Papatheocharous_etcFig1]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/papatheocharous-fig1.png
"Figure 1. Riding’s CSA Scale Mapping to Web Environments”

Explicit user model generation approaches usually result in user models becoming inaccurate over time.

The data mining techniques reported enable pattern discovery through clustering, classification, association rules, and Markov chains for Web personalisation purposes.

So, instead of monitoring usage, this paper proposes an alternative approach to user modeling by monitoring the users’ sequence of links visited in a Web environment through an online tool that utilises specific user interaction metrics

###Study.
78 undergraduate students of the University of Cyprus

The participants first completed the cognitive styles elicitation process utilising Riding’s CSA test [7], and further navigated in a reproduced version of Wikipedia.org

participants were assigned 10 problem-based tasks whose answers could be found inside the Wikipedia articles 

###Results
![fig6][Papatheocharous_etcFig2]
[Papatheocharous_etcFig2]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/papatheocharous-fig2.png
"Figure 6. Clusters formed based on Total Viewing Time for each Cognitive Styles Group”

the clustering method distinguished users in two clusters indicating that users had differing navigation behavior.

In this respect, no safe conclusions can be drawn whether users with similar cognitive styles have the same navigation behaviour. 

![fig7][Papatheocharous_etcFig3]
[Papatheocharous_etcFig3]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/papatheocharous-fig3.png
“Figure 8. Clusters formed based on the Sequence Vectors for each Cognitive Styles Group“
###Conclusions
In sum, results revealed that cognitive styles of users (taking into account the Verbal/Imager dimension) could be inferred, i.e., a strong significant relationship was found between the users’ cognitive styles and preference toward a specific type of content, based on their total viewing time of Web-pages that contain visual or verbal information. 

he clustering of users, based on the sequence vectors has shown some promising results and was effective to locate users with similar navigation behavior and in the same cognitive typology.

## Integrating Human Factors and Semantic Mark-ups in Adaptive Interactive Systems
_Marios Belk, Panagiotis Germanakos, Efi Papatheocharous, Panayiotis Andreou, George Samaras_

Main aim of this work is to investigate the added value of personalising content and functionality of Web environments based on the unique cognitive characteristics of users. 

###Introduction

In a technical point of view, an important challenge of designing an effective adaptive interactive system is to study and incorporate structures of meta-data (i.e., semantics) at the Web content provider’s side, as well as propose the construction of a Web-based adaptation mechanism that will serve as an automatic filter, adapting the distributed Web content based on the user characteristics.

a complete adaptation framework embracing: 
1) user modeling techniques for eliciting the cognitive characteristics of users, 
2) an authoring tool for supporting Web content providers throughout the creation of machine- understandable content, and 
3) an intelligent adaptation mechanism for dynamically reconstructing the semantic-based content and functionality of the Web environment. 

Effective personalisation of Web content and functionality in adaptive interactive systems involves two important challenges:
1) appropriate user modelling dealing with what information is important to be incorporated in the system
2) appropriate adaptation procedures dealing with what adaptation types and mechanisms are most effective

it is also necessary to study and design the structure of semantics in the context of adaptive interactive systems
###Semantic Web Technologies
Ontologies have been proven an effective means for enabling semantic-driven data processing

Authoring tools in the context of adaptive interactive systems have been proposed in the past as part of adaptive educational systems.

###Semantic-based adaptation framework
The framework consists of the following interconnected layers: 
1) *User Modelling*, for extracting the demographic (i.e., age, gender, profession) and cognitive characteristics of users, 
  1) Cognitive styles
  2) Working Memory Capacity. Working memory capacity was elicited through a psychometric test that requires from the participants to memorise an abstract image and then compare that image with five other similar images.

2) *Semantic Authoring Tool*, for the creation of semantically- enriched, machine-understandable content. In particular, a customised version of Wordpress has been developed and extended to enable the creation process of Web content with specific RDFa tags.
![fig8][Belk_etc2Fig1]
[Belk_etc2Fig1]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc2-fig1.png
“Figure 2: Personalisation and Adaptation Process“
3) *Adaptation Mechanism*, that performs various adaptation rules obtained by experts and which are based on the user models and the semantically-enriched content, and 
4) *Adaptive User Interface*, that presents the Web content in an adapted format and through adapted navigation controls based on the users’ cognitive characteristics.

###Study
70 undergraduate students

participants provided demographic information such as, name, age, education, etc.

the participants navigated in a commercial Web-site selling computer products that was developed for the purpose of the experiment.

As soon users completed answering all questions in both versions, they were presented with a comparative satisfaction questionnaire based on WAMMI questionnaire

###Results
![fig9][Belk_etc2Fig2]
[Belk_etc2Fig2]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc2-fig2.png
“Table 1: Cognitive Factors of Participants“

*Task Completion Performance*
![fig10][Belk_etc2Fig3]
[Belk_etc2Fig3]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc2-fig3.png
“Table 2: Means of Overall Performance per Cognitive Style Group“
The analysis of variance (ANOVA) indicates that users belonging to the Wholist and Intermediate classes performed considerably faster in the personalised version of the environment than in the original version (Wholist: F(1,47)=2.999, p=0.09, Intermediate: F(1,25)=2.699, p=0.11).

With regard to the Verbal/Imager dimension, the analysis revealed that Verbals and Imagers performed considerably faster in the personalised version of the environment than in the original version

![fig11][Belk_etc2Fig4]
[Belk_etc2Fig4]: https://github.com/chilicoder/study-wpm-workbook/blob/master/images/belk_etc2-fig4.png
users with limited working memory capacity performed faster in the personalised version

Users with intermediate and enhanced working memory capacity did not perform significantly different in either of the two environments since these two user classes did not receive any tool for comparing different products

*Task Accuracy*
Users in the personalised version were consistently more accurate in providing the correct answer for each task. 

although the difference of accuracy between the two versions was not significant in many cases, results are encouraging for the proposed mechanism, implying that adaptation on the basis of these cognitive factors (cognitive style and working memory capacity) provides adaptation effects that benefits users within an eCommerce environment.

*User Satisfaction*
Results revealed that 51 users (71.83%) preferred the personalised environment and 18 users (25.35%) preferred the original environment, while 1 user had neutral preference.

relationship between the users’ performances and preferred environment. 
The analysis showed that out of 21 users that performed slower in the personalised version, 18 users (85%) preferred the personalised environment, and out of 49 users that performed faster in the personalised version, 34 users (69%) preferred the personalised environment, whereas 15 users preferred the non-personalised environment.

###Discussion
the personalisation provided seems to have benefited primarily the Wholist and Intermediate users, and also users with limited working memory capacity. This might be explained by the fact that Wholists tend to rely more on information provided from the outside world and therefore require more guidance in navigation, in comparison to Analysts

###Conclusion
It was demonstrated that users’ information finding ability was considerably more accurate and efficient in the personalised version rather than the original version of the same environment.

co-worked with PersonaWeb project




