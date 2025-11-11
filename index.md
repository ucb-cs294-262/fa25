---
title: Home
layout: home
nav_exclude: false
---

# CS294-262: Performance Analysis and Optimization of Computer Systems

**Fall 2025, UC Berkeley**

**Location:** Monday and Friday, 3:30pm to 5:00pm in 306 Soda. 

**Course Overview:** This course introduces the principles and techniques for analyzing and improving the performance of large-scale, heterogeneous computer systems. We’ll start with classical topics such as caching, load balancing, and scheduling, before moving to modern challenges in achieving efficiency and predictable performance in production environments. Finally, we will explore how ideas from machine learning and programming languages can offer new insights and tools for performance analysis. Case studies will span a diverse range of systems---including operating systems, distributed systems, hardware accelerators, and LLM-serving platforms---to give students a holistic understanding of system performance. 

**Prerequisites:** Students must have previously taken at least two of the following courses or their equivalents:
- CS262A: Advanced Topics in Computer Systems
- CS268: Computer Networks
- CS162: Operating Systems and Systems Programming
- CS168: Introduction to the Internet: Architecture and Protocols
- CS186: Introduction to Database Systems
- CS152: Computer Architecture and Engineering

**Enrollment policy:** Graduate students may enroll directly. Undergraduate students who meet the above pre-requisites---or have other significant systems experience (e.g., via internships)---are also welcome and should [email Rishabh](mailto:rishabh.iyer@berkeley.edu) for enrollment.  

