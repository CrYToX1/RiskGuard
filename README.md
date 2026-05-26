# RiskGuard

**AI systém pro detekci rizikových křižovatek a prevenci nehod**

## Popis projektu
RiskGuard je AI řešení vyvinuté pro Středočeský kraj v rámci České AI Olympiády 2026.  
Cílem je včasně detekovat nebezpečné situace na křižovatkách (rizikové manévry, chodci a cyklisté v konfliktu) a pomoci dopravní správě předcházet nehodám.

## Použité technologie
- **Image klasifikace** — Teachable Machine (TensorFlow.js)
- **Prediktivní model** — Simple ML for Sheets
- **Webová aplikace** — HTML + TensorFlow.js (běží přímo v prohlížeči)

## Jak funguje
1. Uživatel nahraje snímek z dopravní kamery
2. Model okamžitě klasifikuje situaci
3. Při detekci vysokého rizika (`rizikova_situace` nebo `chodci_cykliste`) systém vydá varování + doporučení prevence

## Demo
[Otevřít RiskGuard →](https://tvojejmeno.github.io/riskguard)

## Součásti řešení
- `index.html` — hlavní webová aplikace
- `model/` — natrénovaný model z Teachable Machine

## Budoucí rozvoj
- Integrace s živými kamerami ŘSD
- Propojení s prediktivním modelem v reálném čase
- Mobilní notifikace pro dispečery

---

**Vyvinuto pro:** Středočeský kraj & IDSK  
**Téma:** Chytrá mobilita – Bezpečnost a prevence nehod