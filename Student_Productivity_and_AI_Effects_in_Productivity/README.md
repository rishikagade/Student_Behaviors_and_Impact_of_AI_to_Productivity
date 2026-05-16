# Virginia Tech Student Productivity Dashboard

## Project Overview

This project analyzes the daily habits, behavioral patterns, and technology usage choices that influence academic productivity among Virginia Tech students. The goal was to understand why students with similar academic workloads may experience different GPA outcomes, and to identify actionable habits that students, advisors, and faculty can use to improve academic performance.

The project was developed as part of **Business Visualization Analytics, Spring 2026** at the Pamplin College of Business.

## Disclaimer

This project is based on a survey sample of 151 Virginia Tech students. Since the sample size is limited and was collected through convenience-based outreach, the findings are **not intended to represent the entire Virginia Tech student population** or all college students.

Instead, this project should be interpreted as an exploratory data visualization and storytelling exercise designed to identify possible patterns, behavioral trends, and areas for further investigation. The insights are useful for generating discussion and guiding future research, but they should not be treated as statistically generalizable conclusions.

## Team Members

- Vignesh Anand
- Vishwaja Bute
- Rishika Gade
- Krish Maniar
- Krishna Sharma

## Problem Statement

College students manage academic, social, and personal responsibilities while facing increasing distractions from phones, social media, irregular sleep, and AI tools. Although many students put in similar study effort, their academic outcomes often differ.

This project explores the central question:

**Which daily habits, behavioral factors, and technology usage patterns most significantly influence academic productivity among Virginia Tech students?**

## Business / Analytical Motivation

The project was designed to help students and academic stakeholders better understand the behaviors associated with stronger academic outcomes. The main audiences for this analysis include:

- Virginia Tech students
- Academic advisors and counselors
- Faculty members and teaching assistants
- Student success and academic support services
- University administrators focused on student outcomes

The findings are intended to support data-backed conversations around study habits, sleep, distractions, AI use, and academic performance.

## Dataset

The data was collected through a student survey of **151 Virginia Tech students** during Spring 2026. Responses were gathered through online distribution channels including WhatsApp, BIT 5424 email, personal networks, and in-person outreach.

Because the dataset is based on a relatively small, convenience-based sample, it is not meant to represent the entire Virginia Tech student population. The purpose of the dataset is to explore student productivity patterns and identify trends that may be useful for discussion, advising, and future research.

The survey captured information on:

- GPA and academic background
- Credit hours and attendance
- Sleep duration
- Study habits and exam preparation
- Phone distraction
- Study location and social setting
- Music and caffeine use
- AI usage, dependency, and understanding
- Productivity barriers and promoters
- Work status and financial support

## Key Metrics

The sample included:

- **151 student responses**
- **Average GPA:** 3.47
- **Average credit hours:** 13.38
- **Average attendance rating:** 3.78 / 5
- **50.3%** of students sleeping fewer than 7 hours
- **45.7%** of students reporting high phone distraction
- **70.9%** agreeing that AI improves productivity
- **62.3%** reporting they would perform worse without AI

## Data Cleaning & Preparation

The dataset was cleaned in Microsoft Excel before being imported into Tableau. Key preparation steps included:

- Renaming survey question fields into shorter, cleaner column names
- Standardizing open-ended responses
- Grouping majors into broader college/program categories
- Binning GPA into four performance groups
- Bucketing sleep duration into five ranges
- Verifying Likert-scale responses for consistency
- Standardizing text-entry answers with similar meanings
- Separating multi-select work-status responses into binary fields
- Pivoting AI assignment and exam impact fields for better visualization

## Analysis Methods

The project used:

- Descriptive statistics
- Comparative analysis
- Correlation-based exploration
- GPA group segmentation
- Behavioral pattern comparison
- Dashboard-based storytelling in Tableau

The analysis focused on understanding how habits such as sleep, phone usage, study environment, AI reliance, attendance, and exam preparation relate to GPA outcomes.

## Dashboard Story Structure

The Tableau story was designed as an 8-part dashboard sequence:

1. **Story Context & Background**  
   Introduces the project, sample profile, and academic context.

2. **Behavioral Insights**  
   Provides an overview of major behaviors connected to productivity.

3. **Daily Habits**  
   Explores sleep, study time, attendance, and exam preparation.

4. **Distraction Insights**  
   Highlights phone use, study environment, and other focus barriers.

5. **AI Influence**  
   Examines AI usage, perceived benefits, dependency, and understanding.

6. **Productivity Barriers**  
   Identifies the most common factors that help or hurt productivity.

7. **GPA Group Behaviors**  
   Compares behavioral patterns across GPA performance bands.

8. **Key Takeaways**  
   Concludes with recommendations for students, advisors, and faculty.

## Key Findings

### 1. Sleep and phone distraction are major productivity risks

Roughly half of the surveyed students reported sleeping fewer than 7 hours, and nearly half reported high phone distraction during study sessions. These patterns suggest that productivity challenges are widespread rather than isolated.

### 2. Phone use appears strongly related to GPA

Students who reported always using their phone while studying had an average GPA of approximately **3.20**, compared to around **3.5+** for students with lower phone distraction.

### 3. AI is useful, but dependency is a concern

Most students believe AI improves productivity and academic performance. However, many also reported that they would perform worse without AI, suggesting that AI may be functioning as both a productivity tool and a dependency risk.

### 4. Higher-GPA students show stronger behavioral discipline

Students in higher GPA groups generally showed stronger habits, including lower phone distraction, better attendance, healthier sleep patterns, stronger preparation routines, and more independent use of AI.

### 5. Productivity is shaped by multiple behaviors, not one factor

The analysis suggests that academic performance is connected to a combination of habits rather than a single driver. Sleep, study setting, phone use, preparation, attendance, and AI behavior together form a broader productivity profile.

## Recommendations

### For Students

- Aim for at least 7 hours of sleep
- Reduce phone use during study sessions
- Choose structured, distraction-free study environments
- Use AI as a support tool, not a replacement for independent thinking
- Build consistent preparation habits before exams

### For Academic Advisors

- Ask students about sleep, phone use, study setting, and AI reliance during advising conversations
- Use behavioral patterns to identify students who may need support
- Focus especially on students in the 3.0–3.49 GPA range, where improvement potential may be high

### For Faculty and University Programs

- Provide structured milestones instead of relying only on high-stakes deadlines
- Promote responsible AI literacy
- Encourage healthier study environments
- Consider integrating productivity findings into orientation or student success programming

## Tools Used

- Tableau
- Microsoft Excel
- Survey-based data collection
- Data cleaning and transformation
- Descriptive and comparative analysis
- Dashboard storytelling

## Repository Contents

```text
├── Team_14_Data_Collection.pdf                  # Data collection plan and survey measurement framework
├── Team_14_Project_planning_worksheet.pdf       # Project planning, analysis goals, and methodology
├── Team_14_Story_Telling_worksheet.docx         # Tableau story outline and dashboard narrative
├── README.md                                    # Project documentation