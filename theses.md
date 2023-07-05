---
layout: page
title: Available theses and projects
permalink: /theses/
---

The following is a list of research fields available for master's theses and master/Ph.D. projects. Each research field may offer multiple thesis topics, aiming to familiarize students with current and relevant areas of interest in the field of artificial intelligence, spanning both industrial and academic domains. All theses are conducted in collaboration with the Scuola Superiore Sant'Anna of Pisa in the TeCIP institute area (CNR).

Please [contact me](mailto:giulio.rossolini@santannapisa.it) to get more details and schedule a meeting. 
If you would like to address other topics close to safe and secure aspects of AI, feel free to [contact me](mailto:giulio.rossolini@santannapisa.it) too!

<em>General requirements (not hard) </em>: a basic knowledge of deep neural networks and computer vision tasks; a minimum level of programming skills with python and classic AI libraries (e.g., Torch, Tensorflow, SciPy).
<br>

<hr>

### 1 - Simulators and Synthetic Datasets for Testing Computer Vision Algorithms in Driving Scenarios


<table>
<tr>
<p>
To address the challenge of acquiring extensive and annotated datasets for computer vision models in autonomous domains, the presence of reliable simulators and suitable synthetic datasets is of utmost importance.
The following topics explore various aspects related to simulators and synthetic datasets and contribute to the advancement of computer vision algorithms in driving scenarios, particularly in terms of robustness, generalization, and transferability to real-world domains:
<br>

 <ol>
<li> Evaluating the Robustness of Computer Vision Models Against <b> Attacks and Environmental Changes </b>. <br></li>
<li> Improving the Testing of Computer Vision Algorithms against <b> Out-of-Distribution Samples </b> through Simulators.<br></li>
<li> Reducing the <b> Domain Shift for Domain Adaptation </b> through Simulators and Games for Synthetic Datasets.<br></li>
</ol> 

</p>
</tr>
<tr style="padding:20px;width:40%;vertical-align:middle; horizontal-align:middle">
<p style="text-align:center; margin-top: 0px; margin-bottom: 0px">
  <img src="{{ site.baseurl }}/images/temp/simulator_gta.png" width="70%" height="80%">
  <figcaption style="text-align:center"> Fig. - (a) CarlaGear framework [<a href="https://arxiv.org/abs/2206.04365">REF</a>]; (b) GTA Dataset [<a href="https://arxiv.org/abs/1608.02192v1">REF</a>]</figcaption>
</p>
</tr>
</table>
<hr>


### 2 -   Physically-Realizable Adversarial Attacks in Real-World Machine Learning Applications
<table cellpadding="0" cellspacing="0" width="100%" border-collapse="collapse">
<tr>
<p>
With the increasing adoption of machine learning models in real-world applications, concerns have arisen about their vulnerability to physically-realizable adversarial attacks. The following topics delve into the phenomenon of adversarial attacks in real-world scenarios and explore methods to mitigate their impact, while also considering potential new threats. The study specifically addresses the following aspects:
   <ul>
<li> <b>Run-time Defense Monitoring </b> of Internal DNNs Behaviors Against Physical Attacks.<br></li>
<li> Reviewing <b> Certification Approaches </b> for Assessing Robustness against Physical Attacks. <br></li>
<li> Examining the <b> Transferability of Physical Attacks </b> and <b> Backdoor Attack Scenarios </b>.
 <br></li>
</ul> 
</p>

</tr>
<tr>
<tr style="padding:20px;width:40%;vertical-align:middle; horizontal-align:middle">
        <p style="text-align:center; margin-top: 0px; margin-bottom: 0px">
          <img src="{{ site.baseurl }}/images/temp/adversarial_patch.png" width="70%" height="100%">  
          <figcaption style="text-align:center"> Fig. -Adversarial patch attack for image classification [<a href="https://arxiv.org/abs/1712.09665">REF</a>]</figcaption>
        </p>  
</tr>
</tr>
</table>



<hr>

