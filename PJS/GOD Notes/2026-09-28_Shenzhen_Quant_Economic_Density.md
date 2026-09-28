# Shenzhen Quant Firm Revenue-per-Head Benchmark V0.2

**Timestamp:** 2026-09-28

## Core metric

```text
Normalized Revenue / Head
= AUM × 2% normalized monetization rate ÷ headcount
```

This is a standardized benchmark, not reported accounting revenue.

| Rank | Firm | AUM | Headcount | AUM / Head | 2% Normalized Revenue / Head |
|---:|---|---:|---:|---:|---:|
| 1 | JHL / 进化论 | 400–500亿 | 37 | 10.8–13.5亿 | 2160–2700万 |
| 2 | 知行通达 | 200亿+ | 35 | 5.71亿+ | 1140万+ |
| 3 | 世纪前沿 | 600亿+ | 100+ | ~6亿级 | ~1200万级 |
| 4 | 九坤 Ubiquant | 800亿 | 178 | ~4.49亿 | ~899万 |
| 5 | HopeSeek / 宏锡* | 100–150亿 | ~25 | 4–6亿 | 800–1200万 |
| 6 | 千惠 | 100–150亿 | ~47 | 2.13–3.19亿 | 426–638万 |
| 7 | 茂源 | 400–500亿 | ~160 | 2.50–3.13亿 | 500–625万 |
| 8 | 大道 | 100亿+ | ~45 | 2.22亿+ | 444万+ |
| 9 | 大岩 | 100亿+ | 40+ | ~2.5亿+ | ~500万+ |
| 10 | 衍盛 | 50–100亿 | ~32 | 1.56–3.13亿 | 313–625万 |
| 11 | 久期量和 | 20–50亿 | ~35 | 0.57–1.43亿 | 114–286万 |

*HopeSeek is Zhongshan-headquartered and retained as GBA benchmark.

## GOD Notes

### Economic Density

```text
Economic Density
= Monetizable Capital / Organizational Complexity
```

AUM alone is not enough. A better organizational benchmark is how much monetizable capital a firm can support per employee while preserving research, engineering, trading and risk quality.

### Two institution archetypes

```text
Heavy Platform
= 茂源 / 九坤 / 世纪前沿
= larger team
+ infra
+ engineering
+ specialization
+ institutional scale
```

```text
Compact Research Institution
= 进化论 / 知行通达
= smaller team
+ high AUM/head
+ high research density
+ high decision density
```

### Do not confuse revenue/head with salary/head

```text
Revenue / Head
→ Fixed Compensation
→ Compute / Data / Execution
→ Operating Cost
→ Bonus Pool
→ Retained Profit
```

## Next DD queue

1. 诚奇 — exact headcount
2. 超量子 — exact headcount
3. 博普 — AUM + headcount
4. 安子 — AUM + headcount
5. 国恩 — AUM + headcount
6. 和美 — AUM + headcount
7. 康曼德 — AUM + headcount
8. 泰润海吉 — AUM + headcount

## Reusable schema

```text
firm
snapshot_date
AUM_low
AUM_high
headcount
AUM_per_head
normalized_rate
normalized_revenue_per_head
firm_specific_revenue_low
firm_specific_revenue_high
source_confidence
notes
```
