# HMC Auditory Radar FPV Framework

**Гармонійна модуляція як «слуховий радар»: 5D-модель тренування розпізнавання FPV-дронів за звуком**

Автор: **Олександр Лозовий**  
Статус: Conceptual Framework / Technical Report  
DOI: [10.5281/zenodo.17774342](https://doi.org/10.5281/zenodo.17774342)

---

## 🔍 Опис (UA)

Цей репозиторій містить концептуальну модель дешевого тренажера для навчання військових
розпізнаванню та локалізації FPV-дронів за звуком.

Фреймворк базується на:

- **5D-когнітивній рамці** (Час, Енергія, Структура, Режим, Спостерігач)
- **HMC (Harmonic Modulation Control)** – гармонійна модуляція як «слуховий радар»

Ключова ідея – подати звук FPV не як хаотичний шум, а як **структурований, гармонійно
модульований сигнал**, який мозок бійця може легко виділяти на фоні шуму бою.

У репозиторії:

- LaTeX-версія наукової статті (`docs/HMC_Auditory_Radar_FPV_Framework.tex`)
- Структура для подальшого додавання:
  - аудіо-сценаріїв (`data/`)
  - генераторів звуку / тренажера (`src/`)

---

## 🔎 Description (EN)

This repository contains a **conceptual and technical framework** for a low-cost training
system aimed at teaching soldiers to **detect and localize FPV drones by sound**.

The approach combines:

- a **5-dimensional cognitive model** (Time, Energy, Structure, Mode, Observer),
- **HMC (Harmonic Modulation Control)** – harmonic modulation as an *“auditory radar”*.

The core idea is to represent FPV sound not as random noise, but as a **structured,
harmonically modulated signal** that the human brain can reliably lock onto within
battlefield noise.

Contents:

- LaTeX source of the paper (`docs/HMC_Auditory_Radar_FPV_Framework.tex`)
- Skeleton for:
  - audio scenarios (`data/`)
  - future code for generators/trainers (`src/`)

---

## 📄 Наукова стаття / Paper

Файл статті (LaTeX):

- `docs/HMC_Auditory_Radar_FPV_Framework.tex`

Рекомендована назва PDF:

- `HMC_Auditory_Radar_FPV_Framework.pdf`

Офіційний DOI публікації:

```text
DOI: 10.5281/zenodo.17774342
```

---

## ⚙️ Компіляція LaTeX

```bash
cd docs
pdflatex HMC_Auditory_Radar_FPV_Framework.tex
pdflatex HMC_Auditory_Radar_FPV_Framework.tex
```

(подвійний прогін для оновлення змісту, нумерації тощо)

---

## 🧩 Структура тренажера (high-level)

- **Hardware**: ноутбук + 4 дешеві активні колонки (квадрат навколо слухача)
- **Core idea**:
  - FPV-моделі як сума шуму + гармоніки (оберти пропелерів)
  - низькочастотна гармонійна модуляція (HMC) як когнітивний «якір»
- **Scenarios** (під майбутній код у `src/`):
  - калібрування (один дрон, тиша)
  - дрон + шум бою
  - множинні FPV (розвідка vs ударний), пріоритизація загроз

---

## 📚 Цитування / Citation

Якщо ви використовуєте цей фреймворк або ідеї з нього:

```bibtex
@techreport{Lozovyi_HMC_Auditory_Radar_FPV_2025,
  author      = {Oleksandr Lozovyi},
  title       = {Harmonic Modulation as an Auditory Radar: A 5D Training Model for Acoustic FPV Drone Detection},
  institution = {Independent Research},
  year        = {2025},
  doi         = {10.5281/zenodo.17774342}
}
```

---

## 📬 Контакт

Автор: **Олександр Лозовий**  
Тема: FPV, психоакустика, HMC, 5D-когнітивні моделі.
