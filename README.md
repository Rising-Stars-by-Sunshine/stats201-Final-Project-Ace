# COVID and Online Jobs
## Project information
- **Author**: Ace Asim, Ethics and Leadership (Public Policy), Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS201 Introduction to Machine Learning for Social Science, 2023 Spring Term (Seven Week - First)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Acknowledgements to Prof. Luyao Zhang, Ava Baker, and Javier B. whom this project could not be done without.
- **Project Summary**: 

The COVID-19 pandemic has had an immeasurable impact on the job market, with numerous companies embracing remote work for the safety of their employees. This has led to a surge in the demand for virtual jobs, especially in industries that can be remote. This study aims to examine if there is a causal relationship between the COVID-19 pandemic and the increase in virtual jobs. From analyzing the popularity of virtual jobs over time, we found the results to support the hypothesis that COVID-19 has led to a spike in the interest in virtual jobs and that this upward trend is likely to persist as corporations become more resourceful in creating online jobs. This study highlights the impact of the pandemic on the job market and the potential benefits of increased flexibility and opportunities for online work.

- *Chat GPT's Take*:

<img width="746" alt="Screen Shot 2023-03-07 at 6 25 11 PM" src="https://user-images.githubusercontent.com/122700704/223380217-9fecb307-c34e-462d-b4ce-35552a3d249b.png">

  - **Application Scenario**: Not only is this information significant for workers and employers, but also for policymakers. From here, employers need to adopt new practices to manage and evaluate remote workers. Workers need to acquire new skills to succeed in virtual work environments. Policymakers need to adjust policies to support remote work. This study highlights the importance of resourcefulness and adaptation in the face of the unexpected (Tomić and Vizinger 2023).
  - **Methodology**: The data queried in this study is the popularity of the search term "virtual jobs" over the period of March 2018 to February 2023  to provide additional evidence of the trend. The main focus remains to identify any significant changes in the frequency of virtual job postings before and after March 2020, when the COVID-19 pandemic first hit. It is hypothesized that there will be a significant increase in the frequency of virtual job postings after March 2020, and this trend will continue in the future.
  - **Results**: The results of this study provide evidence to support the hypothesis that the COVID-19 pandemic has led to a surge and increase of virtual jobs in the United States, as reflected in the increase of virtual job postings and popularity of the search term "virtual jobs" since March 2020. The upward trend has continued, implying that virtual work is here to stay. 
  - **Intellectual Merits**:
  -  *Addressing a timely and relevant topic.*
  -  *Contributing to the existing literature.*
  -  *Using data-driven analysis.*
  -  *Highlighting potential implications and considerations for stakeholders, highlighting considerations for policymakers, employers, and workers in adapting to this new trend.*


## Table of Contents

| Get Where You Need to Go  | 
| ------------- |
| [Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/data)  | 
| [Code](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/code)  |
| [Spotlight](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/spotlight)  |
| [More about the Author](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/moreabouttheauthor)  |
| [References](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/references)  |



## Data

| All Data Used  | 
| ------------- |
| [Queried Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/data/Queried_Data)  |
| [Processed Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/tree/main/data/Processed_Data)  |



## Code

| All Code Used  | 
| ------------- |
| [Query Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/blob/main/code/Query_Data.ipynb)  | 
| [Process Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/blob/main/code/Process_Data.ipynb)  |
| [Analyze Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/blob/main/code/Analyze_Data.ipynb)  |

## Spotlight

**Figure 1: Random Forest Regression**

