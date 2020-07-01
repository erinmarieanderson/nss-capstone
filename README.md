# A PROPOSAL TO UPDATE BOSTON MARATHON QUALIFYING TIMES USING AGE-GRADING

[Video presentation summarizing analysis](https://www.loom.com/share/fb89c095f0794deca4e2e06a0beac236)

[Nashville Software School, Data Analytics class website](https://nss-data-analytics-cohort-2.github.io/)

### About Me
- Graduate of Dartmouth College and Boston College Law School.
- Practiced law for six years representing whistleblowers alleging fraud against the government.
- Qualified for and was prepared to run the Boston Marathon 2020.
- June 2020 graduate of Data Analytics Bootcamp, Nashville Software School.

### Initial Goals
- Analyze 2020 proposed age grade standards for the marathon 
  * Intended on (and began) reverse-engineering 2015 standards using current single-age marathon records (arrs.run); ended up using Alan Jones' (@AlanLyttonJones) work after discovering his Age-Grade-Tables repository on Github on or about 6/9/20.
- Look at age standards in real world context (start with most recent Boston Marathon results (2019)) and go from there).
- Check validity of age-grading system for the marathon.

### Path I Took
- Kept an open mind and followed the data.  
- Ended up in place didn't expect to.

### Findings
- Age-grading standards appear sound as long as they are periodically updated with single-age records and outliers are considered and dealt with on a case-by-case basis. 
- However, curiousity piqued when saw **negative** correlation between age and age-graded times of female finishers at Boston 2019. 
- Same pattern **negative correlation** in age and age-graded times of female finishers at Boston 2010 - 2018.
- Discovered Boston Marathon qualifying times, when age-graded, are unequal between genders and across age-groups.
- In looking at finisher demographics, found that there are fewer finishers in gender/age groups that have the toughest age-graded qualifying times.

### Implications
- Boston Marathon qualifying times, when age-graded, are unequal between genders and across age-groups.
- Older women are held to the highest standard.
- Older women are also underrepresented in finish-number.

### Hypothesis
-Unequal standards ***cause*** disproporate participation.  
 * For example, older women are vastly underrepresented in number of finishers *because* they need to meet a tougher qualification time.  

### Recommendation
- Boston Marathon qualifying times should be updated using age-grading.
- For project, suggest (and run numbers for) 68% age-graded because
  * Minimally disruptive to current times and
  * Mant to make tougher because of problem that qualification no longer guarantees entry. 

### Data Sources
- Boston Athletic Association (BAA) (Boston Marathon race results 2010 - 2019, various charts and informaton re: history, qualification times, etc.)
- Association of Road Running Statisticians (ARRS)
- Alan L. Jones (@AlanLyttonJones) Age-Graded Tables (June 2020) and all his previous work (previously accessible at https://www.runscore.com/Alan/AgeGrade.html)

### Tools Used
- Python
 * Seaborn package for visualizations
- Excel
- Powerpoint

### Parameters
-Limited analysis to:
 * Marathon
 * Ages 18 - 84
