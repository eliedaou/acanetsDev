---
the_title: Heterospark
the_date: "Aug 8, 2014"
the_description: "HeteroSpark clusters can be regarded as Spark clusters with GPUs connected within some or all of Spark worker nodes. HeteroSpark extends original Spark with GPU acceleration option on Spark worker nodes. HeteroSpark currently supports three ways to connect GPUs with Spark workers: “local GPU” , “remote GPU”, or “no GPU”. All GPU enable/disable and connection options are configured in the cluster configuration file which is read on starting."
sponsor_url: "http://www.hugedata.com.cn/"
the_url: ../heterospark/
tags:
  - projects
  - rss
  - heterospark
image_filename: "heterospark_overview.pdf"
introduction: "&bull; Recent research advance in machine learning / deep learning algorithms and data analytics tools imposes new requirements on existing computing systems and architectures. Machine learning algorithms such as singular vector decomposition (SVD), support vector machine (SVM), principal component analysis (PCA), clustering, and neural networks are applied to extremely large data sets to extract data information and build a knowledge base. New deep learning algorithms such as autoencoder, RBM, both computing and memory intensive, have become infeasible because of the scale of data. <br /> &bull; Distributed computing platform such as Hadoop and Spark are invented to address ‘big data’ problems. However, the complex algorithms applied on the data unit in a single node still consume a large number of CPU cycles. <br /> &bull; In the latest technology, GPUs have been leveraged as accelerators in speeding up complex workloads thanks to the density of the cores and their power efficiency."
motivation: "We are motivated to address the challenges with heteroge-neous architecture where GPUs work side by side with CPUs at the worker nodes of a compute cluster. Such heterogeneous architecture has three design objectives: <br /> &bull; Acceleration: Integrate GPU accelerators into current Spark platform to achieve further data parallelism and algorithm acceleration. <br /> &bull; Plug-n-play: “Plugin” style design – current Spark applications can choose to enable/disable GPU acceleration. <br /> &bull; Portability: Existing Spark code can be easily ported to the heterogeneous platform."
---