![image](https://user-images.githubusercontent.com/122700704/232252695-f7ca8fe0-f392-41e4-9424-1f0fd6176ba3.png)

*Source: [Google Trends](https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work) Created By: [sklearn.ensemble.RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)*

Figure 1 depicts a random forest regression analysis that demonstrates the relationship between time and the popularity of virtual jobs. The random forest algorithm is a machine-learning technique that uses decision trees to build a predictive model. By using multiple decision trees and combining their predictions, the model can generate more accurate and reliable results than a single decision tree. The plot in Figure 1 provides insight into the strength and character of this relationship, allowing for a better understanding of the trends and patterns in virtual job popularity over time.

**Figure 2: Word Cloud**

![image](https://user-images.githubusercontent.com/122700704/232258618-fc68e152-4d45-4fae-9537-648a4b6079c5.png)

*Source: [Relevant Literature: COVID and Online Jobs](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/blob/main/code/PS2-References.csv) Created By: [WordCloud](https://pypi.org/project/wordcloud/)*

Figure 2 displays a word cloud that visualizes the frequency of words used throughout relevant literature. In this case, the word cloud depicts the most commonly used terms in research related to remote work and virtual jobs. The larger the word appears in the cloud, the more frequently it is used in the literature. As shown in Figure 2, the words "COVID," "Remote," "Work," and "Pandemic" are the most commonly used terms in this context. A word cloud can be a useful tool for quickly identifying the most salient themes and topics in a large body of text.

**Figure 3: Regression Analysis**

![image](https://user-images.githubusercontent.com/122700704/232659154-4bc58c5b-fd8b-4e5a-8066-ca4061d70d06.png)

*Source: [Google Trends](https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work)*

Figure 3's regression analysis displays a steeper slope after COVID-19 quarantine orders in the US were placed (March 12, 2020) compared to before, indicating that there was a significant increase in the search popularity of "remote jobs" following the onset of the pandemic (Jacobsen and Jacobsen 2020). This is consistent with the fact that many people were forced to work from home as a result of the pandemic, and others may have been looking for alternative work arrangements due to economic uncertainty. It's also worth noting that the graph may reflect not only a change in people's behavior but also a change in how they search for information. Specifically, people may have been more likely to search for "remote jobs" specifically because of the pandemic, whereas they may have used different search terms in the past. Overall, the graph suggests that the COVID pandemic had a significant impact on the search popularity of "remote jobs," and this may reflect broader changes in how people work and seek employment.

**Figure 4: Project Poster**

![A  Asim: STATS-201 Final Project](https://user-images.githubusercontent.com/122700704/223381091-2f4d790f-8a92-4fde-818f-d1a0a94d0c98.png)

[A. Asim: STATS-201 Final Project -- PDF Version](https://github.com/Rising-Stars-by-Sunshine/stats201-Final-Project-Ace/files/10907880/A.Asim.STATS-201.Final.Project.pdf)

The study examined the relationship between the COVID-19 pandemic and the increase in remote jobs in the United States. The data were collected by analyzing the popularity of the search term "remote jobs" on Google Trends from March 2018 to February 2023. The study found that there was a significant increase in interest in remote job postings in the USA starting from the last week of February 2020 to the middle of March 2020. During this period, the number of interest, measured by searches, led to a 145% increase. Following the initial spike, the interest in remote jobs has continued to rise steadily, with a 12% increase from March 2020 to February 2023. The rate of searches also increased by 268.97% from 0.0126 to 0.0465. The results support the hypothesis that COVID-19 has led to a surge in the popularity of remote jobs, with companies and organizations becoming more resourceful in creating online jobs. The study highlights the impact of the pandemic on the job market and the potential benefits of increased flexibility and opportunities for online work. However, the study only pertains to the United States and does not provide insight into the quality of remote jobs, which may affect job retention. Further research could explore these factors and their implications for the future of work.

**Figure 5: Prediction**

<img width="511" alt="Screen Shot 2023-02-28 at 7 07 09 PM" src="https://user-images.githubusercontent.com/122700704/232663052-4288485f-50b2-4a7a-8ad4-cb8375ebdf1d.png">

*Created by [Whimsical](https://whimsical.com/)*

Figure 5 presents a prediction that the analysis of causality will demonstrate a notable shift in the search volume for the term "remote jobs" before and following the onset of COVID-19 quarantine in the US. The study hypothesizes that interest in remote jobs will experience a substantial increase after the outbreak, and this trend will persist. The graph illustrates a positive slope that transitions to an even steeper positive slope, reinforcing the hypothesis.

**Cybersecurity and AI Ethics**

Another critical aspect to consider in the virtual job market is cybersecurity. With the increasing reliance on technology, the need for cybersecurity professionals is growing rapidly. A study conducted in 2019 by Morgan Frank found that tech workers are increasingly taking on cybersecurity responsibilities. This shift is reflected in the data, with the number of unfilled cybersecurity positions increasing from 1 million in 2014 to 3.5 million in 2021, a 31% increase over the past decade, compared to a 4% increase in other IT positions. This trend is set to continue, with cybersecurity predicted to be one of the fastest-growing industries in the next decade. It is also worth noting that cybersecurity professionals will need to grapple with ethical considerations as the use of AI becomes more prevalent in the field (Morgan 2019). Ensuring that AI systems are transparent, accountable, and aligned with ethical principles is crucial for maintaining trust in the technology and safeguarding against potential abuses. As the demand for cybersecurity professionals continues to grow, so too will the need for AI ethics experts who can help ensure that these technologies are used responsibly and ethically.

## More about the Author

Ace Asim is a student at Duke Kunshan University majoring in Ethics and Leadership, Public Policy. His academic interests lay in ethics, law, and their intersection with software and Artificial Intelligence. He has previous experience working with R Programming for Statistics and is beginning his journey with Python. He wants to use his knowledge of programming and ethics to explore how Artificial Intelligence can become a useful, safe tool for the world.

![Ace in Barcelona, December 2022](https://user-images.githubusercontent.com/122700704/214361081-16216840-72e8-4439-930d-35d32c82322f.JPG)

### Sample Course Projects

[Problem Set 1](https://rising-stars-by-sunshine.github.io/stats201-PS1-Ace/)

[Problem Set 2](https://rising-stars-by-sunshine.github.io/stats201-PS2-Ace/)

[Final Project](https://rising-stars-by-sunshine.github.io/stats201-Final-Project-Ace/)

### Outside Projects
Read my [blog](https://aces-topsecret-blog.my.canva.site/) on AI Ethics!


## Final reflections

As the course comes to a close, I can confidently say that I have experienced tremendous growth in various aspects of my life. Firstly, intellectually, I have gained a deep understanding of machine learning concepts and techniques, enabling me to tackle real-world problems using interdisciplinary data. Through practical applications, I have learned how to structure machine learning problems, identify relevant algorithmic tools, and evaluate performance to produce accurate and meaningful results.

Secondly, professionally, this course has equipped me with the necessary skills to thrive in the technology industry. I have expanded my knowledge of programming languages, including R and Python, and developed an interest in their intersection with ethics and law. This newfound passion has motivated me to explore how Artificial Intelligence can become a useful and safe tool for the world.

Finally, this course has encouraged me to reflect on living a purposeful life. The DKU 7 animating principles, particularly rooted in globalism and wise leadership, have played a significant role in shaping my perspective on what it means to live a purposeful life. Through collaborative problem-solving and lucid communication, I have gained a deeper appreciation for the value of working with others toward a common goal. Furthermore, as a global citizen, I feel a responsibility to use my skills to make a positive impact on society.

In conclusion, this course has been a transformative experience, providing me with the necessary skills to tackle real-world problems, grow professionally, and live a purposeful life. As I move forward in my academic and professional pursuits, I am grateful for the opportunity to have learned from the DKU community and look forward to contributing to positive change in the world. Thank you so much, STATS-201!


## References

### Data Source
- [Google Trends](https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work)
- [NYC Jobs Dataset](https://catalog.data.gov/dataset/nyc-jobs)
### Code Source
- [STATS-201 Prediction Code Tutorial](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
### Articles
- [“Remote Work Before, During, and after the Pandemic.”](https://www.ncci.com/SecureDocuments/QEB/QEB_Q4_2020_RemoteWork.html)
- [“A Two-Year, 50-Million-Person Experiment in Changing How We Work.”](https://www.nytimes.com/2022/03/10/business/remote-work-office-life.html)
- [“Accelerating Remote Work after COVID-19.”](https://www.thecgo.org/research/accelerating-remote-work-after-covid-19/)
- [Parker, Kim, Juliana Horowitz, and Rachel Minkin. 2020. “How Coronavirus Has Changed the Way Americans Work.”](https://www.pewresearch.org/social-trends/2020/12/09/how-the-coronavirus-outbreak-has-and-hasnt-changed-the-way-americans-work/)

### Literature

**Chicago Author-Date Format**

Battisti, Enrico, Simona Alfiero, and Erasmia Leonidou. 2022. “Remote Working and Digital Transformation during the COVID-19 Pandemic: Economic–Financial Impacts and Psychological Drivers for Employees.” Journal of Business Research 150 (June). https://doi.org/10.1016/j.jbusres.2022.06.010.

Brynjolfsson, Erik, John Horton, Adam Ozimek, Daniel Rock, Garima Sharma, and Hong-Yi TuYe. 2020. “COVID-19 and Remote Work: An Early Look at US Data.” National Bureau of Economic Research, June. https://doi.org/10.3386/w27344.

Coate, Patrick. 2021. “Remote Work Before, During, and after the Pandemic.” Www.ncci.com. January 25, 2021. https://www.ncci.com/SecureDocuments/QEB/QEB_Q4_2020_RemoteWork.html.

Fan, Wen, and Phyllis Moen. 2023. “Ongoing Remote Work, Returning to Working at Work, or in between during COVID-19: What Promotes Subjective Well-Being?” Journal of Health and Social Behavior, January, 002214652211502. https://doi.org/10.1177/00221465221150283.

Galanti, Teresa, Gloria Guidetti, Eleonora Mazzei, Salvatore Zappalà, and Ferdinando Toscano. 2021. “Work from Home during the COVID-19 Outbreak.” Journal of Occupational & Environmental Medicine 63 (7): 426–32. https://doi.org/10.1097/jom.0000000000002236.

Goldberg, Emma. 2022. “A Two-Year, 50-Million-Person Experiment in Changing How We Work.” The New York Times, March 10, 2022, sec. Business. https://www.nytimes.com/2022/03/10/business/remote-work-office-life.html.

Google. 2023. “Google Trends.” Google Trends. February 28, 2023. https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work.
Gupta, Arpit. 2020. “Accelerating Remote Work after COVID-19.” The CGO. April 30, 2020. https://www.thecgo.org/research/accelerating-remote-work-after-covid-19/.

Jacks, Tim. 2021. “Research on Remote Work in the Era of COVID-19.” Journal of Global Information Technology Management 24 (2): 93–97. https://doi.org/10.1080/1097198x.2021.1914500.

Ozimek, Adam. 2020. “The Future of Remote Work.” SSRN Electronic Journal, May. https://doi.org/10.2139/ssrn.3638597.

Parker, Kim, Juliana Horowitz, and Rachel Minkin. 2020. “How Coronavirus Has Changed the Way Americans Work.” Pew Research Center’s Social & Demographic Trends Project. December 9, 2020. https://www.pewresearch.org/social-trends/2020/12/09/how-the-coronavirus-outbreak-has-and-hasnt-changed-the-way-americans-work/.

Tomić, Damir, and Karla Vizinger. 2023. “Effects of Remote Business during the Covid-19 Pandemic - a Literature Review.” American Journal of Economics and Business Innovation 2 (1): 1–13. https://doi.org/10.54536/ajebi.v2i1.1088.

Tursunbayeva, Aizhan, Stefano Di Lauro, and Gilda Antonelli. 2021. “Remote Work at the Time of COVID-19 Pandemic and Beyond: A Scoping Review.” HR Analytics and Digital HR Practices, December, 127–69. https://doi.org/10.1007/978-981-16-7099-2_6.

**BibTex Format**

```
@article{ozimek_2020_the,
  author = {Ozimek, Adam},
  month = {05},
  title = {The Future of Remote Work},
  doi = {10.2139/ssrn.3638597},
  url = {https://content-static.upwork.com/blog/uploads/sites/6/2020/05/26131624/Upwork_EconomistReport_FWR_052020.pdf},
  year = {2020},
  journal = {SSRN Electronic Journal}
}

@article{jacks_2021_research,
  author = {Jacks, Tim},
  month = {04},
  pages = {93-97},
  title = {Research on Remote Work in the Era of COVID-19},
  doi = {10.1080/1097198x.2021.1914500},
  volume = {24},
  year = {2021},
  journal = {Journal of Global Information Technology Management}
}

@article{galanti_2021_work,
  author = {Galanti, Teresa and Guidetti, Gloria and Mazzei, Eleonora and Zappal√†, Salvatore and Toscano, Ferdinando},
  month = {04},
  pages = {426-432},
  title = {Work from Home during the COVID-19 Outbreak},
  doi = {10.1097/jom.0000000000002236},
  url = {https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8247534/},
  volume = {63},
  year = {2021},
  journal = {Journal of Occupational & Environmental Medicine}
}

@article{brynjolfsson_2020_covid19,
  author = {Brynjolfsson, Erik and Horton, John and Ozimek, Adam and Rock, Daniel and Sharma, Garima and TuYe, Hong-Yi},
  month = {06},
  title = {COVID-19 and remote work: An early look at US data},
  doi = {10.3386/w27344},
  year = {2020},
  journal = {National Bureau of Economic Research}
}

@article{tomi_2023_effects,
  author = {Tomiƒá, Damir and Vizinger, Karla},
  month = {01},
  pages = {1‚Äì13},
  title = {Effects of Remote Business During the Covid-19 Pandemic - A Literature Review},
  doi = {10.54536/ajebi.v2i1.1088},
  url = {https://journals.e-palli.com/home/index.php/ajebi/article/view/1088/483},
  urldate = {2023-01-21},
  volume = {2},
  year = {2023},
  journal = {American Journal of Economics and Business Innovation}
}

@article{fan_2023_ongoing,
  author = {Fan, Wen and Moen, Phyllis},
  month = {01},
  pages = {002214652211502},
  title = {Ongoing Remote Work, Returning to Working at Work, or in between during COVID-19: What Promotes Subjective Well-being?},
  doi = {10.1177/00221465221150283},
  urldate = {2023-02-28},
  year = {2023},
  journal = {Journal of Health and Social Behavior}
}

@misc{gupta_2020_accelerating,
  author = {Gupta, Arpit},
  month = {04},
  title = {Accelerating Remote Work After COVID-19},
  url = {https://www.thecgo.org/research/accelerating-remote-work-after-covid-19/},
  year = {2020},
  organization = {The CGO}
}

@article{tursunbayeva_2021_remote,
  author = {Tursunbayeva, Aizhan and Di Lauro, Stefano and Antonelli, Gilda},
  month = {12},
  pages = {127-169},
  title = {Remote Work at the Time of COVID-19 Pandemic and Beyond: A Scoping Review},
  doi = {10.1007/978-981-16-7099-2_6},
  year = {2021},
  journal = {HR Analytics and Digital HR Practices}
}

@article{battisti_2022_remote,
  author = {Battisti, Enrico and Alfiero, Simona and Leonidou, Erasmia},
  month = {06},
  title = {Remote working and digital transformation during the COVID-19 pandemic: Economic‚Äìfinancial impacts and psychological drivers for employees},
  doi = {10.1016/j.jbusres.2022.06.010},
  volume = {150},
  year = {2022},
  journal = {Journal of Business Research}
}

@misc{parker_2020_how,
  author = {Parker, Kim and Horowitz, Juliana and Minkin, Rachel},
  month = {12},
  title = {How Coronavirus Has Changed the Way Americans Work},
  url = {https://www.pewresearch.org/social-trends/2020/12/09/how-the-coronavirus-outbreak-has-and-hasnt-changed-the-way-americans-work/},
  year = {2020},
  organization = {Pew Research Center‚Äôs Social & Demographic Trends Project}
}

@misc{_2023_google,
  author = {, Google},
  month = {02},
  title = {Google Trends},
  url = {https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work},
  urldate = {2023-02-28},
  year = {2023},
  organization = {Google Trends}
}

@misc{coate_2021_remote,
  author = {Coate, Patrick},
  month = {01},
  title = {Remote Work Before, During, and After the Pandemic},
  url = {https://www.ncci.com/SecureDocuments/QEB/QEB_Q4_2020_RemoteWork.html},
  year = {2021},
  organization = {www.ncci.com}
}

@article{goldberg_2022_a,
  author = {Goldberg, Emma},
  month = {03},
  title = {A Two-Year, 50-Million-Person Experiment in Changing How We Work},
  url = {https://www.nytimes.com/2022/03/10/business/remote-work-office-life.html},
  year = {2022},
  organization = {The New York Times},
  journal = {The New York Times}
}
![image](https://user-images.githubusercontent.com/122700704/223400778-a66b17a9-8a52-4eff-bdc7-1431c17a7c9a.png)

```

Thank you!
