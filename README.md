
# Galaxy classification and redshift derivation with Machine Learning
![alt text](https://www.sdss.org/wp-content/uploads/2014/05/segue.jpg)

This repository contains:

<ul>
    <li> a <a href='https://github.com/lvallini/Galaxy_classification_withML/blob/main/sdss_class_bpt_colors.ipynb'>Jupyter Notebook</a> where galaxies from the SDSS survey are classified with ML methods.
The objects can be divided into two MAJOR CLASSES (GALAXIES and QSO) and in 6 SUB-CLASSES (AGN, AGN BROADLINE, BROADLINE, STARBURST, STARBURST BROADLINE, STARFORMING, STARFORMING BROADLINE). The classification is performed with two different ML algorithms: a KNN method, and a Random Forest classification. Both are implemented with <a href='https://scikit-learn.org/stable/index.html'>scikit-learn</a>. Given the class imbalance, the algorithm has been optimized with the dedicated <a href='https://imbalanced-learn.org/stable/'>imbalanced-learn</a> library.

<li> a <a href='https://github.com/lvallini/Galaxy_classification_withML/blob/main/sdss_class_bpt_colors.ipynb'>Jupyter Notebook</a> where the cosmological distance (redshift) of galaxies from the SDSS survey is determined with ML. 
  In this case the cosmological distance of both GALAXIES and QSO is determined with Random Forest regression implemented with <a href='https://scikit-learn.org/stable/index.html'>scikit-learn</a>.

</ul>
  
