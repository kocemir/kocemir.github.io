<p align='justify'>
I am a M.Sc. student at the Electrical and Electronics Engineering department in Bilkent University/UMRAM under the supervision of <a href="http://aykut.koc.bilkent.edu.tr/" target="_blank"> Assoc. Prof. Aykut Koc</a>. My primary research focus centers on <b> Machine Learning </b>,<b> Deep Learning </b> and <b> Signal Processing </b>with a strong emphasis on the statistical and mathematical foundations underpinning these fields. I seek to design intelligent learning systems that can be seamlessly integrated into multidisciplinary teams. I have had the privilege of gaining hands-on experience during my undergraduate studies, particularly in the development of cutting-edge deep learning-based Brain-Computer Interface (BCI) systems. As part of my master's studies, I have worked on the intersection of signal processing, time series analysis, image processing and natural language processing. I believe that science should be open and reproducible and
freely publish my research code to <a href="https://github.com/kocemir" target="_blank">GitHub</a>.
</p><br>




## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td>
      <span class='cvdate'>2021&nbsp;-&nbsp;2024</span>
      <strong>M.Sc. in Electrical and Electronics Engineering</strong>   
      <br>
      Bilkent University | Ankara, TR
      <br>
      Advisor: <a href="http://aykut.koc.bilkent.edu.tr/" target="_blank"> Assoc. Prof. Aykut Koc</a>
    </td>
  </tr>
  <tr>
    <td>
      <span class='cvdate'>2016&nbsp;-&nbsp;2021</span>
      <strong>B.S. in Electronics Engineering</strong>
      <br>
      Sabancı University | Istanbul, TR
    </td>
  </tr>
</table>




## <i class="fa fa-chevron-right"></i> Publications

[<a href="https://scholar.google.com/citations?user=eUaNFf0AAAAJ&hl=tr&oi=ao">Google Scholar</a>]
<br>

<table class="table table-hover">


<tr id="tr-amos2023tutorial" style="background-color: #ffffd0">
<td align='right' style='padding-left:0;padding-right:0;'>

1.
</td>
<td>
<a href='https://ieeexplore.ieee.org/document/9978636' target='_blank'><img src="images/publications/frac_v3.png" onerror="this.style.display='none'" class="publicationImg" /></a> 
<em><a href='https://ieeexplore.ieee.org/document/9978636' target='_blank'>Fractional Fourier Transform in Time Series Prediction</a> </em> 
[<a href='javascript:;'
    onclick='$("#frac").toggle()'>Abstract</a>]  <br>
 <strong>Emirhan&nbsp;Koç</strong>, Aykut Koç
<br>
IEEE Signal Processing Letters, 2022<br>

<div id="frac" style="text-align: justify; display: none" markdown="1">
Several signal processing tools are integrated into machine learning models for performance and computational cost improvements. Fourier transform (FT) and its variants, which are powerful tools for spectral analysis, are employed in the prediction of univariate time series by converting them to sequences in the spectral domain to be processed further by recurrent neural networks (RNNs). This approach increases the prediction performance and reduces training time compared to conventional methods. In this letter, we introduce fractional Fourier transform (FrFT) to time series prediction by RNNs. As a parametric transformation, FrFT allows us to seek and select better-performing transformation domains by providing access to a continuum of domains between time and frequency. This flexibility yields significant improvements in the prediction power of the underlying models without sacrificing computational efficiency. We evaluated our FrFT-based time series prediction approach on synthetic and real-world datasets. Our results show that FrFT gives rise to performance improvements over ordinary FT.
</div>

</td>
</tr>

<tr id="tr-amos2023tutorial" style="background-color: #ffffd0">
<td align='right' style='padding-left:0;padding-right:0;'>

2.
</td>
<td>
<a href='https://ieeexplore.ieee.org/document/9964035' target='_blank'><img src="images/publications/transformer_renewed.png" onerror="this.style.display='none'" class="publicationImg" /></a> 
<em><a href='https://ieeexplore.ieee.org/document/9964035' target='_blank'>Fractional Fourier Transform in Time Series Prediction</a> </em> 
[<a href='javascript:;'
    onclick='$("#mvtsit").toggle()'>Abstract</a>]  <br>
