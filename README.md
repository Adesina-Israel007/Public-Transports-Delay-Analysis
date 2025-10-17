# Public Transportation Delay Analysis Dataset

![Image](https://github.com/user-attachments/assets/2479fdc0-74a0-4f1a-b621-0757081d5af9)

## Overview
Public Transportation delay dataset with 2,000+ trips, weather data, event impacts, and operational metrics. Perfect for ML prediction models, route optimization, and public transit reliability analysis across multiple transport modes.
## Research Questions Analyzed

### 1. Transport Mode Performance
**"Which transport mode has the worst on-time performance, and how does delay duration vary between them?"**
- **Key Finding**: Buses show worst performance (25.09 min avg delay) vs Trams (10.94 min avg delay)
- **ANOVA Result**: No statistically significant difference between transport types (p=0.161)
- **Practical Insight**: Despite statistical similarity, buses require operational attention

### 2. Event Impact Analysis
**"Do large-scale events with high attendance cause significant network-wide delays?"**
- Correlates event types (Concerts, Sports, Festivals, Protests) with delay patterns
- Analyzes attendance size impact on network performance
- Identifies most disruptive event types

### 3. Seasonal Variations
**"Are delays more severe during specific seasons, and does this vary by transport types?"**
- **Key Finding**: Spring shows the highest delays (22.94 min) vs Winter (17.08 min)
- **ANOVA Result**: No statistically significant seasonal differences (p=0.754)
- **Transport-Season Interaction**: Two-Factor ANOVA shows no significant interaction effects

### 4. Station Pair Analysis
**"Are there specific origin-destination station pairs that are particularly prone to delays?"**
- Maps delay hotspots across station combinations
- Identifies critical corridors requiring intervention
- Analyzes spatial patterns in delay distribution

### 5. Route Reliability
**"Which specific routes are the most unreliable in terms of consistent scheduling?"**
- Calculates Unreliability Scores combining average delays and variability
- Ranks routes by consistency and predictability
- Highlights routes needing schedule optimization

### 6. System Performance Overview
**"What is the proportion of both delayed and not delayed trips?"**
- Provides baseline system reliability metrics
- Calculates overall delay rate and on-time performance
- Establishes performance benchmarks

## Statistical Analysis: Two-Factor ANOVA Results

### Transport Type Performance (Rows)
| Mode | Average Delay | Variance | Statistical Significance |
|------|---------------|----------|--------------------------|
| Bus | 25.09 min | 76.43 | p=0.161 (Not Significant) |
| Metro | 18.02 min | 12.84 | p=0.161 (Not Significant) |
| Train | 22.38 min | 57.90 | p=0.161 (Not Significant) |
| Tram | 10.94 min | 91.77 | p=0.161 (Not Significant) |

### Seasonal Performance (Columns)
| Season | Average Delay | Variance | Statistical Significance |
|--------|---------------|----------|--------------------------|
| Spring | 22.94 min | 86.27 | p=0.754 (Not Significant) |
| Summer | 18.84 min | 88.43 | p=0.754 (Not Significant) |
| Autumn | 17.56 min | 152.77 | p=0.754 (Not Significant) |
| Winter | 17.08 min | 35.73 | p=0.754 (Not Significant) |

### ANOVA Summary Table

**Interpretation**: Although practical differences exist (Bus vs. Tram: a 14+ minute gap), the ANOVA reveals no statistical significance, likely due to high variability and a small sample size (4 observations per group).

## Dataset Features

- **2,000+ trip records** with detailed timing data
- **Multiple transport modes**: Bus, Metro, Train, Tram
- **Weather conditions**: Storm, Rain, Snow, Fog, Clear, Cloudy
- **Event data**: Type, estimated attendance, timing
- **Station network**: 50+ stations with origin-destination pairs
- **Temporal factors**: Peak hours, holidays, seasons, weekdays

## Analysis Tools
All analyses were conducted using **Microsoft Excel** with:
- Pivot Tables and Charts
- Statistical functions (AVERAGE, STDEV, ANOVA)
- Conditional formatting and data visualization
- Calculated fields and measures

## Key Applications
- Transportation planning and optimization
- Delay prediction modeling
- Resource allocation and scheduling
- Performance benchmarking
- Infrastructure investment prioritization

## Files Included
- `transport_delay_data.csv` - Main dataset
- `analysis_dashboard.xlsx` - Excel analysis workbook
- `documentation.md` - Detailed data dictionary

---
*Ideal for urban planners, data analysts, and transportation researchers focusing on public transit reliability and performance optimization.*

I am open to collaborating on Data analysis, Statistical analysis, and visualization-related projects. You can reach me via my Email: [remcomfort007@gmail.com] 
