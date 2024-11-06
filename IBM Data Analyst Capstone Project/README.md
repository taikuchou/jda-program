# Building A Dashboard With IBM Cognos Analytics

## Introduction

In this assignment, you will create some visualizations and add them to dashboards.

## Dataset used in this assignment

The dataset you are going to use in this assignment comes from the following [source]: (https://stackoverflow.blog/2019/04/09/the-2019-stack-overflow-developer-survey-results-are-in/) under a ODbL: Open Database License.

## Download and upload data to Cognos Analytics

- [m5_survey_data_demographics.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_demographics.csv)
- [m5_survey_data_technologies_normalised.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_technologies_normalised.csv)

## Dashboard tabs

Create 3 dashboards (3 separate tabs under a single dashboard) as follows:

- First dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Current Technology Usage.

- Second dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Future Technology Trend.

- Third dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Demographics.

## Visualizations Details

### Current Technology Usage Tab

#### Panel 1: Top 10 Languages Worked With

- **Visualization**: Bar Chart
- **Data Field**: `LanguageWorkedWith`
- **Settings**:
  - Use **Bars, Length, and Color** fields.
  - Enable **Show value labels**.
  - Title: _Top 10 Languages Used in Current Technology_.

#### Panel 2: Top 10 Databases Worked With

- **Visualization**: Column Chart
- **Data Field**: `DatabaseWorkedWith`
- **Settings**:
  - Use **Bars, Length, and Color** fields.
  - Enable **Show value labels**.
  - Title: _Top 10 Databases Used in Current Technology_.

#### Panel 3: Platforms Worked With

- **Visualization**: Word Cloud Chart
- **Data Field**: `PlatformWorkedWith`
- **Settings**:
  - Use **Words, Size, and Color** fields.
  - Title: _Platforms Used in Current Technology_.

#### Panel 4: Top 10 Web Frameworks Worked With

- **Visualization**: Hierarchy Bubble Chart
- **Data Field**: `WebFrameWorkedWith`
- **Settings**:
  - Use **Bubbles, Size, and Color** fields.
  - Title: _Top 10 Web Frameworks Used in Current Technology_.

---

### Future Technology Trend Tab

#### Panel 1: Top 10 Languages Desired for Next Year

- **Visualization**: Bar Chart
- **Data Field**: `LanguageDesireNextYear`
- **Settings**:
  - Use **Bars, Length, and Color** fields.
  - Enable **Show value labels**.
  - Title: _Top 10 Languages Desired for Next Year_.

#### Panel 2: Top 10 Databases Desired for Next Year

- **Visualization**: Column Chart
- **Data Field**: `DatabaseDesireNextYear`
- **Settings**:
  - Use **Bars, Length, and Color** fields.
  - Enable **Show value labels**.
  - Title: _Top 10 Databases Desired for Next Year_.

#### Panel 3: Platforms Desired for Next Year

- **Visualization**: Tree Map Chart
- **Data Field**: `PlatformDesireNextYear`
- **Settings**:
  - Use **Area hierarchy, Size, and Heat** fields.
  - Enable **Contrast label color**.
  - Title: _Platform Desire for Next Year_.

#### Panel 4: Top 10 Web Frameworks Desired for Next Year

- **Visualization**: Hierarchy Bubble Chart
- **Data Field**: `WebFrameDesireNextYear`
- **Settings**:
  - Use **Bubbles, Size, and Color** fields.
  - Title: _Top 10 Web Frameworks Desired for Next Year_.

---

### Demographics Tab

#### Filters

- Apply filters to exclude entries except for _Man_ and _Woman_ in the `Gender` data point.

#### Panel 1: Respondent Gender Distribution

- **Visualization**: Pie Chart
- **Data Field**: `Gender`
- **Settings**:
  - Use **Segments and Size** fields.
  - Enable **Display %**.
  - Title: _Gender Distribution of Respondents_.

#### Panel 2: Respondent Count by Country

- **Visualization**: Map Chart
- **Data Field**: `Country`
- **Settings**:
  - Use **Regions-Locations and Regions-Location color** fields.
  - Title: _Respondent Count by Country_.

#### Panel 3: Respondent Count by Age

- **Visualization**: Line Chart
- **Data Field**: `Age`
- **Settings**:
  - Use **x-axis and y-axis** fields.
  - Enable **Show value labels** and **Show markers**.
  - Title: _Respondent Count by Age_.

#### Panel 4: Respondent Count by Gender and Formal Education Level

- **Visualization**: Stacked Bar Chart
- **Data Field**: `Gender`, classified by `FormalEducation`
- **Settings**:
  - Use **Bars, Length, and Color** fields.
  - Enable **Show value labels**.
  - Title: _Respondent Count by Gender and Education Level_.
