# Yachting Pages SEO Keyword Analysis

Comprehensive SEO analysis of the Yachting Pages keyword portfolio compared to 4 major competitors. This project analyzes 7,884 keywords across 5 domains to identify ranking opportunities, competitive gaps, and revenue optimization strategies.

## 📊 Project Overview

This analysis covers:
- **Total Keywords Analyzed**: 7,884 keywords
- **Analysis Period**: Q3 2025 (June - September)
- **Competing Domains**: 5 major competitors in the yachting/superyacht industry
- **Current Market Position**: #1 with 47.2% Share of Voice (SoV)

## 🎯 Key Findings

### Market Position
- **Yachting Pages**: 47.2% SoV (#1 Market Leader)
- **Boat International**: 25.1% SoV (#2 Challenger)
- **Superyacht Times**: 14.8% SoV (#3 Growing)
- **Service Guide**: 8.3% SoV (#4 Declining)
- **Superyacht Content**: 4.6% SoV (#5 Declining)

### High-Value Opportunities
- **Money Keywords (Top 10)**: 162 keywords generating core revenue
- **On-the-Cusp Keywords (Rank 11-20)**: 208 keywords | +$159/month potential
- **Quick Win Keywords**: 1,191 keywords with high volume/low difficulty
- **Gap Keywords**: 180 competitive gaps | +$50/month potential

### 90-Day Revenue Opportunity
- **Total Potential**: +$329/month (+76.5% improvement in top 10 rankings)
- **On-the-Cusp Optimization**: +124 keywords to top 10 = **+$159/month**
- **Gap Closure**: +73 easy gap keywords = **+$50/month**
- **Content Decay Fix**: Prevent -$120/month loss

### Critical Alert
⚠️ **Content Decay Crisis**: 34,442 net positions lost in 90 days
- Top decaying page: /articles/ (down 81 positions)
- Estimated impact: -$120-180/month
- **Action Required**: Week 1 emergency content refresh

## 📁 Project Structure

```
keyword_analysis/
├── Keyword_Analysis.ipynb          # Main analysis notebook
├── Correlation_Analysis.ipynb       # Correlation analysis (KD vs Rank, Vol vs CPC)
├── Gap_Analysis.ipynb              # Competitive gap identification
├── Quadrant_Analysis.ipynb         # Opportunity quadrant classification
├── Pivot_Analysis.ipynb            # Intent & geographic segmentation
├── Volatility_Analysis.ipynb       # SERP volatility & net growth
├── TImeSeries_Analysis.ipynb       # Ranking trends & content decay
├── keywords_data.csv               # Raw keyword dataset (7,884 keywords)
├── .gitignore                      # Git ignore rules
└── README.md                       # This file
```

## 📊 Analysis Sections

### 1. Correlation Analysis
- Spearman correlation of Keyword Difficulty vs. Ranking Position
- Yachting Pages shows strongest correlation (r=0.285) = superior SEO methodology
- Search Volume vs. CPC correlation (r=0.402) = moderate relationship
- Competitor ranking methodology analysis

### 2. Quadrant Analysis
- Classification by Search Volume × Keyword Difficulty
- **Quick Win**: 1,191 keywords (15.1%) - Urgent priority
- **Strategic**: 1,693 keywords (21.5%) - Medium priority
- **Long-tail**: 2,690 keywords (34.1%) - Low priority
- **Low Priority**: 2,310 keywords (29.3%) - Skip

### 3. Gap Analysis
- Identifies 180 competitive gap keywords
- Validated by competitor rankings
- **Easy gaps**: 105 keywords (KD < 30) | 70% success rate
- **Medium gaps**: 75 keywords (KD 30-60) | 40% success rate
- Top gap: 'yacht tender' (480 searches/mo, $1.47 CPC, KD=18)

### 4. Market Share of Voice (SoV)
- Domain-level visibility distribution
- 43.2% keyword overlap with Boat International
- 42.6% keyword overlap with Superyacht Times
- Interpretation: Shared market demand, superior rankings

### 5. Intent & Geographic Segmentation
- **Intent Distribution**: 81.3% informational, 14.9% commercial, 3.0% navigational, 0.4% transactional
- **Geographic Focus**: USA is 5x more valuable than any other market ($1.15 CPC)
- **Rebalancing Opportunity**: Increase commercial keywords from 15% to 30%

### 6. Volatility Analysis
- Net rank movement by domain
- SERP stability by keyword intent
- **Navigational keywords** most volatile (SD: 21.24)
- All intent types trending negative = ranking decay detected

### 7. Timeseries Analysis
- Domain-wide ranking trends (June-Sept 2025)
- Top 5 decaying landing pages with decay trajectory
- /articles/ section losing 165 positions (primary issue)

## 🚀 Recommendations (Priority Order)

### Phase 1: Emergency (Week 1)
**Fix Content Decay Crisis**
- Diagnose root cause of 34,442 position loss
- Emergency content refresh on /articles/ section
- Technical SEO audit for penalties/issues
- Expected recovery: +$120/month

### Phase 2: Short-term (Weeks 2-4)
**Optimize On-the-Cusp Keywords**
- Move 124 keywords from ranks 11-20 to top 10
- On-page optimization + fresh content
- Backlink acquisition (5-10 per keyword)
- Revenue impact: +$159/month

### Phase 3: Medium-term (Weeks 4-8)
**Close Competitive Gaps**
- Target 105 easy gap keywords (KD < 30)
- Expected captures: 73 keywords (70% success)
- Revenue impact: +$50/month

### Phase 4: Strategic (Ongoing)
**Expand Commercial Keyword Portfolio**
- Current: 1,178 commercial keywords (14.9%)
- Target: 2,400+ commercial keywords (30%)
- Long-term revenue growth: +$200-300/month

## 📈 Expected 90-Day Outcomes

| Metric | Current | Projected | Change |
|--------|---------|-----------|--------|
| Top 10 Keywords | 162 | 286 | +124 (+76.5%) |
| Top 20 Keywords | 370 | 443 | +73 (+19.7%) |
| Share of Voice | 47.2% | 49.7% | +2.5% |
| Monthly Revenue | $X | $X+$329 | +$329 (+YY%) |
| Market Position | #1 at Risk | #1 Stabilized | Maintained |
| Content Health | ⚠️ Critical | ✅ Stable | Improved |

**Annual Revenue Impact**: +$3,948 from priority actions alone

## 🛠️ Tools & Technologies

- **Python 3.11**
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **SciPy**: Statistical analysis (Spearman correlation)
- **Jupyter Notebooks**: Interactive analysis & reporting

## 📖 How to Use

1. **Install dependencies**:
   ```bash
   pip install pandas matplotlib seaborn scipy jupyter
   ```

2. **Open notebooks**:
   ```bash
   jupyter notebook
   ```

3. **Load data**:
   - All notebooks automatically load `keywords_data.csv`
   - 7,884 keywords with rankings, CPC, difficulty, volume data

4. **Run analysis**:
   - Execute cells sequentially to generate visualizations
   - Modify thresholds as needed for your analysis

## 📊 Key Visualizations Included

- ✅ Correlation heatmaps (KD vs Rank, Vol vs CPC)
- ✅ SEO Opportunity Matrix (4-quadrant scatter)
- ✅ Value Matrix (CPC vs Rank by domain)
- ✅ Market Share of Voice (SoV %)
- ✅ Keyword Overlap Heatmap (5x5 domain matrix)
- ✅ Volatility Scatter Plot (Chaos vs Growth)
- ✅ Ranking Tier Distribution (Bar chart)
- ✅ Top 10 Gap Keywords (Horizontal bar chart)
- ✅ Content Decay Timeseries (5-page trend lines)
- ✅ Current vs Projected Comparison (Outcome table)

## 💡 Strategic Insights

### Strengths ✅
- Market leader position with 47.2% SoV
- Superior KD-rank correlation (0.285) = stronger SEO foundation
- 1,191 Quick Win keywords available
- 180 proven gap keywords with competitor validation

### Weaknesses ⚠️
- Critical content decay: 34,442 positions lost
- Revenue concentrated in 21% of keywords
- Weak commercial intent coverage (14.9%)
- Navigational keywords highly volatile

### Opportunities 🎯
- +73 easy gap captures within 8 weeks
- +124 On-the-Cusp keywords to top 10
- USA market 5x more valuable - expand focus
- Rebalance toward commercial keywords (target 30%)

### Threats 🚨
- Boat International aggressive growth
- Algorithm changes affecting all intents
- Content decay if not addressed immediately
- Market consolidation risk (M&A)

## 📝 Data Dictionary

### Key Metrics
- **Keyword Difficulty (KD)**: 0-100 scale, higher = harder to rank
- **Search Volume**: Monthly searches (global)
- **CPC**: Cost-Per-Click in USD (advertising value)
- **Rank**: Current ranking position (1-100+, >100 = unranked)
- **Visibility**: Estimated visibility score from search ranking
- **Intent**: Keyword intent (i=informational, c=commercial, n=navigational, t=transactional)

### Data Fields
- `Keyword`: Target keyword phrase
- `Search Volume`: Monthly search volume
- `Keyword Difficulty`: KD 0-100
- `CPC`: Cost per click (USD)
- `Primary Intent`: i/c/n/t classification
- `Country`: Geographic market
- `yatchingpages.com_cleaned_rank`: Your rank
- `boatinternation.com_cleaned_rank`: Competitor 1 rank
- `superyachttimes.com_rank_cleaned`: Competitor 2 rank
- (Additional competitor ranks...)

## 🧹 Data Cleaning & Preparation

To ensure statistical accuracy and resolve formatting inconsistencies in the raw dataset, the following steps were taken:

### Rank Normalization (The "Unranked" Penalty)
- Keywords where a domain did not appear in the Top 100 were originally marked with symbols (e.g., `-`, `c`, `x`)
- These were converted to a numerical value of **150**
- **Purpose**: Allows for mathematical comparison (Spearman Correlation) and ensures unranked keywords are correctly penalized in "Average Rank" calculations

### String-to-Numeric Conversion
- Several columns (specifically Ranking and Rank Difference) contained hidden characters like single quotes (e.g., `'-5`)
- **Action**: All metric columns were forcibly cast to numeric formats using `pd.to_numeric` with error-coercion to prevent calculation failures

### Imputation of Missing Values
- **Keyword Difficulty (KD)**: Missing values filled with the **Median KD** of the dataset to prevent skewing the "Opportunity Matrix"
- **CPC & Search Volume**: Missing values treated as **0**, assuming negligible commercial value/volume if data provider lacks a record

### Intent Mapping
- Raw shorthand codes (`i`, `c`, `t`, `n`) mapped to descriptive labels:
  - `i` = Informational
  - `c` = Commercial
  - `t` = Transactional
  - `n` = Navigational
- **Purpose**: Clearer stakeholder reporting and intent-based segmentation analysis

## 📋 Strategic Assumptions

The following core assumptions underpin all analysis conclusions:

### Primary Subject Designation
- **Yachting Pages** (yachtingpages.com) is designated as the primary subject domain
- All performance metrics, including the "Value Matrix" and "Content Decay Analysis," are centered on this domain
- Provides actionable internal insights for strategic planning

### Representative Competitor Set
- Four additional domains selected represent the primary "Share of Voice" benchmarks for the superyacht industry:
  - Boat International
  - Superyacht Times
  - Superyacht Content
  - Superyacht Service Guide
- Competitive gaps identified based on **collective performance** of this group
- Assumption: These competitors represent the true competitive landscape for the target keyword portfolio

### Ordinality of Rankings
- Ranking data is **non-linear**; visibility and traffic value varies exponentially
- Moving from **Rank 2 → Rank 1** generates significantly higher traffic lift than **Rank 20 → Rank 19**
- Implications: Small improvements at top positions have outsized ROI vs. mid-tier optimizations

### Visibility Weighting
- "Visibility Score" in dataset accurately weights the value of ranking positions
- Weighting based on click-through rate (CTR) expectations
- Used for revenue projections and opportunity prioritization

### Penalty Value Impact (Unranked = 150)
- Any keyword outside Top 100 provides **zero organic traffic**
- Represents **total content deficiency** for the subject domain
- Justifies aggressive gap-closure strategy for "unranked but rankable" terms

## 🔄 Update Schedule

Recommended quarterly updates (every 3 months):
1. Re-run gap analysis to identify new opportunities
2. Track On-the-Cusp progress (should be moving to top 10)
3. Monitor competitor moves (especially Boat International)
4. Assess commercial keyword expansion progress
5. Identify new content decay signals

## 📞 Questions & Support

For questions about:
- **Analysis methodology**: See individual notebooks for detailed comments
- **Recommendations**: Review "Strategic Recommendations" section of Keyword_Analysis.ipynb
- **Data**: Check keywords_data.csv for raw keyword dataset

## 📄 License

This analysis is proprietary to Yachting Pages. Unauthorized use or distribution is prohibited.

---

**Last Updated**: February 1, 2026  
**Analysis Period**: June - September 2025  
**Next Review**: May 1, 2026