Ayberk Yarkın Yıldız, <strong>Emirhan&nbsp;Koç</strong>, Aykut Koç
<br>
IEEE Signal Processing Letters, 2022 <br>

<div id="mvtsit" style="text-align: justify; display: none" markdown="1">
Processing time series with missing segments is a fundamental challenge that puts obstacles to advanced analysis in various disciplines such as engineering, medicine, and economics. One of the remedies is imputation to fill the missing values based on observed values properly without undermining performance. We propose the Multivariate Time-Series Imputation with Transformers (MTSIT), a novel method that uses transformer architecture in an unsupervised manner for missing value imputation. Unlike the existing transformer architectures, this model only uses the encoder part of the transformer due to computational benefits. Crucially, MTSIT trains the autoencoder by jointly reconstructing and imputing stochastically-masked inputs via an objective designed for multivariate time-series data. The trained autoencoder is then evaluated for imputing both simulated and real missing values. Experiments show that MTSIT outperforms state-of-the-art imputation methods over benchmark datasets.
</div>

</td>
</tr>


<tr id="tr-amos2023tutorial" style="background-color: #ffffd0">
<td align='right' style='padding-left:0;padding-right:0;'>

3.
</td>
<td>
<em><a href='https://ieeexplore.ieee.org/document/9477841' target='_blank'>Adaptive Boosting of DNN Ensembles for Brain-Computer Interface Spellers</a> </em> 
[<a href='javascript:;'
    onclick='$("#bci").toggle()'>Abstract</a>]  <br>
Osman Berke Güney, <strong>Emirhan&nbsp;Koç</strong>, Can Aksoy, Yiğit Çatak, Şuayip S. Arslan, Hüseyin Özkan
<br>
IEEE Signal Processing and Communication Applications Conference (SIU), 2021 <br>

<div id="bci" style="text-align: justify; display: none" markdown="1">
Steady-state visual evoked potentials (SSVEP) are commonly used in brain computer interface (BCI) applications such as spelling systems, due to their advantages over other paradigms. In this study, we develop a method for SSVEP-based BCI speller systems, using a known deep neural network (DNN), which includes transfer and ensemble learning techniques. We test performance of our method on publicly available benchmark and BETA datasets with leave-one-subject-out procedure. Our method consists of two stages. In the first stage, a global DNN is trained using data from all subjects except one subject that is excluded for testing. In the second stage, the global model is fine-tuned to each subject whose data are used in the training. Combining the responses of trained DNNs with different weights for each test subject, rather than an equal weight, provide better performance as brain signals may differ significantly between individuals. To this end, weights of DNNs are learnt with SAMME algorithm with using data belonging to the test subject. Our method significantly outperforms canonical correlation analysis (CCA) and filter bank canonical correlation analysis (FBCCA) methods.
</div>

</td>
</tr>


</table>



## <i class="fa fa-chevron-right"></i> Teaching
<table class="table table-hover">
<tr>
  <td style='padding-right:0'><strong>Neural Networks</strong> (EEE 443/543), TA</td>
  <td class='col-md-2' style='text-align:right; padding-left:0;'>Fall 2023</td>
</tr>
<tr>
  <td style='padding-right:0'><strong>Digital Signal Processing</strong> (EEE 424), TA</td>
  <td class='col-md-2' style='text-align:right; padding-left:0;'>Fall 2022, Spring 2023</td>
</tr>
<tr>
  <td style='padding-right:0'><strong>Signals and Systems</strong> (EEE 321), TA</td>
  <td class='col-md-2' style='text-align:right; padding-left:0;'>Fall 2021, Spring 2022</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
<tr>
  <td class='col-md-2'>Programming</td>
  <td>
C++,  Python, Matlab
  </td>
</tr>
<tr>
  <td class='col-md-2'>Frameworks</td>
  <td>
Pytorch, Tensorflow, HuggingFace
  </td>
</tr>
<tr>
  <td class='col-md-2'>Tools</td>
  <td>
 LaTEX, Bash, VSCode, EEGLAB, Qt Designer
  </td>
</tr>
</table>

<br>

Template is from <a href="https://bamos.github.io/" target="_blank"> Brandon Amos</a>
