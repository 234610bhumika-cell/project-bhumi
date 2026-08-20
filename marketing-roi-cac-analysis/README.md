
# Marketing Campaign ROI & Customer Acquisition Cost (CAC) Analysis

**Tools:** Power BI, DAX, Excel/Google Sheets
**Context:** Independent portfolio project — Business Analyst track
**Result:** 📈 Identified a budget reallocation projected to generate ~₹2.7L in net revenue gain

## 🔗 Problem

Marketing spend across 8 channels (Email, Referral, Search, Social, Content, Direct Mail, TV/Radio, Affiliate) wasn't being evaluated consistently — it wasn't clear which channels were actually profitable versus which ones were just consuming budget on reach or brand visibility.

## 💡 Approach

- Built a Power BI dashboard calculating CAC, ROI, conversion rate, and CLV:CAC ratio by channel
- Diagnosed and fixed a data modeling issue (a many-to-many relationship) that was flattening the CLV:CAC metric to the same value across every channel
- Built a budget reallocation model testing the revenue impact of shifting spend from the weakest channel to the strongest, with sensitivity analysis across three shift levels
- Wrote a recommendation memo translating the analysis into a concrete, numbers-backed business decision

## 📊 Key Findings

- **Email Marketing** and **Referral Program** are the strongest channels — 620.8% and 427.0% ROI, with the lowest CAC and highest CLV:CAC ratios (17.7x and 16.1x)
- **TV/Radio** is the weakest performer across every metric — ROI of -57.6%, the highest CAC (₹196), and a CLV:CAC ratio of just 0.6x
- **Facebook/Instagram Ads** has the best conversion rate (24.5%) but almost no profitable return (1.0% ROI) — pointing to a funnel/offer issue rather than a targeting one
- TV/Radio receives the largest share of total spend despite being the worst performer, while Email Marketing — the best performer — gets one of the smallest budgets

## ✅ Recommendation

Shift 20% of TV/Radio's budget (~₹39,900) into Email Marketing. Projected net revenue gain: **~₹2,70,660**, without increasing total marketing spend.

## 📁 Files

- `Marketing_ROI_CAC_Dashboard.pdf` — Power BI dashboard (ROI%, CAC, Conversion Rate, CLV:CAC by channel)
- `Marketing_ROI_Reallocation_Model.xlsx` — Data model + budget reallocation scenario with sensitivity testing
- `Marketing_ROI_Recommendation_Memo.docx` — Full recommendation memo with findings, caveats, and next steps
