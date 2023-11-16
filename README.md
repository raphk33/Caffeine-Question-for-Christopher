# Answering Christopher’s Question: How Does Caffeine Intake Affect Physical Performance in Different Types of Exercise?

## Introduction

After speaking with Christopher, we found that a cool (and rather applicable) data science question would be to explore the correlation between caffeine intake and physical performance, making sure to note how that correlation changes between different types of exercise - specifically, running & weightlifting. Prior to beginning my work in answering this question, I made sure to note what Christopher wanted to see from me as a result. He told me that my results from this data science project should be able to tell him how much caffeine he should consume (for his body weight) before engaging in a physical activity, and what effect that will have on his performance. The goal of the below project is to answer his question.

## My Procedure & The Reasoning Behind It

Given that there are many dozens of studies that have been conducted searching to answer this question, and a corresponding amount of meta-analyses on these studies, I felt that the best way to answer Christopher’s question would be to do a meta-analysis of meta-analyses if you will. More specifically, I am compiling results from several meta-analysis studies on the correlation between caffeine intake and athletic performance, and analyzing what the consensus (if any) among these studies is.

The reason I am taking more of a qualitative approach to answering this question is because I recognize that an analysis of my own would likely fall short of the analyses that have already been done by professional researchers. Given the plethora of meta-analyses out there on this topic, I feel that exploring their results is both a fair and accurate way of answering Christopher’s question. I will first analyze results from studies considering endurance athletic events, then look at weightlifting, before finally considering what impact these results have on different sports.

This all comes from my asking the professor “what should I do since this question has already been answered multiple times?” and receiving the response “use the studies that exist as your own data points.”

So here goes!

## A Preface on the Methodology

Of course these meta-analysis studies get their data from a pool of studies. As such, we must certainly take into account that the pools may overlap, and that meta-analyses may be drawing on the same studies. On the one hand, this can be good because it serves as a check on the results of each meta-analysis (they should be similar). However, this could be detrimental as there may be some studies that none of the meta-analyses were able to draw from (although this is unlikely).

## Caffeine Intake & Performance in Endurance Events

Below are 3 meta-analysis studies that explore the correlation between caffeine intake and time of endurance events. It’s important to note that throughout the studies, the caffeine intake for these tests ranged from 3-6 mg per kilogram of body weight.

1. *Establishing a relationship between the effect of caffeine and duration of endurance athletic time trial events: A systematic review and meta-analysis. Shen, Brooks, et al.*
   - This study came to the conclusion that caffeine improved performance by 3% in endurance events of time trial nature.

2. *The Effect of Acute Caffeine Ingestion on Endurance Performance: A Systematic Review and Meta–Analysis. Southward, Rutherford-Markwick, and Ali.*
   - It was found that caffeine improved performance by 2.63% in endurance events.

3. *Effect of Caffeine on Sport-Specific Endurance Performance: A Systematic Review. Ganio, Klau, et. al.*
   - Caffeine ingested before exercise resulted in a mean performance improvement of 2.3%, with a variability of ±3.2%.

### Overall Synthesis

The three meta-analyses show a consistent trend of caffeine having a positive effect on endurance performance. The reported improvements in performance due to caffeine intake range from 2.3% to 3%, indicating a general agreement among the studies about the beneficial impact of caffeine, though the exact magnitude of this effect varies slightly.

The variability noted in the third study suggests that while the average effect is positive, individual responses to caffeine and specific conditions of the endurance events can influence the extent of performance enhancement.

Overall, these studies largely agree that caffeine intake is beneficial for enhancing performance in endurance events, but the degree of improvement may vary depending on various factors like genes.

## Caffeine Intake & Performance for Muscular Endurance Training (Weightlifting)

Again, I’ll look into three meta-analysis studies, but this time for weightlifting. But in this case, the data is listed in terms of Standard Mean Difference (SMD). What does that mean, and why is it significant?

