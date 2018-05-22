# ML4JavaDevs (https://www.linkedin.com/groups/8667046)

### Initial tool requirements for learning objectives:
1. In this iteration create simple Java tools which typically comprise a single class with a main method.
2. We will keep Utility classes to a minimum
3. We will adopt the simplest coding style possible, so it lends itself to easy readability 
4. We should refrain from using frameworks for logging and configuration to keep readability up (so use System.out.println instead of log4j, SLF4K or say the Properties or class bundled with the standard JDK instead of the Spring framework

### What we will be coding and learning:
1. Our first learning problem (Intro2MLTutorial1KMeans.java)
  - Create a 2D synthetic data set with two Gaussians
  - Run K-Means Clustering animation
  - Show how the centroids start out
  - Show how the centroids drift apart
  - What did the machine learn?
  - Unpack the algorithm and discuss how it works
  - Discuss the concept of distance and how it relates to the concept of similarity
  - Ask the question: is there something out of place -- do some points belong to the wrong cluster
2. Our second learning problem (Intro2MLTutorial2KMeansDistanceProblem.java)
  - Create the same 2D Gaussians except multiply one dimension by a 1000 (say measurement in inches vs. yards)
  - Run K-Means Clustering animation
  - What just happened?
  - Let's revisit the Pythagorean theorem
  - Let's normalize both dimensions (use a simple normalization -- consider the Z-score)
  - Run K-Means Clustering animation again
3. Our third learning problem (Intro2MLTutorial2KMeansWhatIsK.java)
  - Create 2D Gaussians except let's create 5
  - Run K-Means Clustering animation with K=2
  - What just happened?
  - Run K-Means Clustering animation with K=3
  - What just happened?
  - Run K-Means Clustering animation with K=5
  - What just happened?
  - Run K-Means Clustering animation with K=7
  - What just happened?
4. Our fourth learning problem (Intro2MLTutorial2KMeansVsIris.java)
  - Load the Iris dataset
  - Briefly discuss the iris dataset
  - Visualize the iris dataset
  - Point out the number of dimensions
  - Run a K-means on it
  - Discuss results
5. Our fifth learning problem -- high dimensional cubes are spiky (Intro2MLSpikyCubes.java)
  - Let's discuss what an N-dimensional cube looks like
  - Let's generate 2 N-dimensional Gaussians where N > 20
  - Apply K-Means
  - What happened?
  - As a bonus exercise compare the percentage of the volume contained in the corners of 3-dimensional cube vs. a 20-dimensional cube
  - Revisit the notion of distance
  - Discuss why higher dimensions may be a problem
  - Discussion
  - What was the machine learning?
  - What is the model?
  - What do you think about Box’s famous quote: "All models are wrong, but some are useful."

### Supporting material:
1. Introduction to Statistical Learning -- http://www-bcf.usc.edu/~gareth/ISL/ -- get the full book for free (pdf format)
2. Lecture 13.2 — Clustering | KMeans Algorithm — [ Machine Learning | Andrew Ng ] -- https://www.youtube.com/watch?v=hDmNF9JG3lo
3. https://github.com/haifengl/smile/tree/master/shell/src/universal/data/clustering

### Academic References
1. MacQueen, J. (1967) Some methods for classification and analysis of multivariate observations. In Proceedings of the Fifth Berkeley Symposium on Mathematical Statistics and Probability, eds L. M. Le Cam & J. Neyman, 1, pp. 281–297. Berkeley, CA: University of California Press. -- https://bit.ly/2LeL0Lp
2. Tapas Kanungo, David M. Mount, Nathan S. Netanyahu, Christine D. Piatko, Ruth Silverman, and Angela Y. Wu. An Efficient k-Means Clustering Algorithm: Analysis and Implementation. IEEE TRANS. PAMI, 2002. -- https://bit.ly/2KzdZIY
3. D. Arthur and S. Vassilvitskii. "K-means++: the advantages of careful seeding". ACM-SIAM symposium on Discrete algorithms, 1027-1035, 2007. -- https://stanford.io/2rT1IrV
4. Anna D. Peterson, Arka P. Ghosh and Ranjan Maitra. A systematic evaluation of different methods for initializing the K-means clustering algorithm. 2010.
4. Forgy, E. W. (1965) Cluster analysis of multivariate data: efficiency vs interpretability of classifications. Biometrics 21, 768–769.
5. Hartigan, J. A. and Wong, M. A. (1979). A K-means clustering algorithm. Applied Statistics 28, 100–108. -- https://bit.ly/2hDNuFB
6. Lloyd, S. P. (1957, 1982) Least squares quantization in PCM. Technical Note, Bell Laboratories. Published in 1982 in IEEE Transactions on Information Theory 28, 128–137. -- https://bit.ly/2KD64dE 





