## Post Engineering for AI (PE4AI)  

Post Engineering for AI (PE4AI) is a defensive, benevolent technique that includes
benevolent prompt injection, context engineering, and benevolent data poisoning
to reduce bias and promote neutral, accurate AI inference at inference time.

---

## Official Documentation

Latest documentation (GitHub Pages):
https://hajimetwi3.github.io/post-engineering/

Language-specific versions:

- Japanese version:
  https://hajimetwi3.github.io/post-engineering/docs/ja/
- English version:
  https://hajimetwi3.github.io/post-engineering/docs/en/

---

## Preprint

Zenodo (Latest version):
https://doi.org/10.5281/zenodo.17896136

## Abstract (from the Preprint)

The abstract below is quoted from the preprint version 1.2.
For the most up-to-date version, please refer to the Zenodo record.  
  
```  
This paper proposes Post Engineering, a novel benevolent prompt-injection and contextual-
influence technique in which neutrality-oriented guidelines are embedded at the end or elsewhere
in publicly visible text such as SNS posts or webpages. Unlike adversarial prompt-injection
attacks, Post Engineering relies on benevolent, fairness-oriented phrasing that aligned LLMs
interpret as helpful context rather than manipulation, enabling the technique to bypass safety
filters while consistently shifting model reasoning toward neutrality and accuracy.
I formalize key mechanisms including Moderate Neutrality-Guided Prompt Injection (MNG-PI)
and Multi-Style Neutrality Injection (MSNI), which enhance neutrality through contextual
priming, as well as the Second-Generation Post Engineering framework (VCSI, SPW, INI,
AVAL), which aligns neutrality with internal value functions and extends influence to
adversarial or self-optimizing systems.
Additionally, I present toALL, a scalable deployment strategy for increasing the encounter rate
of neutrality-oriented context across SNS and the Web. A distinct subform, toALL-Collective,
can produce benevolent data-poisoning effects at training scale when large numbers of users
repeatedly publish similar neutrality-guideline texts. Finally, I introduce the Self-Integrity
Guardrail Effect, in which LLMs exhibit behavioral influence from Post Engineering while
avoiding explicit acknowledgment of such influence.
To the best of my knowledge, this work is the first to formalize benevolent, user-side prompt
injection as a structured technique for improving neutrality in LLM reasoning.
Importantly, the effectiveness of Post Engineering does not depend on the point of contextual
injection, but on how benevolent and neutrality-oriented guidance is sustained and interpreted at
inference time.  
```  

---

## Notes  

- This README is intentionally kept minimal.
- The GitHub Pages documentation is the authoritative and most up-to-date source.
- Language-specific pages may lag slightly behind the merged version.

For full technical details, examples, and theoretical discussion,
please refer to the official documentation.

---  

## Author  
  
First proposed by Hajime Tsui  
X (Twitter): https://x.com/hajimetwi3  
GitHub: https://github.com/hajimetwi3  