Standardized Mean Difference (SMD) is a statistical measure used in meta-analyses and systematic reviews to quantify the effect size of an intervention across different studies. It calculates the difference in means between two groups (like treatment and control groups) and divides it by the standard deviation of the measurements. This standardization allows for comparing effect sizes from studies with different measurement scales. The significance of SMD lies in its ability to provide a uniform metric for assessing the magnitude of an effect, making it invaluable in fields like medicine and psychology. It helps in aggregating results from varied studies, offering insights into the practical significance of research findings beyond mere statistical significance. Now for the studies:

1. *Effects of caffeine intake on muscle strength and power: a systematic review and meta-analysis. Grgic, Trexler, et al.*
    - The study claims that “caffeine ingestion improved strength,” and reported a Standardized Mean Difference of 0.2.
    - 4.7 mg/kg mean dosage reported

2. *Effect of Caffeine Ingestion on Muscular Strength and Endurance, A Meta-Analysis. Warren, Park, et al.*
   - This meta-analysis claims that caffeine has a “small beneficial effect on muscular endurance.” 
     The reported Standardized Mean Difference was  0.19.
   - 6 mg/kg reported

3. *The effects of caffeine ingestion on isokinetic muscular strength: A meta-analysis. Grgic and Pickering.*
   - Again, the reported Standardized Mean Difference of caffeine on strength was .19. This study   
     also discussed that caffeine has a significantly greater effect on the performance of knee 
     extensor muscles. 
   - Median dosage of 6mg/kg was reported among these studies.
     
After reading more literature however, I have found that there is not as much of a consensus about the positive effects of caffeine intake on weight training, as compared to endurance training that was mentioned above.

## Discussion of How These Results Impact Sports
After reading the above results, one would of course presume that sports that have an emphasis on endurance as a key facet of their game would be most affected by caffeine. This is exactly the case.

Exploring the case of soccer, a heavy endurance sport, several independent studies found that caffeine intake resulted in more distance covered during the game, higher passing accuracy, and greater jumping height.
  - *Effects of a caffeine-containing energy drink on simulated soccer performance. Del Coso, Munoz      Fernandez, et al.*
  - *The influence of caffeine and carbohydrate coingestion on simulated soccer performance. Gant,       Ali, and Foskett.*

The same applies for rugby, another high endurance sport.
  - *Effects of Caffeine Ingestion on Skill Performance During an International Female Rugby Sevens      Competition. Portillo, Del Coso, and Abian-Vicen.*

But what about shorter-interval performance, like sprints? What impact does caffeine have? A study considered the effect of 5mg/kg of caffeine vs. a placebo effect on the National Football League (NFL) Combine, in which the collegiate athlete participants engage in several exercises (that are mostly short form in their capacity (40 yard sprint, 20 yard shuttle, etc.) The study found that “caffeine did not improve performance for anaerobic exercise tests used at the NFL Combine.”
  - *Effect of caffeine as an ergogenic aid during anaerobic exercise performance in caffeine naïve      collegiate football players. Woolf, Bidwell, Carlson.*

## Answering Christopher’s Question
The short answer, Christopher, is that it depends. From the two cases that you mentioned, endurance running and weightlifting, it is evident that taking caffeine prior to the endurance exercise will have a noticeable impact on your performance (event time), whereas the effect will likely be harder for you to notice during weight training. In regards to your question about dosage, I would suggest taking 6mg of caffeine per kilogram of body weight, as that’s what most studies used for their testing. Hope you find this answer helpful in your day to day life! This was a fun project to do.

## Reflection on How I am Using LLMs
Generally, I have seen much improvement in my usage of LLMs, especially following the assignment in which we found mistakes in GPT’s prompts. I feel like at the beginning of the semester, I treated LLMs as “magic” and took what they said way too seriously, rather than taking the time to think about their responses and check them. I now know not to do that. Moreover, I feel more confident in using LLMs to brainstorm ideas and begin projects!

