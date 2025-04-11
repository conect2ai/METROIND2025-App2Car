&nbsp;
&nbsp;
<p align="center">
  <img width="800" src="./figures/conecta_logo.png" />
</p> 

&nbsp;

# Timing Challenges in Vehicular TinyML: Characterizing End-to-End Latency

<!-- ### ✍🏾 Autores: [Hilton Machado](https://github.com/HiltonThallyson), [Matheus Andrade](https://github.com/DinizMaths), [Marianne Diniz](https://github.com/MarianneDiniz), [Ivanovitch Silva](https://github.com/ivanovitchm) -->

---

## 1. 📖 Abstract

The increasing integration between IoT and embedded machine learning has created new opportunities for real-time vehicular applications. However, mobile and heterogeneous environments still face latency and communication challenges that impact the reliability of such systems. This paper presents an empirical performance analysis of a vehicular sensing pipeline implemented through the App2Car mobile application, which collects data from vehicles using OBD-II interfaces, performs on-device inference using TinyML algorithms, and transmits results to the cloud. A case study involved two OBD-II device models, two smartphone models, and six vehicles from different manufacturers. The analysis focused on the temporal behavior of three key stages: PID request time, local inference time, and cloud transmission latency. Results highlight the impact of hardware configurations and environmental conditions on system performance, offering valuable insights for the design of low-latency vehicular IoT solutions using commodity hardware.

---

## 🚀 About the code


The complete data analysis is implemented in the `./main_app2car.ipynb` notebook. This notebook includes all the code necessary for processing the data, measuring latency at each stage of the pipeline, and visualizing the experimental results. It serves as a comprehensive guide for evaluating and optimizing the performance of low-latency vehicular IoT applications using TinyML.

---

## 🌎 About Conect2AI

The research group [**Conect2AI**](http://conect2ai.dca.ufrn.br) is composed of undergraduate and graduate students from the Federal University of Rio Grande do Norte (UFRN). Our mission is to apply Artificial Intelligence (AI) and Machine Learning to emerging fields.

### 🎯 Nossas áreas de atuação incluem:

- **Embedded Intelligence and IoT**: Optimizing resource management and energy efficiency in connected environments.

- **Energy Transition and Mobility**: Leveraging AI to optimize energy consumption in connected vehicles and promote more efficient and sustainable mobility.

---