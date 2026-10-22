# Protomonster 1.300

22 October 2026. Character-set expansion and marker arrow redesign, incorporating the improved vertical metrics from local 1.205.

- 430 glyphs and 427 Unicode mappings: 169 new glyphs / 168 new encoded characters compared with 1.204.
- Extended European Latin: additional accented letters, Œœ, Ÿ, ẞ, Ðð, Þþ, Ĳĳ and others.
- Ukrainian and Belarusian letters Ґґ Єє Іі Її Ўў, plus modifier-letter apostrophe ʼ.
- Currency and punctuation: £ ¥ ¢ ¡ ¿ ‰ ‹ › ‚ ′ ″ ‑ ¶.
- Nine original marker-style arrows; ≠ ≤ ≥ ≈ ∞ √; nine fractions and fraction slash; superscript and subscript digits 0–9.
- Eight combining marks, mark positioning and contextual dotless į for decomposed accents.
- Vertical metrics align text more naturally in line boxes; outlines of pre-existing letters remain as in the accepted 1.204 drawing.

Variable 400–700, default Medium 500; static Regular 400 / Medium 500 / Bold 700. True lowercase, ordinary M/М and optional eyes through ss01 are retained.

Each new glyph received three independent agent reviews across five weights. The nine redrawn arrows received a separate three-reviewer pass. Release checks verify preservation of the accepted outlines and layout data, dense weight interpolation, normalization and reproducibility. These checks cover display use and the recorded proofs, not every possible language, word or application. Earlier releases remain available in Git history and GitHub Releases.

---

# Protomonster 1.204

Обновление от 21 октября 2026, включает локальные доработки 1.201–1.204.

- Д/д: цельное нижнее левое соединение без двойной ступеньки.
- O/О, Q/Ø и акцентированные O: увеличена высота, сохранена толщина крайних штрихов; согласованы акценты и 28 кернинговых пар.
- Доведены r, m, E/Е и родственные формы, просветы ф, стыки б и И/Й/и/й.
- Исправлены локальные зубцы и соединения в ряде прописных, u/y/у и их акцентированных вариантах; раскрыты тесные участки € и § в Bold.
- Уточнены 0/6/8/9, центр Ж/ж; строчная l получила отличимый выход и стала шире на 45 единиц на 1000 UPM.

Сохранены наклон, маркерные окончания, истинные строчные, default Medium 500, диапазон 400–700 и вариант M/М с глазами через ss01. Текущая y оставлена без дополнительного сглаживания хвоста.

Полный визуальный просмотр охватил 261 глиф × 3 начертания. После последнего прохода повторно просмотрены изменённые формы и слова в шести весах. Финальные проверки 1.204: 301 вес × 46 изменённых глифов, 144578 парных контекстов и 5040 контекстов с диакритикой без новых пересечений; 11/11 побайтово воспроизводимых экспортов.

Известное ограничение: острые внутренние V у № в Bold сохранены. Экспериментальное сглаживание не вошло в релиз из-за дефектов интерполяции. Проверки ориентированы на короткий display-текст от 32 px и не означают тестирование всех приложений или отсутствие всех унаследованных тесных пар.
