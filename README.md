# JOB-POST-ANALYSIS
The objective of this project is to employ data analysis methodologies utilizing Python programming language.

# KEY OBJECTIVES:
- Utilize Python libraries and tools to perform exploratory data analysis (EDA) on the collected job data.
- Identify trends, patterns, and insights related to the different technology jobs.
- Visualize the analysis results using appropriate charts, graphs, and visual representations.

# DATASET CLEANING

- Employer_company_type exhibits the highest proportion of missing values, amounting to 54.22%.
- Importantly, given the nature of our analytical objectives for this dataset,
- It is pertinent to note that these missing values have no discernible impact on the insights derived from our analysis.
- The decision was made to exclude the job_id column from the analysis, as its inclusion was deemed irrelevant to the analytical objectives at hand.
- This column, typically serving as a unique identifier, does not contribute pertinent information or insights to the analysis of job postings.


# EXPLORATORY DATA ANALYSIS/ 
# UNIVARIATE ANALYSIS

# Count of Job Country categories:
US	73
GB	60	
CA	33
The United States (US) stands out with the highest count of job postings, totaling 73. 
While the US leads in job postings, Great Britain (GB) and Canada (CA) also exhibit notable numbers of job opportunities,
with 60 and 33 postings, respectively.


The majority of job postings originate from the finance and consulting industries, with each sector accounting for 18 postings.

# Count of Job Employment categories:
Fulltime		153
Contractor		10
Intern		2
Parttime		1

The majority of job postings, with a count of 153, are for full-time positions. 
This indicates a strong demand for candidates who are available for permanent employment and are willing to commit to full-time roles.

41.57% of job postings are originating from linkedin.com.	

# Count of Job by City.

London and Toronto emerge as prominent job hubs, with 29 and 11 job postings, respectively.
This indicates a robust employment market in these metropolitan areas, offering diverse opportunities across various industries.

While London and Toronto lead in job openings, cities like Montreal, Boston, New York, and Ogden also offer employment opportunities, albeit to a lesser extent


# Count of job_posted_at_timestamp Categories:

The timestamp category "2023-12-20 00:00:00" stands out with 7 job postings, indicating a peak in job postings on this dat

There is  consistency in posting frequency across multiple dates and times. 

# Top Employers

# Count of employer_website:
http://www.bdo.com               14
http://www.agoda.com              4
http://www.rbc.com                3
http://www.tesla.com              3
http://www.geturgently.com        2


# Top 20 terms found within job descriptions.

The term "data" emerges as the most frequently utilized keyword in job descriptions, closely followed by "experience" and "work". 
These keywords are commonly encountered in various job postings, underscoring their significance in articulating job requirements and qualifications within the employment landscape.


# EXPLORATORY DATA ANALYSIS
# Bivariate Analysis

# Employment type Distribution by job title:

Data Engineer is the most common job title on the list, with over 28 job postings for full time and 3 for part time.
There is a mix of entry-level and senior-level positions on the list, suggesting that there are opportunities for people with all levels of experience.


# Employment type distribution by Job Country:
Full-time positions dominate all three countries, comprising the majority of job postings. 
This suggests a preference for stable, long-term employment arrangements in these regions.


London emerges at the top, boasting the highest concentration of opportunities among the ten leading cities.
Toronto follows closely behind, showcasing its strength as another significant hub for full-time employment.


# METHODOLOGY

# Data Collection and Preparation:
Gather datasets scraped by Data Engineering Interns, ensuring they're in a structured format.
Perform data cleaning and preprocessing to handle missing values, duplicates, and inconsistencies.

# Descriptive Statistics and Data Understanding:

Compute descriptive statistics to understand the basic characteristics of the dataset. Gain insights into the data's structure, distribution, and variability.

# Exploratory Data Analysis (EDA):

Utilize EDA techniques to visually explore the dataset, including bar charts.

- Identify patterns, trends, and relationships between variables.

- Conduct categorical analysis to examine the distribution of categorical variables like job titles and employment types.

# INSIGHTS

-  In contrast to Great Britain and Canada, the dataset suggests a higher volume of job openings in the United States.
-  A predominant portion, specifically 41.57%, of job postings originates from linkedin.com, with LinkedIn.com leading in the number of job postings, followed by uk.linkedin.com.
-  London and Toronto stand out as the cities boasting the highest number of job openings, indicating a robust employment market in these metropolitan centers.
-  The field of finance and consulting emerges as the sector with the most significant number of job openings tailored for technology experts.
-  This observation underscores the demand within these industries for skilled professionals adept in technology-related roles,
-  reflecting the ongoing convergence of technology and financial services as well as consulting practices.
-  Among the common terms found in job descriptions, 'data' emerges as the most frequently utilized, followed closely by 'experience' and 'work'.
-  These keywords are prevalent throughout various job postings, reflecting their significance in conveying job requirements and qualifications. 
-  The most common employment type for these job titles is full-time, with around 92% of job postings being for full-time positions.
-  Contractor roles are the second most common, at around 6%, followed by part-time roles at around 1%. Internship roles make up around 1% of the postings.
-  There is a high demand for data science and engineering skills, as many of the job titles on the list are related to these fields.

