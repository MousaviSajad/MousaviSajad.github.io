---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=f1So9sUAAAAJ&hl=en&oi=ao).

Journals
==========
* **Mousavi S.**, Fotoohinasab A., Afghah F. (2020) Single-modal and multi-modal false arrhythmia alarm
reduction using attention-based convolutional and recurrent neural networks. PLoS ONE Journal 15(1):
e0226990. https://doi.org/10.1371/journal.pone.0226990. [[link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0226990)] <br />
* **Mousavi S.**, Afghah, F., & Acharya, U. R. (2019). SleepEEGNet: Automated Sleep Stage Scoring with
Sequence to Sequence Deep Learning Approach. PloS ONE Journal, doi: 10.1371/journal.pone.0216456. [[link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0216456)] <br />
* **Mousavi S.**, Afghah, F., Ashdown, J. D., & Turck, K. (2019). Use of a quantum genetic algorithm for
coalition formation in large-scale UAV networks. Elsevier Ad Hoc Networks Journal, 87, 26-36. [[link](https://www.sciencedirect.com/science/article/abs/pii/S1570870518303044)]<br />
* **Mousavi S. S.**, Schukat, M., & Howley, E. (2017). Traffic Light Control Using Deep Policy-Gradient and
Value-Function Based Reinforcement Learning. Journal of IET Intelligent Transport Systems, DOI:
10.1049/iet-its.2017.0153. [[link](https://ieeexplore.ieee.org/document/8061182)] <br />
* Habibalahi, A., Moghari, M. D., Samadian, K., **Mousavi S. S.**, & Safizadeh, M. S. (2015). Improving
pulse eddy current and ultrasonic testing stress measurement accuracy using neural network data fusion.
Journal of IET Science, Measurement & Technology, 9(4), 514-521. [[link](https://ieeexplore.ieee.org/document/7138680?reload=true&arnumber=7138680&filter%3DAND(p_IS_Number:7138671)=)]<br />
* **Mousavi S. S.**, Ghazanfari, B., Mozayani, N., & Jahed-Motlagh, M. R. (2014). Automatic abstraction
controller in reinforcement learning agent via automata. Elsevier Applied Soft Computing Journal,
25, 118-128. [[link](https://www.sciencedirect.com/science/article/abs/pii/S1568494614004475)]<br />
Moghaddam, A. P., **Mousavi S. S.** (2012). Learning Decision Tree Using Neural Network for Stability
and Flexibility. Iranian Journal of Medical Informatics, IJMI. 1(3), 39-44. [[link](http://ijmi.ir/index.php/IJMI/article/view/25)]

Conferences 
==========
Ghazanfari, B., Afghah, F., Najarian, K., **Mousavi S.**, Gryak, J., Todd, J., (July 2019). An Unsupervised
Feature Learning Approach to Reduce False Alarm Rate in ICUs, 41th Annual International Conference of
the IEEE Engineering in Medicine and Biology Society (EMBC’19). <br />
**Mousavi S.**, & Afghah, F. (2019). Inter-and intra-patient ECG heartbeat classification for arrhythmia
detection: a sequence to sequence deep learning approach. In ICASSP 2019-2019 IEEE International
Conference on Acoustics, Speech and Signal Processing (ICASSP’19), pp. 1308-1312. <br />
**Mousavi S.**, Afghah, F., Razi, A., & Acharya, U. R. (2019). ECGNET: Learning where to attend for
detection of atrial fibrillation with deep visual attention. In 2019 IEEE EMBS International Conference on
Biomedical & Health Informatics (BHI’19). IEEE. <br />
* **Mousavi S.**, Afghah, F., Ashdown, J. D., & Turck, K. (April 2018). Leader-follower based Coalition
Formation in Large-scale UAV Networks, A Quantum Evolutionary Approach, INFOCOM, Workshop on
Wireless Sensor, Robot, and UAV Networks (Best Paper Recognition). <br />
Zaeri-Amirani, M., Afghah, F.,**Mousavi S.** (July 2018). A Feature Selection Method Based on Shapley
Value to False Alarm Reduction in ICUs, A Genetic-Algorithm Approach, 40th Annual International
Conference of the IEEE Engineering in Medicine and Biology Society (EMBC’18). <br />

* **Mousavi S. S.**, Schukat, M. & Howley, E. (2017). Traffic Light Control Using Deep Reinforcement
Learning Agent. NUIG UL 7th Postgraduate Research Day 2017. <br />
**Mousavi S. S.**, Schukat, M., Howley, E., & Mannion, P. (2017). Applying Q(λ)-learning in Deep
Reinforcement Learning to Play Atari Games. Adaptive Learning Agents (ALA) Workshop at Sixteenth
International Conference on Autonomous Agents and Multiagent Systems (AAMAS’17). <br />
**Mousavi S. S.**., Schukat, M. & Howley, E. (2016). Deep Learning Methodologies in Combination with
Reinforcement Learning Techniques. NUIG UL 6th Postgraduate Research Day 2016.<br />
**Mousavi S. S.**, Schukat, M., Howley, E., Borji, A., & Mozayani, N. (2016). Learning to predict where to
look in interactive environments using deep recurrent q-learning. arXiv preprint arXiv:1612.05753. <br />
**Mousavi S. S.**, Schukat, M., & Howley, E. (2016, September). Deep reinforcement learning: An
overview. In Proceedings of SAI Intelligent Systems Conference (pp. 426-440). Springer, Cham. <br />


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
