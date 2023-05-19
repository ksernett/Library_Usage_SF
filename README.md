# San Francisco Public Library Usage

### Overview
The purpose of this project was to analyze given library patron data to determine trends in library usage as it relates to patrons of different age groups. 

### Process
- Extract the data
    - Load the CSV into a jupyter notebook
    - Examine the data for unneeded columns, null values, and data types
- Review/clean the data
    - Determine reason for discrepancies in data value counts (Home Library Code/Home Library Definition)
- Visualize the data
    - Creation of visualizations using matplotlib and seaborn

### Conculsions
- The largest number of patrons is in the 25 to 24 age range
    - This group has the lowest average number of checkouts
    - They also have the highest percentage of patrons that provided an email address
- In contrast, the lowest number of patrons is in the 75 years and over age range
    - This group has the highest average number of checkouts - which may be due to being long-term patrons of the library
    - They also have the lowest percentage of patrons that provided an email address
    - <img width="1188" alt="Screenshot 2023-05-19 at 3 38 33 PM" src="https://github.com/ksernett/Library_Usage_SF/assets/116037188/352a8e2b-4fc2-45b2-8433-82337ab93088">
    - <img width="1173" alt="Screenshot 2023-05-19 at 3 39 03 PM" src="https://github.com/ksernett/Library_Usage_SF/assets/116037188/46f7eed9-53bd-4c84-b40b-05d200b6c6f0">
    - <img width="1167" alt="Screenshot 2023-05-19 at 3 39 26 PM" src="https://github.com/ksernett/Library_Usage_SF/assets/116037188/f7d8da3a-0d2c-4478-8649-d4f3cb0609cb">
- A majority of the patrons across all age ranges have been active within the last 5 years of data
    - The highest numbers are in the most recent year
    - <img width="1244" alt="Screenshot 2023-05-19 at 3 38 00 PM" src="https://github.com/ksernett/Library_Usage_SF/assets/116037188/116063dd-1355-4386-a924-1222bb1d19fb">

### Next Steps
Improvements or next steps in this project may include:
- Using machine learning to predict type of patron
- Update visualizations to be more interactive using hvplot
- Create additional analysis and visualizations of the given dataset

#### Resources
- Data set was originally found on Kaggle: https://www.kaggle.com/datasets/datasf/sf-library-usage-data

