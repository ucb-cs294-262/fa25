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

## Logistics
- **Lecture/Discussion**: Mondays and Fridays from 3:30pm to 5:00pm in 306 Soda.  
- **Weekly Reading Reviews**: Due Mondays and Fridays @ noon pacific.
- **Slides for Discussion**: Due Fridays and Wednesdays @ noon pacific for Mondays and Fridays respectively.
- **Project Proposal**: Due Sep 22 @midnight pacific.
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
    - [Applying Deep Learning to the Cache Replacement Problem](https://www.cs.utexas.edu/~lin/papers/micro19c.pdf)
<br><br> 
- **Friday, Sep 12: Load balancing requests**
    - The Power of Two Random Choices [[1]](https://brooker.co.za/blog/2012/01/17/two-random.html)[[2]](https://www.haproxy.com/blog/power-of-two-load-balancing)[[3]](https://www.eecs.harvard.edu/~michaelm/postscripts/handbook2001.pdf) 
    - [Load Is Not What You Should Balance: Introducing Prequal](https://www.usenix.org/system/files/nsdi24-wydrowski.pdf)
<br><br> 
- **Monday, Sep 15: Load balancing connections**
    - [Maglev: A Fast and Reliable Software Network Load Balancer](https://www.usenix.org/sites/default/files/nsdi16-paper-eisenbud.pdf)
    - [A High-Speed Load-Balancer Design with Guaranteed Per-Connection-Consistency](https://www.usenix.org/system/files/nsdi20-paper-barbette.pdf)
<br><br> 
- **Friday, Sep 19: CPU scheduling**
    - [ZygOS: Achieving Low Tail Latency for Microsecond-scale Networked Tasks](https://marioskogias.github.io/docs/zygos.pdf)
    - [Shinjuku: Preemptive Scheduling for μsecond-scale Tail Latency](https://www.usenix.org/system/files/nsdi19-kaffes.pdf)
<br><br> 
- **Monday, Sep 22: Scheduling in LLM inference engines**
    - [Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve](https://www.usenix.org/system/files/osdi24-agrawal.pdf)
    - [Fast Distributed Inference Serving for Large Language Models](https://arxiv.org/pdf/2305.05920)
<br><br> 
- **Friday, Sep 26: Packet scheduling**
    - [Universal Packet Scheduling](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-mittal.pdf)
    - [Programmable Packet Scheduling at Line Rate](https://dl.acm.org/doi/pdf/10.1145/2934872.2934899)
<br><br> 
- **Monday, Sep 29: Fair scheduling**
    - [Dominant Resource Fairness: Fair Allocation of Multiple Resource Types](https://www.usenix.org/legacy/events/nsdi11/tech/full_papers/Ghodsi.pdf)
    - [Fair CPU scheduling](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-lottery.pdf)
<br><br> 
- **Friday, Oct 3: Performance isolation**
    - [Caladan: Mitigating Interference at Microsecond Timescales](https://www.usenix.org/system/files/osdi20-fried.pdf)
    - [PicNIC: Predictable Virtualized NIC](https://dl.acm.org/doi/pdf/10.1145/3341302.3342093)
<br><br> 
- **Monday, Oct 6: Rishabh away**
<br><br> 
- **Friday, Oct 10: Project check-in**
<br><br> 
- **Monday, Oct 13: Rishabh away**
<br><br> 
- **Friday, Oct 17: Rishabh away**
<br><br> 
- **Monday, Oct 20: Predictable performance by design: Transactional DBs**
    - [A Top-Down Approach to Achieving Performance Predictability in Database Systems](https://web.eecs.umich.edu/~mozafari/php/data/uploads/sigmod_2017_predictability.pdf)
    - [Contention-Aware Lock Scheduling for Transactional Databases](https://web.eecs.umich.edu/~mozafari/php/data/uploads/sigmod_2017_predictability.pdf)
<br><br> 
- **Friday, Oct 24: Performance predictablity for, and using, ML**
    - [Serving DNNs like Clockwork: Performance Predictability from the Bottom Up](https://www.usenix.org/system/files/osdi20-gujarati.pdf)
    - [LinnOS: Predictability on Unpredictable Flash Storage with a Light Neural Network](https://www.usenix.org/system/files/osdi20-hao.pdf)
<br><br> 
- **Monday, Oct 27: Ensuring predictable performance by avoiding overload**
    - [Overload Control for μs-scale RPCs with Breakwater](https://www.usenix.org/system/files/osdi20-cho.pdf)
    - [IODA: A Host/Device Co-Design for Strong Predictability Contract on Modern Flash Storage](https://ucare.cs.uchicago.edu/pdf/sosp21-ioda.pdf)
<br><br> 
- **Friday, Oct 31: Software abstractions for performance predictability**
    - [Monotasks: Architecting for Performance Clarity in Data Analytics Frameworks](http://kayousterhout.org/publications/sosp17-final183.pdf)
    - [NanoFlow: Towards Optimal Large Language Model Serving Throughput](https://arxiv.org/abs/2408.12757)
<br><br> 
- **Monday, Nov 3: Predicting system performance: Hardware accelerators**
    - [Performance Interfaces for Hardware Accelerators](https://rishabh246.github.io/files/lpn.pdf)
    - [Forecasting GPU Performance for Deep Learning Training and Inference](https://arxiv.org/abs/2407.13853)
<br><br> 
- **Friday, Nov 7: Using ML to understand system performance**
    - [Ernest: Efficient Performance Prediction for Large-Scale Advanced Analytics](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-venkataraman.pdf)
    - [On Modular Learning of Distributed Systems for Predicting End-to-End Latency](https://www.usenix.org/system/files/nsdi23-liang-chieh-jan.pdf)
<br><br> 
- **Monday, Nov 10: One model to rule them all**
    - [Principles and Methodologies for Serial Performance Optimization](https://www.usenix.org/system/files/osdi25-park-sujin.pdf)
<br><br> 
- **Friday, Nov 14: Is performance prediction a solved problem?**
    - [Simulating Large Systems with Regression Language Models](https://research.google/blog/simulating-large-systems-with-regression-language-models/)
<br><br> 
- **Monday, Nov 17: Using PLFM techniques to find performance bugs**
    - [Finding Adversarial Inputs for Heuristics using Multi-level Optimization](https://www.usenix.org/system/files/nsdi24-namyar-finding.pdf)
    - [Automated Reasoning and Detection of Specious Configuration in Large Systems with Symbolic Execution](https://www.usenix.org/system/files/osdi20-hu.pdf)
<br><br> 
- **Friday, Nov 21: Formally verifying performance properties**
    - [Performal: Formal Verification of Latency Properties for Distributed Systems](https://dl.acm.org/doi/pdf/10.1145/3591235)
    - [Toward Formally Verifying Congestion Control Behavior](https://dl.acm.org/doi/pdf/10.1145/3452296.3472912)
<br><br> 
- **Monday, Nov 24: TBD**
<br><br> 
- **Friday, Nov 28: Work on project**
<br><br> 
- **Monday, Dec 1: Project presentations**
<br><br> 
- **Friday, Dec 5: Project presentations**
<br><br> 

## Assignments and Grading
The course workload will consist of the following:

- **25% of grade**: Each week, students will be required to read and provide a review of the week’s papers and attend and participate in the week’s discussion.
    - Can drop two weeks worth, no questions asked.

- **25% of grade**: Each student will lead the discussion of two papers during the semester.  
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