---
## Resources
- **Lecture Slides**: [Link](https://drive.google.com/drive/folders/1_ZMAU9w8t28ghs84jXd9ZlLL3uI90xk9?usp=sharing).
- **Review form**: [Link](https://forms.gle/1k4rdbpun7Kn1LQF6).
- **Project proposal form**: [Link](https://forms.gle/URsu2SDTqYp5Lwo4A)

---

## Logistics
- **Lecture/Discussion**: Mondays and Fridays from 3:30pm to 5:00pm in 306 Soda.
- **Weekly Reading Reviews**: Due Mondays and Fridays @ noon pacific. 
- **Project Proposal**: Due Sep 30 @midnight pacific.

---

## Syllabus 
Subject to change. 

- **Friday, Aug 29: Introduction**

- **Monday, Sep 1: Labor Day**

- **Friday, Sep 5: Caching: Replacement policies**
    - [ARC: A Self-Tuning, Low Overhead Replacement Cache](https://www.usenix.org/legacy/events/fast03/tech/full_papers/megiddo/megiddo.pdf) 
    - [FIFO Queues are All You Need for Cache Eviction](https://junchengyang.com/publication/sosp23-s3fifo.pdf)
<br><br> 
- **Monday, Sep 8: Caching: Challenging assumptions**
    - [Caching with Delayed Hits](https://dl.acm.org/doi/pdf/10.1145/3387514.3405883)
    - [Applying Deep Learning to the Cache Replacement Problem](papers/deep-learning-cache.pdf)
<br><br> 
- **Friday, Sep 12: Load balancing requests**
    - The Power of Two Random Choices [[1]](https://brooker.co.za/blog/2012/01/17/two-random.html)[[2]](https://www.haproxy.com/blog/power-of-two-load-balancing)
    - [Load Is Not What You Should Balance: Introducing Prequal](https://www.usenix.org/system/files/nsdi24-wydrowski.pdf)
    - Optional reading: [Power of Two Random Choices: A Survey of Techniques and Results](https://www.eecs.harvard.edu/~michaelm/postscripts/handbook2001.pdf) 
<br><br> 
- **Monday, Sep 15: Load balancing connections**
    - [Maglev: A Fast and Reliable Software Network Load Balancer](https://www.usenix.org/sites/default/files/nsdi16-paper-eisenbud.pdf)
<br><br> 
- **Friday, Sep 19: CPU scheduling**
    - [ZygOS: Achieving Low Tail Latency for Microsecond-scale Networked Tasks](https://marioskogias.github.io/docs/zygos.pdf)
    - [Shinjuku: Preemptive Scheduling for μsecond-scale Tail Latency](https://www.usenix.org/system/files/nsdi19-kaffes.pdf)
<br><br> 
- **Monday, Sep 22: Scheduling in LLM inference engines**
    - [Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve](https://www.usenix.org/system/files/osdi24-agrawal.pdf)
    - [Fast Distributed Inference Serving for Large Language Models](https://arxiv.org/pdf/2305.05920)
<br><br> 
- **Friday, Sep 26: Performance isolation**
    - [Caladan: Mitigating Interference at Microsecond Timescales](https://www.usenix.org/system/files/osdi20-fried.pdf)
    - [DistServe: Disaggregating Prefill and Decoding for Goodput-optimized
Large Language Model Serving](https://www.usenix.org/system/files/osdi24-zhong-yinmin.pdf)
<br><br> 
- **Monday, Sep 29: Fairness**
    - [Dominant Resource Fairness: Fair Allocation of Multiple Resource Types](https://www.usenix.org/legacy/events/nsdi11/tech/full_papers/Ghodsi.pdf)
<br><br> 
- **Friday, Oct 3: Packet scheduling**
    - [Universal Packet Scheduling](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-mittal.pdf)
    - [Programmable Packet Scheduling at Line Rate](https://dl.acm.org/doi/pdf/10.1145/2934872.2934899)
<br><br> 
- **Monday, Oct 6: No class. Prepare for midterm.**
<br><br> 
- **Friday, Oct 10: Midterm**
<br><br> 
- **Monday, Oct 13: No class. Work on projects**
<br><br> 
- **Friday, Oct 17: No class. Work on projects.**
<br><br> 
- **Monday, Oct 20: Midterm discussion**
<br><br> 
- **Friday, Oct 24: Predictable performance by design: Transactional DBs**
    - [A Top-Down Approach to Achieving Performance Predictability in Database Systems](https://web.eecs.umich.edu/~mozafari/php/data/uploads/sigmod_2017_predictability.pdf)
    - [Contention-Aware Lock Scheduling for Transactional Databases](https://www.vldb.org/pvldb/vol11/p648-tian.pdf)
<br><br>
- **Monday, Oct 27: Predictable storage**
    - [LinnOS: Predictability on Unpredictable Flash Storage with a Light Neural Network](https://www.usenix.org/system/files/osdi20-hao.pdf)
<br><br> 
- **Friday, Oct 31: Software abstractions for performance predictability**
    - [Monotasks: Architecting for Performance Clarity in Data Analytics Frameworks](http://kayousterhout.org/publications/sosp17-final183.pdf)
    - [NanoFlow: Towards Optimal Large Language Model Serving Throughput](https://arxiv.org/abs/2408.12757)
<br><br> 
- **Monday, Nov 3: Predicting system performance: Hardware**
    - [Concorde: Fast and Accurate CPU Performance Modeling with Compositional Analytical-ML Fusion](https://arxiv.org/abs/2503.23076)
    - [Forecasting GPU Performance for Deep Learning Training and Inference](https://arxiv.org/abs/2407.13853)
<br><br> 
- **Friday, Nov 7: Using ML to understand distributed system performance**
    - [Ernest: Efficient Performance Prediction for Large-Scale Advanced Analytics](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-venkataraman.pdf)
    - [On Modular Learning of Distributed Systems for Predicting End-to-End Latency](https://www.usenix.org/system/files/nsdi23-liang-chieh-jan.pdf)
<br><br> 
- **Monday, Nov 10: One model to rule them all?**
    - [Principles and Methodologies for Serial Performance Optimization](https://www.usenix.org/system/files/osdi25-park-sujin.pdf)
<br><br> 
- **Friday, Nov 14: AI-Driven Research for Systems**
    - Guest Lecture: [Audrey Cheng (UC Berkeley)](https://audreyccheng.com/)
<br><br> 
- **Monday, Nov 17: Designing agents for optimizing system performance**
  - [Glia: A Human-Inspired AI for Automated Systems Design and Optimization](https://arxiv.org/pdf/2510.27176)
<br><br> 
- **Friday, Nov 21: Is performance prediction a solved problem?**
    - [Performance Prediction for Large Systems via
Text-to-Text Regression](https://arxiv.org/pdf/2506.21718)
    - [Regression Language Models for Code](https://arxiv.org/pdf/2509.26476)
<br><br> 
- **Monday, Nov 24: Work on projects**
<br><br> 
- **Friday, Nov 28: Thanksgiving**
<br><br> 
- **Monday, Dec 1: Project presentations**
<br><br> 
- **Friday, Dec 5: Project presentations**
<br><br> 

## Assignments and Grading
The course workload will consist of the following:

- **25% of grade**: Each week, students will be required to read and provide a review of the week’s papers and attend and participate in the week’s discussion.
    - Can drop two weeks worth, no questions asked.

- **25% of grade**: Midterm  
- **50% of grade**: Students will complete a semester-long research project, in groups of 2 or 3, related to the course material.

## Instructor
<table border="0" style="border:none; box-shadow:none; background:none; margin:0; padding:0;">
  <tr>
    <td style="vertical-align:top; padding-right:24px; border:none; background:none; box-shadow:none;">
      <img src="img/rishabh.jpg" alt="Instructor Photo" width="130" style="border-radius:50%;">
    </td>
    <td style="vertical-align:middle; border:none; background:none; box-shadow:none;">
      <a href="https://rishabh246.github.io/">Rishabh Iyer</a><br>
      <a href="mailto:rishabh.iyer@berkeley.edu">rishabh.iyer@berkeley.edu</a><br>
      <b>Office Hours:</b> By appointment.
    </td>
  </tr>
</table>




