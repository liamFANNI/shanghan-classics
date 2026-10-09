# shanghan-classics

Agent skill generated from **《伤寒论》(Shang Han Lun / Treatise on Cold Damage)** by **张仲景 (Zhang Zhongjing)**, with [book-to-skill](https://github.com/virgiliojr94/book-to-skill).

A reusable knowledge base for the classical Chinese medical text 《伤寒论》: the **六经辨证** (six-channel pattern differentiation) system, **经方** (classical formulas — 桂枝汤, 麻黄汤, 小柴胡汤, 白虎汤, 承气汤, 四逆汤, 乌梅丸, etc.), **方证对应** (formula-pattern correspondence), and **表里先后** (exterior/interior treatment order). Covers all 398 clauses (条文) across 10 chapters (篇).

## Install

```bash
npx skills add https://github.com/liamFANNI/shanghan-classics --skill shanghan-classics
```

## File inventory

- `SKILL.md` — core frameworks (六经辨证, 方证对应) + chapter/topic index
- `chapters/` — 10 chapter files (太阳上/中/下, 阳明, 少阳, 太阴, 少阴, 厥阴, 霍乱, 阴阳易差后劳复)
- `glossary.md` — key terms (六经, 方剂, 病机)
- `patterns.md` — formula-pattern and treatment-method patterns
- `cheatsheet.md` — decision-reference tables (六经定位, 选方, 鉴别)

## Usage

- Load `shanghan-classics` → core frameworks
- Ask about a topic (`太阳病`, `桂枝汤`, `结胸`, `发黄`) → the agent reads the relevant chapter
- Ask for a chapter (`ch04`) → the agent loads that chapter

## Note

The content is **synthesized summaries and structured extraction**, not the original book text. 《伤寒论》 is a public-domain classical text (Eastern Han dynasty, ~25–220 CE). This skill is a study aid, not medical advice — always apply clinical knowledge with appropriate professional judgment.