### 3 - Recent Topics in Secure AI
<table cellpadding="0" cellspacing="0" width="100%" border-collapse="collapse">
<tr>
<p>
The following theses delve into emerging areas of secure AI, providing students with the opportunity to explore the literature, review advancements, and address specific challenges related to the development of safe and robust AI systems.
<ol>
<li> <b>Deep Steganography</b> - Exploring Generative Models and High-Resolution Datasets. 
This project focuses on the concept of deep steganography, which involves hiding information within data. The student will begin by gaining a comprehensive understanding of the existing literature on deep steganography. Then, the thesis will delve into the challenges associated with steganography using generative models and high-resolution datasets.
<br></li>
<li> Addressing the Transferability of <b>Black-Box Attacks</b>. This thesis focuses on black-box adversarial attacks and aims to investigate the state-of-the-art techniques in this area. The student will explore methods to improve the transferability of such attacks across different models, thus enhancing the understanding and defense mechanisms against black-box attacks in AI systems. <br></li>
<li> Studying <b>Adversarial Perturbations in the Fourier Domain</b>. This research aims to investigate adversarial perturbations in the frequency domain as a means to enhance and understand the robustness of computer vision models against adversarial attacks from a new perspective. <br></li>
</ol> 
</p>
</tr>
<tr>
<tr style="padding:20px;width:40%;vertical-align:middle; horizontal-align:middle">
        <p style="text-align:center; margin-top: 0px; margin-bottom: 0px">
          <img src="{{ site.baseurl }}/images/temp/stegano.png" width="70%" height="100%">  
          <figcaption style="text-align:center">Fig. -Exaple of a Deep Steganography scheme [<a href="https://arxiv.org/abs/2101.00350">REF</a>].</figcaption>
        </p>  
</tr>

<tr style="padding:20px;width:40%;vertical-align:middle; horizontal-align:middle">
        <p style="text-align:center; margin-top: 0px; margin-bottom: 0px">
          <img src="{{ site.baseurl }}/images/thesis/frequency_analysis.jpg" width="70%" height="100%">  
          <figcaption style="text-align:center">Fig. - Decoupling the frequencies of an original image and a perturbed image in the Fourier domain.
          </figcaption>
        </p>  
</tr>
</tr>
</table>


<hr>


### 4 -  Domain Adaptation for Autonomous Domains
<table cellpadding="0" cellspacing="0" width="100%" border-collapse="collapse">
<tr>
<p> 
Domain adaptation techniques are crucial for enhancing the accuracy of neural models when real-world annotated samples are scarce, especially in outdoor environments like the railway and driving domains. These theses provide opportunities to tackle recent challenges in the field of domain adaptation.
   <ul>
<li> Unsupervised Domain Adaptation for <b>Railway Segmentation</b>. The student will explore methods to adapt semantic segmentation models to railway datasets without the need for additional annotations. <br></li>
<li> <b>Self-learning </b> Approaches with Label Refinements. This project aims to review and improving pseudo-labelling approaches for unsupervised domain adaptation.  <br></li>
<li> Reviewing <b> Style Transfer </b> Strategies for Domain Adaptation. This research involves reviewing and analyzing image-to-image strategies for domain adaptation. The student will explore state-of-the-art methods that align images from source domain to target domains and so enabling effective knowledge transfer. <br></li>
</ul> 
</p>

</tr>
<tr>
<tr style="padding:20px;width:40%;vertical-align:middle; horizontal-align:middle">
        <p style="text-align:center; margin-top: 0px; margin-bottom: 0px">
          <img src="{{ site.baseurl }}/images/temp/style_transfer.png" width="50%" height="80%">  
          <figcaption style="text-align:center">Fig. - Example of style transfer from a synthetic domain to a real-world domain.</figcaption>
        </p>  
</tr>
</tr>
</table>

<hr>

### Other topics (contact me for further details)
* Safe and robustness topics with Transformers
* Data anonimization in autonomous driving with DeepFake models
* Attention mechanisms for semantic segmentation and object detection

<hr>

### Contact
[giulio.rossolini@santannapisa.it](mailto:giulio.rossolini@santannapisa.it)

#### Last update
July 5, 2023