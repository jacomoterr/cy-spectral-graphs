# cy-spectral-graphs
Spectral analysis of graphs on Calabi–Yau manifolds
Exploring convergence of discrete Laplacians to Laplace–Beltrami spectra and their relation to Hodge numbers and computational models (CYbits)

DOI: https://doi.org/10.5281/zenodo.17050352
License: CC BY 4.0 (text), MIT (code)
Author: Evgeny Monakhov (ORCID: https://orcid.org/0009-0003-1773-5476)
GitHub: https://github.com/jacomoterr
Affiliation: VOSCOM Research Initiative (LLC "VOSCOM ONLINE")

-------------------------------------------------------------------------------

## 📖 Description (EN)

This project investigates the spectral properties of graphs discretized on Calabi–Yau (CY) manifolds, aiming to bridge differential geometry, spectral graph theory, and quantum computation.

### Central Hypothesis
As the number of discretization points N → ∞, the spectrum of the discrete graph Laplacian converges to the spectrum of the Laplace–Beltrami operator on the CY manifold M. Furthermore, spectral features — such as degeneracies and gaps — encode topological invariants like Hodge numbers (h¹¹, h²¹) and the Euler characteristic.

This forms the foundation for CYbits — a proposed unit of meta-quantum information derived from geometric spectra.

### Research Goals
- Validate spectral convergence numerically on simple CY spaces (T², T³, K3, quintic)
- Extract topological data from eigenvalue statistics
- Develop a framework for geometric quantum computation models

Part of the VOSCOM Research Initiative — advancing theoretical foundations for next-generation computing.

-------------------------------------------------------------------------------

## 🗂️ Repository Structure

paper/      - Preprints (LaTeX & PDF)
code/       - Numerical experiments (Python, C++)
data/       - Input/output datasets (spectra, graphs)
figures/    - Plots and illustrations
requirements.txt
LICENSE
README.txt  - This file

-------------------------------------------------------------------------------

## 🚀 Getting Started

Prerequisites:
- Python 3.8+
- NumPy, Matplotlib, SciPy

Install dependencies:
pip install -r requirements.txt

Run examples:
python code/spectral_circle.py
python code/spectral_torus.py

> More complex models (K3, quintic) will be added in future releases.

-------------------------------------------------------------------------------

## 📄 Citation (BibTeX - EN)

@misc{cy_spectral_graphs_2025,
  author       = {Evgeny Monakhov and VOSCOM Research Initiative},
  title        = {Spectral Graphs on Calabi--Yau Manifolds},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17050352},
  url          = {https://doi.org/10.5281/zenodo.17050352}
}

-------------------------------------------------------------------------------

## 🌐 License

- Papers & Text: Creative Commons Attribution 4.0 (CC-BY 4.0)
  https://creativecommons.org/licenses/by/4.0/

- Code: MIT License (see LICENSE file)

You are free to share and adapt — just give appropriate credit.

-------------------------------------------------------------------------------

## 🇷🇺 Описание (RU)

Этот проект посвящён исследованию спектральных свойств графов на многообразиях Калаби–Яу (CY). Основная гипотеза: при увеличении числа точек дискретизации N спектр дискретного лапласиана сходится к спектру оператора Лапласа–Бельтрами на M. Особенности спектра (вырождения, разрывы) кодируют топологическую информацию — например, числа Ходжа.

Проект направлен на построение концепции CY-битов — гипотетической единицы мета-квантовой информации, основанной на геометрических спектрах.

Часть инициативы ООО "ВОСКОМ-ОНЛАЙН".

-------------------------------------------------------------------------------

## 🛠 Структура репозитория

paper/      - Препринты (LaTeX и PDF)
code/       - Численные эксперименты (Python, C++)
data/       - Данные (спектры, графы)
figures/    - Графики и иллюстрации
requirements.txt
LICENSE
README.txt  - Этот файл

-------------------------------------------------------------------------------

## 🚀 Запуск экспериментов

Установка зависимостей:
pip install -r requirements.txt

Примеры:
python code/spectral_circle.py
python code/spectral_torus.py

> Модели K3 и квартики будут добавлены позже.

-------------------------------------------------------------------------------

## 📄 Цитирование (BibTeX - RU)

@misc{cy_spectral_graphs_2025_ru,
  author       = {Монахов Евгений Анатольевич, ООО "ВОСКОМ-ОНЛАЙН"},
  title        = {Спектральные графы на многообразиях Калаби-Яу},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17050352},
  url          = {https://doi.org/10.5281/zenodo.17050352}
}

-------------------------------------------------------------------------------

## 🛡️ Лицензия

- Тексты: CC BY 4.0
  https://creativecommons.org/licenses/by/4.0/

- Код: MIT License (см. файл LICENSE)

Разрешается свободное использование при указании авторства.

-------------------------------------------------------------------------------

© 2025 VOSCOM Research Initiative. All rights reserved.
