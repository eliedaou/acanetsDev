---
the_title: Heterospark
the_date: "Aug 8, 2014"
the_description: "HeteroSpark clusters can be regarded as Spark clusters with GPUs connected within some or all of Spark worker nodes. Figure 1 gives the overview of the HeteroSpark architecture. Basically, HeteroSpark extends original Spark with GPU acceleration option on Spark worker nodes. HeteroSpark currently supports three ways to connect GPUs with Spark workers: “local GPU” (GPU resides on the same Spark worker machine and interacts with the CPU via the PCIe bus), “remote GPU” (GPU resides on different Spark worker over the net- work), or “no GPU”. All GPU enable/disable and connection options are configured in the cluster configuration file which is read on starting."
sponsor_url: "http://www.hugedata.com.cn/"
the_url: ../heterospark/
tags:
  - projects
  - rss
  - heterospark
introduction: "&bull; Recent research advance in machine learning / deep learning algorithms and data analytics tools imposes new requirements on existing computing systems and architectures. Machine learning algorithms such as singular vector decomposition (SVD), support vector machine (SVM), principal component analysis (PCA), clustering, and neural networks are applied to extremely large data sets to extract data information and build a knowledge base. New deep learning algorithms such as autoencoder, RBM, both computing and memory intensive, have become infeasible because of the scale of data. <br /> &bull; Distributed computing platform such as Hadoop and Spark are invented to address ‘big data’ problems. However, the complex algorithms applied on the data unit in a single node still consume a large number of CPU cycles. <br /> &bull; In the latest technology, GPUs have been leveraged as accelerators in speeding up complex workloads thanks to the density of the cores and their power efficiency." 
introduction2: ""
introduction3: ""

---
