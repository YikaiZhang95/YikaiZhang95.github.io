<h1 align="center">Hi, I'm Yikai Zhang👋</h1>
<p align="center">
<a href="https://scholar.google.com/YOUR_LINK_HERE"><img alt="Google Scholar" src="https://img.shields.io/badge/Scholar-4285F4?logo=google-scholar&logoColor=white"></a>
<a href="https://www.linkedin.com/in/yikai-zhang-66a01b160"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
<a href="https://pypi.org/user/yikaizhang/"><img alt="PyPI" src="https://img.shields.io/badge/PyPI-3775A9?logo=pypi&logoColor=white"></a>
<a href="mailto:yikai.zhang@uiowa.edu"><img alt="Email" src="https://img.shields.io/badge/Email-181717?logo=gmail&logoColor=white"></a>
<img alt="Visitors" src="https://komarev.com/ghpvc/?username=YikaiZhang95&style=flat">
</p>


### 🧑‍🔬 About
I'm a statistical Ph.D. candidate with 10+ years of experience in statistics and machine learning:
- Developed innovative algorithms, including the Finite Smoothing Algorithm and Generalized Takeuchi’s Information Criteria, transforming SVM and large-margin classifiers.
- Proficient in Python, R, SQL, and Fortran, delivering high-performance tools and **open-source packages**; integrate **Fortran/CUDA** kernels.
- Published author with research showcased at **ICML**.
- Successfully collaborated across diverse industries, including insurance and chemical manufacturing, to deliver impactful tools.


### 🛠️ Tech Stack
- **Languages**: Python, R, CUDA C/C++, Fortran, SQL
- **ML**: PyTorch, scikit‑learn, XGBoost
- **Systems**: HPC, GitHub Actions, packaging (PyPI/R‑pkg)

### 💼 Work Experience

**Data Science Intern** — UFG Insurance _(Summer 2024)_  
- Refitted a bodily injury cost model with XGBoost and LLMs, improving prediction accuracy by about **10%** over the prior model。  
- Built a Python Shiny tool integrating SQL and LLMs to estimate insurable replacement value.
- Automated fraud detection from police reports with an LLM-based backend which significantly boosts claim flagging efficiency.  

**Data Science Intern** — Dow Inc. _(Summer 2023)_  
- Conducted applied machine learning and statistical analysis projects.  
- Collaborated across functional teams to deliver insights from large datasets.  

**Graduate Researcher** — University of Iowa _(2019–Present)_  
- Research on **large-scale kernel SVMs**, GPU acceleration, and insurance risk modeling.  
- Built open-source packages (**TorchKSVM, cvksvm, SAFE, DROS**) in PyTorch and R.  
- Integrated Fortran/CUDA kernels for high-performance computing.  


### ⭐ Featured Projects


#### 1) TorchSVM (PyTorch, GPU‑accelerated Kernel SVM)
- Exact LOOCV/spectral tricks; scalable training & model selection on large kernels.
- GPU memory tuning (e.g., `PYTORCH_CUDA_ALLOC_CONF=expandable_segments:True`).
- **Repo**: https://github.com/YOUR_LINK_HERE • **Paper/Preprint**: YOUR_LINK_HERE • **Docs**: YOUR_LINK_HERE


#### 2) MagicSVM / TorchSVM
- Clean APIs for margin‑based classifiers; CPU/GPU backends; benchmarks vs mainstream solvers.
- **Repo**: https://github.com/YOUR_LINK_HERE


#### 3) cvksvm (R)
- Cross‑validated kernel SVM with efficient paths; interfaces to Fortran routines.
- **Repo**: https://github.com/YOUR_LINK_HERE • **Pkgdown**: YOUR_LINK_HERE


#### 4) SAFE: Sign‑Aligned Frequency–Severity for Climate Losses
- Frequency/severity components with sign‑aligned regularization; meteorological features (GridMET).
- **Repo**: https://github.com/YOUR_LINK_HERE • **Slides**: YOUR_LINK_HERE • **Data Notes**: YOUR_LINK_HERE



> _More projects →_ [All repositories](https://github.com/YikaiZhang95?tab=repositories)


### 📄 Publications & Writing
- ICML‑adjacent work on kernel SVMs and scalable CV; open‑source software papers (JMLR‑style).
- See **Google Scholar** and preprints: YOUR_LINK_HERE.

### Softwares
#### TorchSVM
[![PyPI Version](https://img.shields.io/pypi/v/torchsvm)](https://pypi.org/project/torchksvm/)
[![Downloads](https://pepy.tech/badge/torchsvm)](https://pepy.tech/project/torchsvm)

GPU-accelerated kernel SVM with exact LOOCV and scalable model selection.

#### hdsvm
![CRAN Downloads](https://cranlogs.r-pkg.org/badges/grand-total/hdsvm)
### 🎙️ Talks
- Prospectus: “Computational Advancements for SVM” — GPU architecture, LOOCV, large‑scale kernels.
- Invited/internal talks on SAFE (insurance analytics) and PyTorch/Fortran/CUDA integration.


### 🤝 Collaboration
I’m open to research collabs, industry partnerships (ML/Stats/Insurance), and OSS contributions.
**Email**: yikai.zhang@YOUR_EMAIL_DOMAIN
**Calendly**: YOUR_LINK_HERE


---


### 📦 Install (examples)
```bash
# Python (TorchKSVM)
pip install torchksvm # if published


# R (cvksvm)
# install.packages("devtools")
devtools::install_github("YikaiZhang95/cvksvm")