An examination of employer type distribution within job postings across the United States, Great Britain, and Canada reveals intriguing patterns:

- Full-time employment reigns supreme: Full-time positions dominate all three countries, comprising the majority of job postings.
  This suggests a preference for stable, long-term employment arrangements in these regions.
  
- Part-time prominence in Canada: Interestingly, Canada stands out with a higher prevalence of part-time job postings compared to the US and UK.
 This could be attributed to factors like a flexible work culture catering to student populations or a desire for work-life balance.

- Contract and internship discrepancies: A curious observation lies in the absence of contract and internship postings from Canada in the data.
  This warrants further investigation into potential reasons behind this discrepancy, such as differing data sources or specific job board limitations.
  
- Cultivating young talent: US and UK lead in internships: The US and UK exhibit a higher concentration of internship opportunities compared to Canada.
  This might indicate a stronger emphasis on nurturing young talent and providing early career exposure in these countries.

# Across the cities analyzed in this data set, a striking trend emerges:
 - Full-time job postings reign supreme. 
This observation suggests a strong overall preference for stable, long-term employment arrangements within the represented locations.
Notably, London takes the top spot, boasting the highest concentration of full-time job postings amongst the ten leading cities.
Following closely behind is Toronto, further solidifying the presence of full-time opportunities in this major metropolitan center.
Certain employer websites stand out with higher counts of job postings.
For example, "http://www.bdo.com" leads with 14 job postings, followed by "http://www.agoda.com" with 4 postings.
This indicates the presence of prominent employers actively recruiting through their websites.
The distribution of job postings across employer websites may reflect sector-specific trends.
For instance, websites like "http://www.bdo.com" and "http://www.rbc.com" are associated with financial and professional services,
while "http://www.tesla.com" represents the technology and automotive sector. This suggests sector-specific recruitment strategies employed by different employers.

# RECOMMENDATIONS

# For Job Seekers:

- Target the U.S. Job Market: Given the higher volume of job openings in the United States compared to Great Britain and Canada,
  consider exploring opportunities in the U.S. market. Leverage online job portals and professional networking platforms to identify relevant roles.
- Utilize LinkedIn Effectively: With LinkedIn.com being the primary source of job postings,
  ensure your LinkedIn profile is updated, optimized, and showcases your skills and experiences effectively.
- Actively engage with industry content, join relevant groups, and network with professionals to increase visibility and access opportunities.
- Explore specific locations: Consider London and Toronto for a wider range of full-time opportunities:
  London and Toronto emerge as cities with robust employment markets for tech professionals.
- Consider targeting job opportunities in these metropolitan centers, where demand for technology expertise is high.
- Explore Finance and Consulting Roles: The finance and consulting industries offer significant job openings tailored for technology experts.
- Upskill in relevant areas such as fintech and data analytics to capitalize on opportunities within these sectors.
- Target prominent employer websites: Research companies like BDO and Agoda that actively recruit through their websites.
- Highlight data skills: Emphasize your data literacy, analytical abilities, and relevant data tools experience in your resume and cover letter.
- Data is the most sought-after skill across various industries.
- Use relevant keywords: Include data-related keywords in job search.


# For Employers and Recruiters:

- Tap into the U.S. Talent Pool: With a higher volume of job openings in the United States, consider expanding recruitment efforts to tap into the diverse talent pool available in the U.S. market.
- Leverage LinkedIn for Recruitment: Given that a predominant portion of job postings originates from LinkedIn, utilize the platform effectively for recruitment purposes.
- Post job vacancies, engage with potential candidates, and leverage LinkedIn's advanced search features to identify suitable talent.
- Target London and Toronto for Talent Acquisition: London and Toronto stand out as cities with high job openings,
- indicating a robust talent pool in these metropolitan centers. Focus recruitment efforts in these regions to access skilled tech professionals.
- Explore Collaboration with Finance and Consulting Sectors: Given the demand for technology expertise in the finance and consulting industries,
- Consider collaborating with organizations in these sectors to identify talent and explore potential partnerships for talent development and recruitment initiatives.
- Emphasize data skills: Clearly outline data-related requirements and responsibilities in job descriptions to attract qualified candidates.
- Utilize employer websites: Leverage your website as a recruitment platform and maintain updated job postings.
- Offer diverse employment options: Consider offering part-time and contract roles alongside full-time positions to cater to different preferences.











