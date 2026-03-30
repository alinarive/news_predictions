# news_predictions
Заявка на участие в конкурсе «HSE Centaur Cap/Гонка кентавров ВШЭ»

# 📰 News Headline Predictor for April 2, 2026

## 🎯 Описание программы

Программа предсказывает **заголовки и первые абзацы** новостных статей, которые выйдут **2 апреля 2026 года** в различных странах мира.

Прогнозы генерируются на основе **реальных данных**:
- **Реальные исторические статьи** из новостных API (GNews API)
- **Национальные и международные праздники** (Calendarific API)
- **Прогноз погоды** (OpenWeatherMap API)
- **Анализ стиля и тональности** конкретных изданий

Для каждой из 5 стран программа анализирует до 8 изданий и генерирует предсказания с оценкой точности.

---

## 🌍 Поддерживаемые страны и события

| Страна | Событие | Поисковые запросы |
|--------|---------|-------------------|
| 🇬🇧 **Великобритания** | World Autism Awareness Day | `autism UK`, `autism awareness UK` |
| 🇺🇸 **США** | International Children's Book Day | `children's books USA`, `literacy programs USA` |
| 🇯🇵 **Япония** | New Fiscal Year + Cherry Blossom | `Japan economy`, `Japan business news` |
| 🇦🇷 **Аргентина** | Malvinas Veterans Day | `Malvinas Argentina`, `veterans Argentina` |
| 🇮🇷 **Иран** | Islamic Republic Day | `Iran Republic Day`, `Islamic Republic anniversary` |

---

## 📦 Требования

### Python 3.8+

Использовались Perplexity и Deepseek: первое для выбора стран, где есть крупные предсказуемые поводы для статей и сами поводы, второе - для генерации кода и отладки
