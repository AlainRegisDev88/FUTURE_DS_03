# Bank Marketing Campaign Funnel Analysis

## Project Overview

Analysis of a bank's marketing campaign to understand how customers move through the conversion funnel: Contact to Subscription. 
This analysis identifies key drivers of conversion and provides recommendations to improve the next campaign's performance.

Dataset: Bank Marketing Campaign (45,211 customer records)

Overall Conversion Rate: 11.7% (5,289 conversions)


## Key Findings

### 1. Age is the Strongest Predictor

Best Performers: Customers aged 66-80 (43.7%) and 81+ (46.0%) convert at nearly 4x the rate of younger customers
Worst Performers: Ages 31-45 (9.6%) and 46-65 (10.6%) convert at less than 10%
Hypothesis: Seniors have more stable finances, more available time, and are more receptive to banking products

### 2. Previous Contact History Creates Massive Lift

Previously Contacted: 23% conversion rate
First-Time Contact: 9% conversion rate
Impact: 2.5x improvement by re-engaging past leads
Hypothesis: Second contacts show genuine interest; those who listened once are warm leads


### 3. Call Duration Strongly Correlates with Conversion

Converted customers: Calls average 6+ minutes
Non-converted customers: Calls average <1 minute
Insight: Longer conversations = stronger engagement and understanding
Recommendation: Invest in quality conversations, not volume of calls


### 4. Tertiary Education Drives Conversion

Tertiary (University): 15.1% conversion
Secondary: 10.6% conversion
Primary: 8.8% conversion
Hypothesis: Higher education = higher financial literacy and purchasing power


### 5. Contact Method Matters

Cellular: 15% conversion (best)
Telephone: 13% conversion
Unknown: 4% conversion (worst)
Insight: Mobile-first approach works best; avoid vague contact channels


### 6. Previous Campaign Success is Gold

Previous Success: 64% conversion
Other/Unknown: 9-16% conversion
Failure: 12% conversion
Hypothesis: Customers who already bought are highly likely to buy again


## High-Risk Segments (Low Conversion)

### Young Professionals (Ages 31-45): ~10% conversion despite likely being economically active

Possible reason: Too busy, less financial pain point

### Blue-Collar Workers: ~8% conversion

Possible reason: Less disposable income, less financial sophistication

### Unknown Education Level: Only 13% (should be higher)

Possible reason: Can't segment effectively without this data



## Top-Performing Segment

Seniors (66+) with Tertiary Education + Previous Success

Conversion rate: 40-47%
Highly receptive, time-rich, financially secure



## Actionable Recommendations

### 1. Prioritize Seniors (Ages 66+)

Allocate 40% of campaign budget to customers 66+
Expected ROI increase: 3x
Create senior-friendly marketing materials (larger fonts, simpler language)

### 2. Re-engagement Strategy

Re-contact customers with previous campaign success at 2x normal frequency
Expected conversion lift: 2-3x
Estimated additional conversions: ~1,000+ customers


### 3. Extend Call Duration Target

Train agents to aim for 5+ minute calls (from average 2-3 minutes)
Quality over volume KPI
Expected improvement: +5% conversion rate


### 4. Optimize Contact Method

Prioritize cellular phone over telephone
Phase out "unknown" contact methods
Expected lift: +2% conversion rate


### 5. Segment by Education + Age

Tier 1 (Highest ROI): 66+ years, tertiary education, previous success → 40%+ conversion
Tier 2 (High ROI): 18-30 years, tertiary education, previous contact → 20% conversion
Tier 3 (Medium ROI): 31-65 years, secondary education → 10-14% conversion
Tier 4 (Low ROI): <45 years, primary education, no history → <10% conversion



## Estimated Business Impact


| Action Segment | Current Conv. | Expected Conv. | Additional Sales |
| :--- | :--- | :--- | :--- |
| **Re-engage previous success** | 1,200 customers | 64% | 70%+72 |
| **Target seniors 66+** | 8,000 contacts | 11.7% | 35%+1,856 |
| **Extend call length** | 25,000 contacts | 11.7% | 16.7%+1,250 |
| **Total Expected Lift** | | | **~3,178 new conversions** |

Annual Revenue Impact: If average customer value = $500, this represents $1.59M additional revenue from optimizing segment targeting alone.


Files in Repository

future-interns-task-3 folder
- task3_analysis.ipynb       
- README.md   

Data Folder
- bank-full.csv        

Results folder
- 01_funnel_overview.png
- 02_conversion_rate_by_age.png
- 03_conversion_rate_by_job.png
- 04_conversion_by_previous_contact.png
- 05_conversion_by_call_duration.png
- 06_conversion_by_education.png
- 07_conversion_rate_by_contact_method.png
- 08_previous_outcome_impact.png
- 09_conversion_heatmap_age_education.png
- conversion_metrics_summary.csv


Key Metrics Summary


| Metric | Value |
| :--- | :--- |
| **Total Contacts** | 45,211 |
| **Total Conversions** | 5,289 |
| **Overall Conversion Rate** | 11.7% |
| **Best Age Group** | 81+ (46.0%) |
| **Best Job** | Student (30.0%) |
| **Best Education** | Tertiary (15.1%) |
| **Best Contact Method** | Cellular (15.0%) |
| **Best Previous Outcome** | Success (64.0%) |
| **Previous Contact Lift** | 2.5x |



How to Use This Analysis


Immediate Actions: Re-contact customers with previous successful campaigns and prioritize the seniors
Campaign Design: Create age-specific messaging for 66+ demographic
Agent Training: Focus on call quality/duration (5+ min targets).
Budgeting: Shift budget allocation to high-performing segments



Author

**Regis Alain Udahemuka**

Ashesi University | Computer Science (BSc)

Future Interns Data Science & Analytics Internship

CIN: FIT/MAY26/DS18653