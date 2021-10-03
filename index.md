---
layout: main-2021
title: Home
order: 1
collection: pages_2021
---

## Overview

**Update: We are excited to announce [four selected abstracts](https://uskb-workshop.github.io/abstracts.html) to be featured at the 2nd USKB Workshop.**

**Update: We have released [the workshop schedule](https://uskb-workshop.github.io/#schedule)!**

There is growing interest in extracting, representing, and applying knowledge in NLP tasks. Diverse knowledge sources have been explored in the literature, from structured (e.g. Freebase, Wikidata) to unstructured (plain text), and more recently pretrained neural models (e.g. language models). Knowledge from such sources plays an important role in advancing the state-of-the-art in various downstream tasks, such as question answering, text generation and fact verification.

The objective of this workshop is to bring together researchers interested in effectively extracting, representing, and applying knowledge in different ways. We promote discussion in related topics including but not limited to:

- The role of explicit structure in representing knowledge in the future.
- Can language models be knowledge bases?
- How to effectively combine structured and unstructured knowledge?
- How to effectively combine external (explicit) and parameterized (implicit) knowledge?
- How to interpret knowledge contained in pretrained models?
- Applications that make use of structured or unstructured knowledge.
- Models which reason over knowledge, e.g. numerical and multi-hop reasoning.
- Transfer learning for diverse knowledge sources.
- Extracting and evaluating knowledge stored in language models.
- Multilingual knowledge sources.

**Due to concerns about COVID-19, the 2nd Workshop on Unstructured and Structured KBs will be fully virtual.**

## Registration
Workshop registration is included in [AKBC 2021 registration](https://na.eventscloud.com/ereg/index.php?eventid=639089&), along with access to the main conference (October 4th-6th).

## Important Dates

- ~~Tuesday, August 31th~~ Friday, September 10th:       Deadline for submission of extended abstracts
- Wednesday, September 15th:  Notification of acceptance
- Friday, October 1st:        Deadline for recorded videos
- Thursday, October 7th:  Workshop date

## Invited Speakers

- [Eunsol Choi](https://www.cs.utexas.edu/~eunsol/), University of Texas, Austin
- [William Cohen](https://wwcohen.github.io/), Google AI
- [Luna Dong](https://lunadong.com/), Facebook
- [Kelvin Guu](https://www.kelvinguu.com/), Google AI
- [Colin Raffel](https://colinraffel.com/), University of North Carolina, Chapel Hill & Hugging Face
- [Ivan Titov](http://ivan-titov.org/), University of Edinburgh

We will also have a panel discussion with speakers.

## Schedule

USKB workshop will be held virtually on October 7th from 8:25AM - 1PM in Pacific Time (UTC-7).

<div id="schedule">
    <ul>
        <li>
            08:25-08:30 - Opening remarks
        </li>
        <li>
        	08:30-09:00	- Invited talk: <a href="https://www.kelvinguu.com/" target="_blank">Kelvin Guu</a> -- <b>Can language models be knowledge bases? If not, why? If so, how?</b>
        	<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#kelvin-card" aria-expanded="false" aria-controls="kelvin-card">Abstract</button>
        	<!--<a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>-->
            <div class="collapse" id="kelvin-card"><div class="card card-body">Language models (LMs) encounter large amounts of world knowledge during training, and recent work has shown how to recover some of this knowledge through various forms of LM prompting / fine-tuning / probing. But how far are we from implementing the full capabilities and fidelity of a knowledge base? What challenges can be solved by simply scaling up to more parameters, and what challenges will require novel research orthogonal to model size? In this talk, I'll start by assessing the frontier of what LMs can and cannot do today. I'll then discuss a set of key challenges that (probably) won't be overcome by model scaling alone, and recent work to address them. For example: how do we obtain provenance for a model's assertions? And how can we update a model to account for new information or new context?</div></div>
        </li>
        <li>
			09:00-09:30	- Invited talk: <a href="https://lunadong.com/" target="_blank">Luna Dong</a> -- <b>Zero to One Billion: The Path to a Rich Product Knowledge Graph</b>
        	<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#luna-card" aria-expanded="false" aria-controls="luna-card">Abstract</button>
        	<!--<a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>-->
            <div class="collapse" id="luna-card"><div class="card card-body">Knowledge graphs have been used to support a wide range of applications and enhance search results for multiple major search engines, such as Google and Bing. To better serve customers in eCommerce, we need a product knowledge graph with comprehensive and accurate knowledge for products. The thousands of product verticals we need to model, the vast number of data sources we need to extract knowledge from, the huge volume of new products we need to handle every day, and the various applications in Search, Discovery, Personalization, Voice, that we wish to support, all present big challenges in constructing such a graph.
           	<br />
			This talk takes my past experiences for collecting product knowledge as an example to describe the journey to build a rich knowledge graph. We describe how we nail down the most important first step for delivering the data business: training high-precision models that generate accurate data. We then describe how we scale up the models with learning from limited labels, and how we increase the yields with multi-modal models and web extraction. We share the many learnings and lessons in building this product graph and applying it to support customer-facing applications.</div></div>
		</li>
		<li>
			09:30-10:00	- Invited talk: <a href="https://wwcohen.github.io/" target="_blank">William Cohen</a> -- <b>TBA</b>
        	<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#william-card" aria-expanded="false" aria-controls="william-card">Abstract</button>
        	<!--<a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>-->
            <div class="collapse" id="william-card"><div class="card card-body">TBA</div></div>
		</li>
		<li>
			10:00-10:30	- Break + featuring accepted abstracts
		</li>
		<li>
			10:30-11:00	- Invited talk: <a href="https://www.cs.utexas.edu/~eunsol/" target="_blank">Eunsol Choi</a> -- <b>Incorporating extra-linguistic contexts and entity knowledge into natural language processing</b>
        	<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#eunsol-card" aria-expanded="false" aria-controls="eunsol-card">Abstract</button>
        	<!--<a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>-->
            <div class="collapse" id="eunsol-card"><div class="card card-body">Many real-world applications of natural language processing need to be able to interpret text from the rich context in which it occurs. While earlier NLP benchmarks focused on self-contained linguistic knowledge, recent benchmarks simulate end application more closely, requiring us to bring in rich context and background knowledge. In the first part of the talk, I will present our recent work incorporating two extra-linguistic contexts (when and where the question was asked) into open retrieval question answering. To handle queries where answer varies based on their contexts (e.g., who is the Vice President?), humans easily combine information from the query and the situation where the query was posed. Yet, our study finds that existing models struggle to handle extra-linguistic contexts, struggling to answer questions where answers are recently updated (even when provided with an updated evidence corpus) or from uncommon locations. In the latter part of the talk, I will present a benchmark testing models' reasoning capability based on background knowledge about specific entities. Again, we find models show limited success in incorporating entity knowledge to interpret texts. Together, we highlight models should embrace extra-linguistic contexts and background knowledge to support real-world applications. </div></div>
		</li>
		<li>
			11:00-11:30	- Invited talk: <a href="https://colinraffel.com/" target="_blank">Colin Raffel</a> -- <b>A better way to get language models to do what you ask</b>
        	<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#colin-card" aria-expanded="false" aria-controls="colin-card">Abstract</button>
        	<!--<a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>-->
            <div class="collapse" id="colin-card"><div class="card card-body">Very large language models have recently been shown to attain reasonable zero-shot generalization on a diverse set of tasks. It is theorized that this is a consequence of implicit multitask learning in language model training. Can better zero-shot generalization be directly induced by multitask learning on explicit prompts? To test this question at scale, we develop a system for easily mapping natural language tasks into a human-readable prompted form. We annotate a large set of supervised datasets, each with multiple prompts using varying language. We fine-tune T5 on this multitask mixture covering a wide variety of tasks, from question-answering to text classification to summarization. We dub the resulting model T0 and show that it outperforms GPT-3 on zero-shot task generalization in many cases, despite being about 16 times smaller.</div></div>
		</li>
		<li>
			11:30-12:00	- Invited talk: <a href="http://ivan-titov.org/" target="_blank">Ivan Titov</a> -- <b>Editing Factual Knowledge in Language Models</b>
        	<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#ivan-card" aria-expanded="false" aria-controls="ivan-card">Abstract</button>
        	<!--<a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>-->
            <div class="collapse" id="ivan-card"><div class="card card-body">The factual knowledge acquired during pre-training and stored in the parameters of Language Models (LMs) can be useful in downstream tasks (e.g., question answering or textual inference). However, some facts can be incorrectly induced or become obsolete over time. In the talk, I will look into question answering and fact checking, and will introduce  KnowledgeEditor, a method which can be used to edit the knowledge and, thus, fix 'bugs' or unexpected predictions without the need for expensive re-training or fine-tuning. Besides being computationally efficient, KnowledgeEditor does not require any modifications in LM pre-training (e.g., the use of meta-learning). In our approach, we train a hyper-network with constrained optimization to modify a fact without affecting the rest of the knowledge; the trained hyper-network is then used to predict the weight update at test time. With our method, changing a prediction on the specific wording of a query tends to result in a consistent change in predictions also for its paraphrases. We show that this can be further encouraged by exploiting (e.g., automatically-generated) paraphrases during training. Interestingly, our hyper-network can be regarded as a 'probe' revealing which components need to be changed to manipulate factual knowledge; our analysis shows that the updates tend to be concentrated on a small subset of components. Work with Nicola De Cao and Wilker Aziz. Details in https://arxiv.org/abs/2104.08164</div></div>
		</li>
		<li>
			12:00-12:15	- Break
		</li>
		<li>
			12:15-13:00	- Panel discussion
		</li>
	</ul>
</div>

Each talk is 25 min + 5 min Q&A.


## Organizing Committee
- [Rajarshi Das](http://rajarshd.github.io/), University of Massachusetts Amherst
- [Bhuwan Dhingra](https://www.cs.cmu.edu/~bdhingra/), Duke University
- [Nicholas FitzGerald](http://nfitz.net/), Google AI
- [Sewon Min](https://shmsw25.github.io/), University of Washington
- [Aleksandra Piktus](https://uk.linkedin.com/in/piktus), Facebook AI
- [Siamak Shakeri](https://www.linkedin.com/in/siamak-shakeri-b0827316), Google AI
- [Pat Verga](https://people.cs.umass.edu/~pat/), Google AI

