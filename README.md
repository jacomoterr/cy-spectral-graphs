# cy-spectral-graphs
Spectral analysis of graphs on Calabi–Yau manifolds. Exploring the convergence of discrete Laplacians to Laplace–Beltrami spectra and their relation to Hodge numbers and computational models (CYbits).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxx)
EN:
## 📖 Description
This project is dedicated to the study of **spectral properties of graphs on Calabi–Yau (CY) manifolds**.  
The central hypothesis is that as the number of discretization points $N$ increases, the spectrum of the discrete Laplacian converges to the spectrum of the Laplace–Beltrami operator on $M$. Moreover, specific spectral features (degeneracies, gaps) encode information about the topology of CY spaces (e.g., Hodge numbers).  

The project is part of the **LLC "VOSCOM ONLINE" Research Initiative** and aims to develop the concept of **CY-bits** and their meta-extensions.

## 🛠 Repository Structure
- `paper/` — preprints (LaTeX and PDF)  
- `code/` — (Research) numerical experiments (Python, C++, etc.)  
- `data/` — (Research) example input and output datasets (spectra, discretizations)  
- `figures/` — (Research) plots and illustrations  
- `README.md` — project description  
- `LICENSE` — license (recommended CC-BY 4.0 for papers and MIT for code)

## 🚀 How to Run Experiments
```bash
# Install dependencies
pip install -r requirements.txt

# Run spectral analysis of the circle
python code/spectral_circle.py

# Run spectral analysis of the 2-torus
python code/spectral_torus.py
```


## 📄 Citation
If you use this project in your work, please cite it as:
  @misc{cy_spectral_graphs,
  author       = {Evgeny Monakhov, LLC "VOSCOM ONLINE"},
  title        = {Spectral Graphs on Calabi--Yau Manifolds},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.xxxxx}
}

----------------------------------------------------
RU:

## 📖 Описание
Этот проект посвящён исследованию **спектральных свойств графов на многообразиях Калаби–Яу (CY)**.  
Основная гипотеза: при увеличении числа точек дискретизации $N$ спектр дискретного лапласиана сходится к спектру лапласиана–Бельтрами на $M$, а особенности спектра (вырождения, разрывы) несут информацию о топологии CY (например, числа Ходжа).  

Проект является частью инициативы **ООО "ВОСКОМ-ОНЛАЙН" исследования** и направлен на построение концепции **CY-битов** и их мета-расширений.

## 🛠 Структура репозитория
- `paper/` — препринты (LaTeX и PDF)  
- `code/` — (в разработке) численные эксперименты (Python, C++ и др.)  
- `data/` — (в разработке) примеры входных и выходных данных (спектры, дискретизации)  
- `figures/` — (в разработке) графики и иллюстрации  
- `README.md` — описание проекта  
- `LICENSE` — лицензия (рекомендуется CC-BY 4.0 для текстов и MIT для кода)  

## 🚀 Как запустить эксперименты
```bash
# Установка зависимостей
pip install -r requirements.txt

# Запуск примера анализа спектра окружности
python code/spectral_circle.py

# Запуск анализа тора T^2
python code/spectral_torus.py
```

## 📄 Цитирование.
Если вы используете этот проект в своей работе, пожалуйста, цитируйте его так:
@misc{cy_spectral_graphs,
  author       = {Evgeny Monakhov LLC "VOSCOM ONLINE" },
  title        = {Spectral Graphs on Calabi--Yau Manifolds},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.xxxxx}
}
