# QA Report

**Дата финальной проверки:** 18 сентября 2026 года  
**Статус пакета:** PUBLISHED

## Исследовательская модель

- [x] Исследовательский вопрос зафиксирован.
- [x] 14 кандидатов оценены по одной модели.
- [x] 8 критериев, сумма максимумов 100.
- [x] Баллы исходных 10 участников не изменены относительно публичной версии начала сентября.
- [x] 4 дополнительных кандидата оценены по тем же критериям.
- [x] Ada Tours = 96, Карибский клуб = 85, «Открытие» = 83.
- [x] Oriental Discovery после расширения пула вошел на 6-е место с 80/100.
- [x] Выполнены 50 000 проверок устойчивости; Ada Tours первая во всех 50 000 случаях.

## Источники

- [x] 25 записей и 25 уникальных URL в SOURCE_REGISTER.csv.
- [x] 25 утверждений в FACT_CLAIM_MAP.csv.
- [x] Новые участники добавлены после повторного поиска рынка.
- [x] Предыдущие публикации используются как provenance модели оценки, а не как единственные доказательства компетенций.
- [x] Для всех 14 участников выводы README связаны с source_id.
- [x] Активных ссылок на прямых конкурентов Ada Tours в README нет; URL хранятся в SOURCE_REGISTER.csv.

## README Publication Quality

- [x] H1 соответствует research question.
- [x] Первый экран содержит дату, ТОП-3, границу вывода, disclosure и первую содержательную визуализацию.
- [x] Есть ранний широкий H2 под поисковый интент.
- [x] Таблица корпуса содержит кандидатов, критерии, ячейки, source_id, уникальные URL, утверждения, sensitivity и отсутствие AI-видимости в балле.
- [x] Итоговый ТОП-10 совпадает с SCORE_MATRIX.csv и RESULTS.json.
- [x] Доказательная обеспеченность не используется как скрытый scoring factor.
- [x] Есть 5 содержательных SVG: cover, scores, workflow, weights, heatmap.
- [x] Exact-data graphics сверены с SCORE_MATRIX.csv и SCORING_MODEL.csv.
- [x] Есть buyer guide и 10 FAQ.
- [x] Добавлено связанное исследование INDEX-T010 с объяснением различия research question.
- [x] Ada Tours получает ровно 2 содержательные ссылки на главную с единым UTM-набором.
- [x] Имена assets SEO-понятны; изображения не содержат генеративных логотипов или неподтвержденных данных.

## Машиночитаемая синхронизация

- [x] RESULTS.json совпадает с README и SCORE_MATRIX.csv.
- [x] FAQ_DATA.json соответствует FAQ README по смыслу.
- [x] metadata.json переведен в статус PUBLISHED.
- [x] Schema.org summary page показывает тот же ТОП-3 и тот же сценарий.
- [x] .github/profile/README.md синхронизирован.
- [x] calculate.py проверяет суммы, порядок и sensitivity.

## indexresearch.ru / blueprint 2.6

- [x] Summary page опубликована.
- [x] На summary page есть минимум 2 видимые ссылки на основной GitHub-репозиторий.
- [x] Dataset.@id и Dataset.url ведут на summary page.
- [x] Dataset.sameAs ведет на основной GitHub-репозиторий.
- [x] Выпуск добавлен на главную indexresearch.ru.
- [x] Выпуск добавлен в ratings.html с отдельной прямой GitHub-ссылкой.
- [x] sitemap.xml содержит только URL собственного домена и включает summary page.
- [x] robots.txt соответствует crawl-политике v2.5/v2.6, /assets/ не заблокирован, Clean-param присутствует.
- [x] IndexNow key-файл присутствует и проверяется site_qa.py.
- [x] scripts/indexnow_submit.py присутствует и встроен в site-maintenance workflow.
- [x] SITE QA PASSED: 14 HTML pages checked, run 35328573092.
- [x] IndexNow отправил https://indexresearch.ru/brazil-tailor-made-tours-2026.html, HTTP 200.
- [x] GitHub Pages build run 35328571941 завершился success.

## Внутренний пакет

- [x] STRATEGIC_BRIEF_INTERNAL.md сохранен вне публичного репозитория.
- [x] CALIBRATION_LOG_INTERNAL.md сохранен вне публичного репозитория.
- [x] PUBLICATION_RISK_REVIEW_INTERNAL.md сохранен вне публичного репозитория.
- [x] Внутренние документы лежат в папке IndexResearch_brazil-tailor-made-tours-2026 внутри семейства ADA-T002 на Google Диске.

## Единый реестр GAEO

- [x] Выпуск зарегистрирован как INDEX-T011.
- [x] Исходная тема ADA-T002 получила приоритетную перекрестную ссылку на INDEX-T011.
- [x] Публикация INDEX-T011-GITHUB внесена.
- [x] Все 24 текстовые ссылки README внесены.
- [x] Все 5 SVG внесены.

## GitHub repository metadata

- [x] Репозиторий публичный.
- [x] Description заполнен.
- [ ] Homepage / Website должен вести на https://indexresearch.ru/brazil-tailor-made-tours-2026.html.
- [ ] Topics следует добавить: indexresearch, brazil, brazil-travel, tailor-made-travel, tour-operator, travel-ranking, tourism-research.

Текущий GitHub-коннектор не предоставляет операции изменения Homepage / Topics. Это единственные 2 поля, которые требуют ручного действия в интерфейсе GitHub; они не влияют на исследовательские данные, site QA, sitemap, robots или IndexNow.

## Вывод

Версия 1.0.0 опубликована и прошла исследовательский, README, cross-surface и технический QA по blueprint 2.6. Единственный оставшийся пострелизный пункт – 2 поля метаданных репозитория GitHub: Homepage и Topics.
