# machine-learning-homework-15--meta-learning-solved
**TO GET THIS SOLUTION VISIT:** [Machine Learning Homework 15- Meta Learning Solved](https://www.ankitcodinghub.com/product/machine-learning-solved-14/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121252&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Machine Learning Homework 15- Meta Learning  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Machine Learning HW15

Meta Learning

ML TAs

Outline

● Task Description

● Data Format

● Grading

● Submission ● Regulations

● Contact

The Omniglot dataset

The Omniglot dataset

– background set: 30 alphabets

– evaluation set: 20 alphabets

Problem setup: 5-way 1-shot classification

Support set Query set

Data Format

Training / validation set:

30 alphabets

– multiple characters in one alphabet

– 20 images for one character

Data Format

Testing set:

640 support and query pairs

– 5 support images

– 5 query images

Guidance – Simple Baseline

Simple transfer learning model (implemented in sample code) training

– normal classification training on randomly chose five tasks validation / testing

– finetune on the five support images, and do inference on query images

Guidance – Medium / Strong Baseline

Finish the TODO blocks for meta learning inner &amp; outer loop (in sample code)

Medium baseline

– FO-MAML

Strong baseline

– MAML / ANIL

– Original MAML: slides p.12 – p.18 &amp; p. 21 – p. 26

– First-order approximation MAML (FO-MAML): slides p. 24 – 27

– Reptile: slides p. 29 – p. 31

– MAML tips: How to train your MAML?

– ANIL: Feature reuse

Guidance – Boss Baseline

Task augmentation (with meta learning) – What is a reasonable way to create new task?

Original task Additional task

augmented

Grading – Baseline Guide 1/3

● Simple baseline (acc ~ 0.6)

– Transfer learning (sample code)

● Medium baseline (acc ~ 0.7)

– Meta learning (FO-MAML)

● Strong baseline (acc ~ 0.9) – Meta learning (MAML)

● Boss baseline (acc ~ 0.95)

– Meta learning (MAML) + task augmentation

Grading – Baselines 2/3

● Simple baseline (public) +0.5 pt

● Simple baseline (private) +0.5 pt

● Medium baseline (public) +0.5 pt

● Medium baseline (private) +0.5 pt

● Strong baseline (public) +0.5 pt

● Strong baseline (private) +0.5 pt

● Boss baseline (public) +0.5 pt

● Boss baseline (private) +0.5 pt

● Report +4 pts

● Code submission +2 pts

Total: 10 pts

Grading – Bonus

If your ranking in private set is top 3, you can choose to share a report to NTU COOL and get extra 0.5 pts.

About the report (report template)

● Your name and student_ID

● Methods you used in code

● Reference

● In 200 words

● Please upload to NTU COOL’s discussion of HW15

Report questions (4%)

Part 1: Number of Tasks

– According to your best meta-learning result, plot the relation between dev accuracy and the number of tasks. Include at least three different experiment in the figure. (1pt)

– A one sentence description of what you observe from the above figure. (1pt)

Report questions (4%)

Part 2: Inner Update Steps

– According to your best meta-learning result, plot the relation between dev accuracy and the inner update step at inference (noted that you should not change the inner update step at training, it should be the same with your best meta-learning result throughout the experiment). Include at least three different experiment in the figure. (1pt)

– A one sentence description of what you observe from the above figure. (1pt)

Links

– Colab

– Kaggle

– Report (On Gradescope)

Submission – Deadlines 1/6

● Kaggle, Report (GradeScope), Code Submission (NTU COOL)

Submit early!

Submission – NTU COOL 5/6

● NTU COOL

○ Compress your code into

&lt;student ID&gt;_hwX.zip

* e.g. b06901020_hw15.zip

* X is the homework number

○ We can only see your last submission.

○ Do not submit your model or dataset.

○ If your code is not reasonable, your semester grade x 0.9.

Regulations 1/2

● You should NOT plagiarize, if you use any other resource, you should cite it in the reference. (＊)

● You should NOT modify your prediction files manually.

● Do NOT share codes or prediction files with any living creatures.

● Do NOT use any approaches to submit your results more than 5 times a day.

● Do NOT search or use additional data.

● You are allowed to use pre-trained models on any image datasets.

● Your final grade x 0.9 if you violate any of the above rules.

● Prof. Lee &amp; TAs preserve the rights to change the rules &amp; grades.

(＊) Academic Ethics Guidelines for Researchers by the

Ministry of Science and Technology

If you have any question…

● NTU COOL (recommended)

○ HW15 discussion board

● Kaggle discussion

● Email

○ The title should begin with “[hw15]”

Post-test Questionnaire (後測問卷)

教育部後測問卷 學生心得問卷
