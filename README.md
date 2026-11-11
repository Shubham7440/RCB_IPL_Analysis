# IPL Data Analytics: RCB Squad Selection \& Auction Strategy

###### 

## About the Project

#### In this project, I performed an end-to-end data analysis on multi-season IPL datasets (spanning 4+ seasons) to solve key operational and strategic questions for team management. Using MySQL, I analyzed ball-by-ball records, match results, and individual player performance logs to evaluate bowling efficacy, venue dynamics, and player impact.

##### 

#### The primary objective was to move beyond basic statistics and build an actionable, data-backed auction and squad-selection strategy tailored specifically for Royal Challengers Bengaluru (RCB).

###### 

## Key Insights \& Strategy Recommendations

* #### Identified Dominant Bowling Types: Analyzing wicket distribution across bowling styles revealed that right-arm medium pacers were the most effective wicket-takers (\*\*232 wickets\*\*), significantly outperforming right-arm fast-medium bowlers (\*\*145 wickets\*\*). This directly informed my target profiles for bowling recruitment.
* #### Evaluated Venue Dynamics: Calculated venue-wise win/loss records and pitch behaviors across grounds to understand how specific bowling variations and batting approaches perform under varying match conditions.
* #### Built a Data-Driven "Dream XI": Developed a custom composite scoring system combining batting averages, strike rates, bowling economy, and all-rounder impact to select an optimized playing XI.
* #### Designed an Auction Strategy: Synthesized player performance metrics into a strategic bidding framework for RCB, helping prioritize high-value targets while optimizing remaining purse limits.
* #### Executive Presentation: Summarized all technical query results and strategic takeaways into an RCB-branded PowerPoint deck with clear data visuals for non-technical stakeholders.

###### 

## Technical Execution \& SQL Workflows

#### I answered 10+ complex objective and subjective business queries by leveraging advanced MySQL features:

* #### Advanced Joins \& Aggregations: Combined ball-by-ball and match metadata tables to calculate granular player and team metrics.
* #### Common Table Expressions (CTEs): Structured complex multi-stage calculations for multi-column player rankings and window comparisons.
* #### Window Functions: Applied `DENSE\_RANK()`, `ROW\_NUMBER()`, and moving averages to rank players within specific roles and track season-over-season performance consistency.

