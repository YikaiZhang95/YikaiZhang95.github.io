<h1 align="center">Hi, I'm Yikai Zhang👋</h1>
<p align="center">
<a href="https://scholar.google.com/YOUR_LINK_HERE"><img alt="Google Scholar" src="https://img.shields.io/badge/Scholar-4285F4?logo=google-scholar&logoColor=white"></a>
<a href="https://www.linkedin.com/in/yikai-zhang-66a01b160"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
<a href="https://pypi.org/user/yikaizhang/"><img alt="PyPI" src="https://img.shields.io/badge/PyPI-3775A9?logo=pypi&logoColor=white"></a>
<a href="mailto:yikai.zhang@uiowa.edu"><img alt="Email" src="https://img.shields.io/badge/Email-181717?logo=gmail&logoColor=white"></a>
<img alt="Visitors" src="https://komarev.com/ghpvc/?username=YikaiZhang95&style=flat">
</p>
<meta name="description" content="This is my Github page. I'm a developer and I share my code here.">
<meta name="keywords" content="dcode, github, page, Yikai Zhang, torch, svm, high dimentional, kernel, uiowa">

### 🧑‍🔬 About

I'm a statistical Ph.D. candidate with 10+ years of experience in statistics and machine learning:
- Developed innovative algorithms, including the Finite Smoothing Algorithm and Generalized Takeuchi’s Information Criteria, transforming SVM and large-margin classifiers.
- Proficient in Python, R, SQL, and Fortran, delivering high-performance tools and **open-source packages**; integrate **Fortran/CUDA** kernels.
- Published author with research showcased at **ICML**.
- Successfully collaborated across diverse industries, including insurance and chemical manufacturing, to deliver impactful tools.

**Now I'm open to work!**

### 🛠️ Tech Stack
- **Languages**: Python, R, CUDA C/C++, Fortran, SQL
- **ML**: PyTorch, scikit‑learn, XGBoost
- **Systems**: HPC, GitHub Actions, packaging (PyPI/R‑pkg)

### 💼 Work Experience

**Data Science Intern** — UFG Insurance _(Summer 2024)_  
- Refitted a bodily injury (BI) cost model in commercial auto (CA) insurance using XGBoost; leveraged large language models (LLMs) to extract, validate, and interpret multi-source data, improving prediction  accuracy by 15% and significantly enhancing model robustness.  
- Built a Python Shiny tool integrating SQL and LLMs to estimate insurable replacement value.
- Automated fraud detection from police reports with an LLM-based backend which significantly boosts claim flagging efficiency.  

**Data Science Intern** — Dow Inc. _(Summer 2023)_  
- Developed a DOE simulation app (R + Shiny) that improved design efficiency by 50% and computation speed by 35%. 
- Enhanced usability for statisticians and engineers, achieving 90%+ user satisfaction. 

**Graduate Researcher** — University of Iowa _(2019–Present)_  
- Research on **large-scale kernel SVMs**, **kernel logistics regression**, GPU acceleration, and insurance risk modeling.  
- Built open-source packages (**TorchSVM, hdsvm, SAFE, GTIC**) in PyTorch and R.  
- Integrated Fortran/CUDA kernels for high-performance computing.  


### ⭐ Featured Projects


#### 1)  Efficient Kernel Large-Margin Classifiers with Exact Cross-Validation Error Computation in PyTorch
- Developed TorchSVM, a PyTorch-based library that efficiently trains kernel SVMs and computes exact leave-one-out cross-validation (LOOCV) errors with GPU acceleration.
- Achieved scalable and fast computation, reducing the cost of LOOCV to that of training a single SVM, making large-scale kernel classification practical.
- Benchmarked superior performance against existing solvers (e.g., LibSVM, scikit-learn), with significant improvements in speed and scalability.
- **Repo**: [torchsvm](https://github.com/YikaiZhang95/torchsvm)
- **Docs**: [torchsvm](https://pypi.org/project/torchsvm/)

#### 2) Finite Smoothing Algorithm for High-Dimensional Support Vector Machines and Quantile Regression
- Introduced a finite smoothing algorithm (FSA), a novel approach to tackle computational challenges in applying support vector machines (SVM) and quantile regression to high-dimensional data.
- Implemented FSA using the coordinate descent method and demonstrated that FSA significantly outpaces its competitors in speed, often by orders of magnitude, while maintaining or improving precision.
- Developed twoopen-source R packages: hdsvm for high-dimensional SVM and hdqr for high-dimensional quantile regression.
- **Repo**: [FSA](https://github.com/YikaiZhang95/hdsvm)
- **Paper**: [FSA](https://openreview.net/pdf?id=RvwMTDYTOb)

> _More projects →_ [All repositories](https://github.com/YikaiZhang95?tab=repositories)


### 📄 Publications & Writing
- Tang, Q.∗, Zhang, Y.∗, and Wang, B. Finite Smoothing Algorithm for High-Dimensional Support Vector
 Machines and Quantile Regression. International Conference on Machine Learning (ICML), 2024.
-  Zhang,Y.,Jia, G., andWang, B.TorchKSVM:EfficientKernelLarge-MarginClassifierswithExactCross
Validation Error Computation in PyTorch. To be submitted.

### Softwares
#### TorchSVM
[![PyPI Version](https://img.shields.io/pypi/v/torchsvm)](https://pypi.org/project/torchksvm/)
[![Downloads](https://pepy.tech/badge/torchsvm)](https://pepy.tech/project/torchsvm)

GPU-accelerated kernel SVM with exact LOOCV and scalable model selection.
```python
pip install torchsvm
```

#### hdsvm
![CRAN Downloads](https://cranlogs.r-pkg.org/badges/grand-total/hdsvm)

- Implements an efficient algorithm for fitting the entire regularization path of support vector machine models with elastic-net penalties using a generalized coordinate descent scheme. The framework also supports SCAD and MCP penalties. It is designed for high-dimensional datasets and emphasizes numerical accuracy and computational efficiency.
- **Docs**: [hdsvm](https://cran.r-project.org/web/packages/hdsvm/index.html)
  
```r
install.packages("hdsvm")
```


### 🎙️ Talks
- Prospectus: On Advanced and Modern Computational Frameworks for Support Vector Machines. University of Iowa.



### 🤝 Collaboration
I’m open to research collabs, industry partnerships (ML/Stats/Insurance).
**Email**: yikai-zhang@uiowa.edu

