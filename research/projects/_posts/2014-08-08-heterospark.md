---
the_title: Heterospark
the_date: "Aug 8, 2014"
the_description: "HeterSpark is to extend the big data computing framework Spark on to GPUs to accelerate complex workloads"
sponsor_url: "http://www.hugedata.com.cn/"
the_url: ../heterospark/
tags:
  - projects
  - rss
  - heterospark
image_filename: "heterospark_overview.png"
introduction: " <h3> Introduction </h3> <p>&bull; Recent research advance in machine learning / deep learning algorithms and data analytics tools imposes new requirements on existing computing systems and architectures. Machine learning algorithms such as singular vector decomposition (SVD), support vector machine (SVM), principal component analysis (PCA), clustering, and neural networks are applied to extremely large data sets to extract data information and build a knowledge base. New deep learning algorithms such as autoencoder, RBM, both computing and memory intensive, have become infeasible because of the scale of data. <br /> &bull; Distributed computing platform such as Hadoop and Spark are invented to address ‘big data’ problems. However, the complex algorithms applied on the data unit in a single node still consume a large number of CPU cycles. <br /> &bull; In the latest technology, GPUs have been leveraged as accelerators in speeding up complex workloads thanks to the density of the cores and their power efficiency.</p>"
motivation: "<h3> Motivation </h3> <p> We are motivated to address the challenges with heteroge-neous architecture where GPUs work side by side with CPUs at the worker nodes of a compute cluster. Such heterogeneous architecture has three design objectives: <br /> &bull; Acceleration: Integrate GPU accelerators into current Spark platform to achieve further data parallelism and algorithm acceleration. <br /> &bull; Plug-n-play: “Plugin” style design – current Spark applications can choose to enable/disable GPU acceleration. <br /> &bull; Portability: Existing Spark code can be easily ported to the heterogeneous platform.</p>"
publications: "<h3>Publications</h3> <br /> &bull; Peilong Li, Yan Luo, Ning Zhang and Yu Cao, HeteroSpark: A Heterogeneous CPU/GPU Spark Platform for Machine Learning Algorithms, IEEE Internation Conference on Network, Architecture and Storage 2015, Boston, MA, August 6-7, 2015  <br /> &bull;  Peilong Li, Yan Luo, Yu Cao and Ning Zhang, HeteroSpark: A Heterogeneous CPU/GPU Spark Platform for Deep Learning Algorithms, Spark Summit East, March 2015 <br />"
currentStatus: "<h3> Current Status</h3>
<ol>
<li>Rewriting RMI communication protocol by using Spring framework.</li>
<li>Developing JNI wrapper automator by using Swig.</li>
<li>Working on a list of machine learning algorithms.</li>
</ol>"
downloads: "<h3>Downloads:</h3> <em>Coming soon </em>"
---
