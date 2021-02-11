# lda-reference
Reference for Topic Modleing with  Latent Dirichlet Allocation


**Statistical Referesher**
- [Generative and Discriminative model](https://medium.com/@mlengineer/generative-and-discriminative-models-af5637a66a3)
- [Joint Probability vs Conditional Probability](https://medium.com/@mlengineer/joint-probability-vs-conditional-probability-fa2d47d95c4a)
- https://www.statisticshowto.com/likelihood-function/
- KL Divergence
    - https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained
    - https://machinelearningmastery.com/divergence-between-probability-distributions/  
- [Beta Distribution](https://towardsdatascience.com/beta-distribution-intuition-examples-and-derivation-cf00f4db57af)
    - https://www.youtube.com/watch?v=CEVELIz4WXM
- https://en.wikipedia.org/wiki/Dirichlet_distribution
- https://towardsdatascience.com/dirichlet-distribution-a82ab942a879

**Blogs explaning LDA Maths**
- https://towardsdatascience.com/light-on-math-machine-learning-intuitive-guide-to-latent-dirichlet-allocation-437c81220158
- https://towardsdatascience.com/latent-dirichlet-allocation-lda-9d1cd064ffa2
- https://medium.com/@lettier/how-does-lda-work-ill-explain-using-emoji-108abf40fa7d

**Evaluation Metric**
- https://labs.imaginea.com/how-to-measure-topic-coherence/

**Examples**
- [Scala Example](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3783546674231782/4413065072037724/latest.html)
- https://towardsdatascience.com/unsupervised-nlp-topic-models-as-a-supervised-learning-input-cf8ee9e5cf28


## Environment Setup
```
sudo apt install openjdk-8-jdk
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/

#Download and extract Spark binaries to /opt/softwares/spark-2.4.7-bin-hadoop2.7/
export SPARK_HOME=/opt/softwares/spark-2.4.7-bin-hadoop2.7/
export PATH=$SPARK_HOME/bin:$PATH
export PYSPARK_PYTHON=/opt/envs/ai4e/bin/python
export PYSPARK_DRIVER_PYTHON=/opt/envs/ai4e/bin/python
```

Shell 1
```
cd /opt/softwares/spark-2.4.7-bin-hadoop2.7/
sbin/start-all.sh # or
sbin/stop-all.sh
```

Shell 2
```
cd /path/to/project
conda activate ${YOUR_ENV}
jupyter-lab
```

My machine has following configuration...
- 6 cores with 12vCores
- 32GB RAM

Spark Standalone server:
```






#export the same on a new shell
jupyter-lab

