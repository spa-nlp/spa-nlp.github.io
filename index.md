---
layout: main-2022
title: Home
order: 1
collection: pages_2022
---

**Update 04/2022** List of [accepted papers](papers) and [the schedule](#workshop-schedule) are out!

[](**Update 03/15/2022: The standard deadline has passed, but you still can make ARR commitment or make non-archival submissions (ddl March 24th)! We award the best paper award as well as registration support for student authors. See details [below](#best-paper-award)!**)

[](**Update 03/03/2022: Due to a technical issue on the submission site, we've extended the submission deadline to 03/08. Please check the new [dates](#important-dates) below!**)

[](**Update 02/04/2022: Deadlines extended! In order to accomodate more submissions, we've extended the submission deadlines by a few days! Please check the new [dates](#important-dates) below!**)

[](**Update 02/04/2022: Date confirmed! Spa-NLP @ ACL2022 will be held on the 27th May**)

## Overview

Large parametric language models have achieved dramatic empirical success across many applications. However, these models lack several desirable properties such as explainability (providing provenance), privacy (ability to remove knowledge from the model), robust controllability, and debuggability. On the other hand, nonparametric models provide many of these features by design such as provenance, ability to incorporate/remove information. However, these models often suffer from weaker empirical performance as compared to deep parametric models.

Recently, many works have independently proposed a middle ground that combines a parametric model (that encodes logic) with a nonparametric model (that retrieves knowledge) in various areas from question answering over natural languages to complex reasoning over knowledge bases to even protein structure predictions. Given the increasingly promising results on various tasks of such [semiparametric model](https://en.wikipedia.org/wiki/Semiparametric_model), we believe this area is ripe for targeted investigation on understanding efficiency, generalization, limitations, widening its applicability, etc. As a result, we want to host a workshop on this topic.


<p align="center">
  <img src="assets/semiparametric.png" width="55%" height="55%">
</p>



## Submissions

Our workshop seeks paper submissions which address this topic. 
Submissions can be long (up to 8 pages) or short (up to 4 pages) and should follow the ACL paper tempate. 
Authors will submit papers for peer review from our program commitee.
Alternatively, we will also be accepting ARR submissions (with reviews).
Since submissions from ARR will come with reviews, the submission deadline for these papers will be later.

Authors of relevant, already-published work can also choose to submit their work to a non-archival track. 

Please check out our [Call for Papers](cfp) for more details!



## Invited Speakers

- [Danqi Chen](https://www.cs.princeton.edu/~danqic/), Princeton University
- [Hannaneh Hajishirzi](https://homes.cs.washington.edu/~hannaneh/), University of Washington & Allen Institute for AI
- [Andrew McCallum](https://people.cs.umass.edu/~mccallum/), University of Massachusetts, Amherst
- [Anna Potapenko](http://apotapenko.com/), Google Deepmind
- [Jason Weston](https://ai.facebook.com/people/jason-weston/), Facebook AI Research

We will also have a panel discussion with speakers and other inivted panelists.


## Workshop Schedule

The workshop will be held on May 27th from 09:20 to 18:00 in Irish Time (GMT+1).

<div id="schedule">
    <ul>
        <li>
          09:20–09:30 - Opening remark
        </li>
        <li>
          09:30–10:10	-	Invited talk 1: Anna Potapenko -- <b>AlphaFold: a semiparametric model for highly accurate protein structure prediction</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#anna-card" aria-expanded="false" aria-controls="reut-card">Abstract</button> <div class="collapse" id="anna-card"><div class="card card-body">In this talk I will cover several retrieval techniques that we employ for the protein structure prediction problem and make connections to NLP techniques where possible. I will start with an introduction to the proteins themselves, and the task of predicting a 3D structure from a sequence of amino acids (letters ranging a vocabulary of ~20). I will then talk about the architecture and intuition behind the AphaFold model, putting emphasis on the details relevant for the NLP community. In this model, apart from the query sequence of amino acids, we embed multiple additional data that we retrieve from external protein sequence and structure databases. This includes evolutionary related sequences (in the form of MSA, Multiple Sequence Alignment) and so-called templates (similar sequences with a known 3D structure). In the recent Critical Assessment of Protein Structure Prediction (CASP), AlphaFold demonstrated accuracy competitive with experimental structures in a majority of cases and greatly outperformed other methods, and has since been recognized as "Method of The Year 2021" by Nature Methods.</div></div>
        </li>
        <li>
          10:10–10:50	- Contributed talks
          <ul>
            <li>
              "Efficient Machine Translation Domain Adaptation" by Pedro Henrique Martins, Zita Marinho, Andre Martins
            </li>
            <li>
              "Internet-augmented language models through few-shot prompting for open-domain question answering" by Angeliki Lazaridou, Elena Gribovskaya, Wojciech Stokowiec, Nikolai Grigorev
            </li>
            <li>
              "Towards Unsupervised Dense Information Retrieval with Contrastive Learning" by Gautier Izacard, Mathilde Caron, Lucas Hosseini, Sebastian Riedel,  Piotr Bojanowski, Armand Joulin, Edouard Grave
            </li>
            <li>
              "Towards Continual Knowledge Learning of Language Models" by Joel Jang, Seonghyeon Ye, Sohee Yang, Joongbo Shin, Janghoon  Han, Gyeonghun Kim, Stanley Jungkyu Choi, Minjoon Seo
            </li>
          </ul>
        </li>
        <li>
          10:50–11:00	- Coffee break
        </li>
        <li>
          11:00–12:00	- Poster session I <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#papers1-card" aria-expanded="false" aria-controls="papers1-card">Paper list</button> <div class="collapse" id="papers1-card">
            <ul>
              <li>
                "Efficient Machine Translation Domain Adaptation" by
                Pedro Henrique Martins, Zita Marinho, Andre Martins
              </li>
              <li>
                "Improving Discriminative Learning for Zero-Shot Relation Extraction" by
                Van-Hien Tran, Hiroki Ouchi, Taro Watanabe, Yuji Matsumoto
              </li>
              <li>
                "Learning To Retrieve Prompts for In-Context Learning" by
                Ohad Rubin, Jonathan Herzig, Jonathan Berant
              </li>
              <li>
                "TemporalWiki: A Lifelong Benchmark for Training and Evaluating Ever-Evolving Language Models" by
                Joel Jang, Seonghyeon ye, Changho Lee, Sohee Yang, Joongbo Shin, Janghoon Han, Gyeonghun Kim, Minjoon Seo
              </li>
              <li>
                "Learning to Retrieve Passages without Supervision" by
                Ori Ram,Gal Shachaf,Omer Levy,Jonathan Berant,Amir Globerson
              </li>
              <li>
                "Is Retriever Merely an Approximator of Reader?" by
                Sohee Yang,Minjoon Seo
              </li>
              <li>
                "Towards Continual Knowledge Learning of Language Models" by
                Joel Jang, Seonghyeon Ye, Sohee Yang, Joongbo Shin, Janghoon Han, Gyeonghun Kim, Stanley Jungkyu Choi, Minjoon Seo
              </li>
              <li>
                "Hyperlink-induced Pre-training for Passage Retrieval in Open-domain Question Answering" by
                Jiawei Zhou,Xiaoguang,Lifeng Shang,Lan Luo,Ke Zhan,Enrui Hu,Xinyu Zhang,Hao Jiang,Zhao Cao,Fan Yu,Xin Jiang,Qun Liu,Lei Chen
              </li>
              <li>
                "Learning Cross-Lingual IR from an English Retriever" by
                Yulong Li, Martin Franz, Md Arafat Sultan, Bhavani Iyer, Young-Suk Lee, Avirup Sil
              </li>
              <li>
                "KNN-BERT: Fine-Tuning Pre-Trained Models with KNN Classifier" by
                Linyang Li, Demin Song, Ruotian Ma, Xipeng Qiu, Xuanjing Huang
              </li>
              <li>
                "GUD-IR: Generative Retrieval for Semiparametric Models" by
                Aman Madaan, Niket Tandon,  Peter Clark, Yiming Yang
              </li>
              <li>
                "Exploring Dual Encoder Architectures for Question Answering" by
                Zhe Dong, Jianmo Ni, Daniel M. Bikel, Enrique Alfonseca, Yuan Wang, Chen Qu, Imed Zitouni
              </li>
              <li>
                "PERKGQA: Question Answering over Personalized Knowledge Graphs" by
                Ritam Dutt, Kasturi Bhattacharjee, Rashmi Gangadharaiah, Dan Roth, Carolyn Rose
              </li>
              <li>
                "Towards Interactive Language Modeling" by
                Maartje ter Hoeve, Evgeny Kharitonov, Dieuwke Hupkes, Emmanuel Dupoux
              </li>
            </ul>
          </div>
        </li>
        <li>
          12:00–13:30	- Lunch
        </li>
        <li>
          13:30–14:10	- Invited talk 2: Danqi Chen -- <b>Learning Representations for Memory-Augmented Language Models</b>
        </li>
        <li>
          14:10–14:50	- Invited talk 3: Jason Weston -- <b>Language Models that Seek for Knowledge with Modular Search & Generation</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#jason-card" aria-expanded="false" aria-controls="jason-card">Abstract</button> <div class="collapse" id="jason-card"><div class="card card-body">We show that applying a single language model in a modular fashion can generate more factual responses. Our SeeKeR (Search engine->Knowledge->Response) method thus applies a single LM to three modular tasks in succession: search, generating knowledge, and generating a final response. We show that, when using SeeKeR as a dialogue model, it outperforms the state-of-the-art model BlenderBot 2 (Chen et al., 2021) on open-domain knowledge-grounded conversations for the same number of parameters, in terms of consistency, knowledge and per-turn engagingness. SeeKeR applied to topical prompt completions as a standard language model outperforms GPT2 (Radford et al., 2019) and GPT3 (Brown et al., 2020) in terms of factuality and topicality, despite GPT3 being a vastly larger model. Our code and models are made publicly available.</div></div>
        </li>
        <li>
          14:50–15:00	- Coffee break
        </li>
        <li>
          15:00–16:00	- Poster session II <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#papers2-card" aria-expanded="false" aria-controls="papers2-card">Paper list</button> <div class="collapse" id="papers2-card">
            <ul>
              <li>
                "Choose Your QA Model Wisely: A Systematic Study of Generative and Extractive Readers for Question Answering" by
                Man Luo, Kazuma Hashimoto, Semih Yavuz, Zhiwei Liu, Chitta Baral, Yingbo Zhou
              </li>
              <li>
                "Knowledge Base Index Compression via Dimensionality and Precision Reduction" by
                Vilém Zouhar, Marius Mosbach, Miaoran Zhang, Dietrich Klakow
              </li>
              <li>
                "Field Extraction from Forms with Unlabeled Data" by
                Mingfei Gao, Zeyuan Chen, Nikhil Naik, Kazuma Hashimoto, Caiming Xiong, Ran Xu
              </li>
              <li>
                "A Survey of Knowledge-Intensive NLP with Pre-Trained Language Models" by
                Da Yin, Li Dong, Hao Cheng, Xiaodong Liu, Kai-Wei Chang, Furu Wei, Jianfeng Gao 
              </li>
              <li>
                "C-MORE: Pretraining to Answer Open-Domain Questions by Consulting Millions of References" by
                Xiang Yue, Xiaoman Pan, Wenlin Yao, Dian Yu, Dong Yu, Jianshu Chen
              </li>
              <li>
                "Towards Unsupervised Dense Information Retrieval with Contrastive Learning" by
                Gautier Izacard, Mathilde Caron, Lucas Hosseini, Sebastian Riedel, Piotr Bojanowski, Armand Joulin, Edouard Grave
              </li>
              <li>
                "Internet-augmented language models through few-shot prompting for open-domain question answering" by
                Angeliki Lazaridou, Elena Gribovskaya, Wojciech Stokowiec, Nikolai Grigorev
              </li>
              <li>
                "Less is More: Summary of Long Instructions is Better for Program Synthesis" by
                Kirby Kuznia, Swaroop Mishra, Mihir Parmar, Chitta Baral
              </li>
              <li>
                "How Many Data Samples is an Additional Instruction Worth?" by
                Ravsehaj Singh Puri, Swaroop Mishra, Mihir Parmar, Chitta Baral
              </li>
              <li>
                "Unsupervised Cross-Task Generalization via Retrieval Augmentation" by
                Bill Yuchen Lin, Kangmin Tan, Chris Scott Miller, Beiwen Tian, Xiang Ren
              </li>
              <li>
                "Controllable Semantic Parsing via Retrieval Augmentation" by
                Panupong Pasupat, Yuan Zhang, Kelvin Guu
              </li>
              <li>
                "On the Effect of Pretraining Corpora on In-context Few-shot Learning by a Large-scale Language Model" by
                Seongjin Shin, Sang-Woo Lee, Hwijeen Ahn, Sungdong Kim, HyoungSeok Kim, Boseop Kim, Kyunghyun Cho, Gichang Lee, Woomyoung Park, Jung-Woo Ha, Nako Sung
              </li>
              <li>
                "StreamingQA: A Benchmark for Adaptation to New Knowledge over Time in Question Answering Models" by
                Adam Liska, Tomas Kocisky, Elena Gribovskaya, Tayfun Terzi, Eren Sezener, Devang Agrawal, Cyprien de Masson d’Autume, Tim Scholtes, Manzil Zaheer, Susannah Young, Ellen Gilsenan-McMahon, Sophia Austin, Phil Blunsom, Angeliki Lazaridou
              </li>
              <li>
                "RetroNLU: Retrieval Augmented Task-Oriented Semantic Parsing" by
                Vivek Gupta, Akshat Shrivastava, Adithya Sagar, Armen Aghajanyan, Denis Savenkov
              </li>
            </ul>
          </div>
        </li>
        <li>
          16:00–16:40	- Invited talk 4: Andrew McCallum -- <b>TITLE TBA</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#andrew-card" aria-expanded="false" aria-controls="andrew-card">Abstract</button> <div class="collapse" id="andrew-card"><div class="card card-body">ABSTRACT TBA</div></div>
        </li>
        <li>
          16:40–17:20	- Invited talk 5: Hanna Hajishirzi -- <b>Toward Robust, Knowledge-Rich NLP</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#hanna-card" aria-expanded="false" aria-controls="hanna-card">Abstract</button> <div class="collapse" id="hanna-card"><div class="card card-body">Enormous amounts of ever-changing  knowledge are available online in diverse textual styles and diverse formats. Recent advances in deep learning algorithms and large-scale datasets are spurring progress in many Natural Language Processing (NLP) tasks, including question answering. Nevertheless, these models cannot scale up when task-annotated training data are scarce. This talk presents my lab's work toward building general-purpose models in NLP and how to systematically evaluate them. First, I present a meta-training approach that can solve a variety of NLP tasks with only using a few examples and introduce a benchmark to evaluate cross-task generalization. Second, I discuss neuro-symbolic approaches to address more complex tasks by eliciting knowledge from structured data and language models.</div></div>
        </li>
        <li>
          17:20–17:50	- Panel discussion
        </li>
        <li>
          17:50–18:00	- Closing remark
        </li>
  </ul>
</div>

## Important Dates

(All AoE)
- Submission deadline (for papers requiring peer review): ~~February 28th~~ ~~March 3rd, 2022~~ March 8th, 2022
- Submission deadline (with ARR reviews): March 24th, 2022
- Submission deadline (Non-archival): March 24th, 2022
- Notification of acceptance: March 26th, 2022
- Camera-ready paper deadline: April 10th, 2022
- Workshop date: May 27th, 2022


## Submission guidelines
We seek submissions of original work or work-in-progress. Submissions can be in the form of long/short papers and should follow the ACL main conference template. Authors can choose to make their paper achival/non-archival. All accepted papers will be presented at the workshop.

#### Archival track
We will follow double-blind review process. We also will accept ACL rolling review (ARR) submissions with reviews. Since these submissions already come with reviews, the submission deadline is much later than the initial deadline. We will use Open Review for the submissions.

Submission Link: <https://openreview.net/group?id=aclweb.org/ACL/2022/Workshop/Spa-NLP>
* For papers needing review: click "ACL 2022 Workshop Spa-NLP submission"
* For papers from ARR: click "ACL 2022 Workshop Spa-NLP commitment Submission"

#### Non-archival track
Non-archival track seeks recently accepted / published work as well as work-in-progress. It does not need to be anonymized and will not go through the review process. The submission should clearly indicate the original venue and will be accepted if the organizers think the work will benefit from exposure to the audience of this workshop.

Submission Link: <https://forms.gle/7cJCvQbXmX9LPEch8>


## Best paper award
Thanks to generous support from our sponsors, we will award the best paper award (with cash prize) to one of the submissions selected by our program committee and organizing committee. The best paper will be given the opportunity for a lightning talk to introduce their work.

## Registration support
Thanks to generous support from our sponsors, we will support registration fees (either in-person or virtual) to student authors of the accepted papers (either archival, ARR commitment or non-archival).


## Organizing Committee
- [Rajarshi Das](http://rajarshd.github.io/), University of Massachusetts Amherst
- [Patrick Lewis](https://www.patricklewis.io/), University College London
- [Sewon Min](https://shmsw25.github.io/), University of Washington
- [June Thai](https://dungtn.github.io/), University of Massachusetts Amherst
- [Manzil Zaheer](http://www.manzil.ml/), Google DeepMind


## Sponsors


![Meta]({{ "/assets/meta-logo.png" | absolute_url }})
![Google]({{ "/assets/google-logo.svg" | absolute_url }})

