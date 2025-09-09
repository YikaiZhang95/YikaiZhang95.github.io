<h1 align="center">Hi, I'm Yikai 👋</h1>
<p align="center">
<a href="https://scholar.google.com/YOUR_LINK_HERE"><img alt="Google Scholar" src="https://img.shields.io/badge/Scholar-4285F4?logo=google-scholar&logoColor=white"></a>
<a href="https://www.linkedin.com/in/YOUR_LINK_HERE"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
<a href="https://pypi.org/user/YOUR_LINK_HERE/"><img alt="PyPI" src="https://img.shields.io/badge/PyPI-3775A9?logo=pypi&logoColor=white"></a>
<a href="mailto:yikai.zhang@YOUR_EMAIL_DOMAIN"><img alt="Email" src="https://img.shields.io/badge/Email-181717?logo=gmail&logoColor=white"></a>
<img alt="Visitors" src="https://komarev.com/ghpvc/?username=YikaiZhang95&style=flat">
</p>


---


### 🧑‍🔬 About
- Ph.D. candidate in Statistics (University of Iowa) focused on **modern large‑margin classifiers** and **GPU acceleration**.
- Build open‑source libraries in **PyTorch** and **R**; integrate **Fortran/CUDA** kernels.
- Domain apps: **insurance risk modeling** (frequency–severity/SAFE), climate extremes, and large‑scale classification.


### 🛠️ Tech Stack
**Languages**: Python, R, CUDA C/C++, Fortran, SQL
**ML**: PyTorch, Triton, cuBLAS/cuSOLVER, scikit‑learn, XGBoost
**Systems**: Linux, GitHub Actions, packaging (PyPI/R‑pkg), profiling & benchmarks


### ⭐ Featured Projects


#### 1) TorchKSVM (PyTorch, GPU‑accelerated Kernel SVM)
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
