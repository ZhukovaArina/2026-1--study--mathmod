# Individual presentation
# Теорема о прогнозе разнообразия

Доклад по дисциплине «Математическое моделирование»

## 📋 Описание

В работе исследуется теорема о прогнозе разнообразия (Diversity Prediction Theorem), которая математически объясняет, почему коллективные решения часто оказываются точнее индивидуальных. Рассматривается история вопроса (от эксперимента Гальтона 1906 года до работ Пейджа 2007 года), математическая формулировка теоремы и её практические следствия.

## 📂 Структура проекта

```
presentation/
├── README.md ← вы здесь
├── README.ru.md ← краткая версия на русском
├── presentation/ ← ПРЕЗЕНТАЦИЯ (beamer/pdf)
│ ├── mathmod-presentation-presentation.qmd ← исходник презентации (Quarto)
│ ├── _quarto.yml ← конфигурация Quarto для презентации
│ ├── Makefile ← сборка презентации
│ ├── image/ ← иллюстрации для презентации
│ │ ├── diversity.png ← компенсация ошибок
│ │ ├── diversity_scheme.png ← сравнение групп
│ │ └── student.jpg ← фото докладчика
│ ├── _resources/ ← ресурсы (шрифты, тема beamer)
│ │ └── tex/
│ │ └── beamer.tex ← настройка шрифтов и темы
│ └── _output/ ← результат сборки
│ └── mathmod-presentation-presentation.pdf
│
└── report/ ← РЕФЕРАТ (pdf)
├── mathmod-presentation-report.qmd ← исходник реферата (Quarto)
├── _quarto.yml ← конфигурация Quarto для реферата
├── Makefile ← сборка реферата
├── refs.bib ← библиография (BibTeX)
├── bib/
│ └── cite.bib ← дополнительная библиография
├── image/ ← иллюстрации для реферата
├── _resources/ ← ресурсы
└── _output/ ← результат сборки
└── mathmod-presentation-report.pdf
```

## 🛠 Сборка

Для сборки используется Quarto + LaTeX (LuaLaTeX):

```bash
# Клонировать репозиторий
git clone <url-репозитория>
cd presentation/

# Установить зависимости (для Ubuntu/Debian)
sudo apt install texlive-full pandoc quarto

# Собрать проект
make
```

Результаты сборки появятся в папке `_output/`.

## Литература

1. **Galton F.** Vox Populi // Nature. — 1907. — Vol. 75, No. 1949. — P. 450–451.
2. **Surowiecki J.** The Wisdom of Crowds. — New York: Anchor Books, 2005.
3. **Page S.E.** The Difference: How the Power of Diversity Creates Better Groups, Firms, Schools, and Societies. — Princeton: Princeton University Press, 2007.

## Автор

**Жукова Арина Александровна**  
Студентка 3-го курса, направление «Прикладная информатика»  
Российский университет дружбы народов им. П. Лумумбы  
1132239120@rudn.ru

## Лицензия

CC BY 4.0
