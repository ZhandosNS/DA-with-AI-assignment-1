# DA-with-AI-assignment-1
# World Values Survey Wave 7 Dataset (2017-2022)

## 1. Dataset Overview
The World Values Survey (WVS) is a worldwide network of social scientists studying changing values and their impact on social and political life. Conducted once every five years, the WVS surveys representative samples from nearly 100 countries across all inhabited continents, making it a premier dataset for cross-cultural research and comparative studies on global values.

## Key Features
- **Survey Period**: 2017 to 2022
- **Countries Covered**: Over 100 countries across global regions
- **Total Observations**: Data from approximately 90,000-100,000 respondents globally
- **Total Variables**: Over 300 variables, capturing a wide range of responses related to personal values, civic engagement, cultural practices, and societal norms.
- **Survey Methodology**: Employs a mix of Computer-Assisted Personal Interviewing (CAPI), Paper-and-Pencil Interviewing (PAPI), Computer-Assisted Web Interviewing (CAWI), and other region-specific methods.

## Core Topics Covered
- **Social Values and Norms**: Includes questions on societal norms, values, and beliefs about family, work, and religion.
- **Happiness and Wellbeing**: Assesses respondents' subjective wellbeing and happiness levels.
- **Social Capital, Trust, and Organizational Membership**: Explores trust in different societal institutions and participation in various organizations.
- **Economic Values**: Respondents' perspectives on their personal and national economic situations.
- **Perceptions of Corruption**: Gauges public opinions on the extent of corruption in government and business.
- **Perceptions of Migration**: Views on immigration, integration, and cultural diversity.
- **Political Interest and Participation**: Measures engagement in national and local political processes, including voting and activism.
- **Religious Values**: Examines the role and impact of religious beliefs on personal and societal levels.
- **Demographic and Socioeconomic Information**: Detailed demographic information such as age, gender, education, and income.

## 2. File Paths

### WVS Data File:
`C:\Users\mrrai\OneDrive\Рабочий стол\CEU\DAwAI\WVS_subset.xlsx`

### WVS Codebook:
`C:\Users\mrrai\OneDrive\Рабочий стол\CEU\DAwAI\WVS_codebook.pdf`

## Research Question
**How do perceptions of corruption influence political participation across different countries and cultural contexts within the World Values Survey Wave 7 data?**

This study aims to explore the relationship between individuals' perceptions of corruption in their respective countries and their levels of political engagement. By analyzing responses from the World Values Survey (Wave 7: 2017-2022), we can assess whether corruption perception discourages or motivates political participation.

## 3. Key Variables

Each variable in the dataset follows a specific measurement scale, such as categorical, ordinal, or numerical.

1. **Q112 - Perceived Corruption in Government**  
   - **Type:** Ordinal  
   - **Scale:** Respondents rate government corruption on a scale (e.g., "Very corrupt" to "Not corrupt").  
   - **Example Values:**
     - 1 = Very corrupt  
     - 2 = Fairly corrupt  
     - 3 = Not very corrupt  
     - 4 = Not corrupt at all  

2. **Q199 - Voting in National Elections**  
   - **Type:** Binary (Categorical)  
   - **Scale:** Whether the respondent has voted in the last national election.  
   - **Example Values:**
     - 1 = Yes  
     - 2 = No  

3. **Q234 - Participation in Lawful Demonstrations**  
   - **Type:** Binary (Categorical)  
   - **Scale:** Indicates if the respondent has participated in peaceful protests.  
   - **Example Values:**
     - 1 = Yes  
     - 2 = No  

4. **Q71 - Confidence in the National Government**  
   - **Type:** Ordinal  
   - **Scale:** Level of trust in the national government.  
   - **Example Values:**
     - 1 = A great deal  
     - 2 = Quite a lot  
     - 3 = Not very much  
     - 4 = None at all  

5. **Q70 - Confidence in the Justice System**  
   - **Type:** Ordinal  
   - **Scale:** Trust in the justice system.  
   - **Example Values:**
     - 1 = A great deal  
     - 2 = Quite a lot  
     - 3 = Not very much  
     - 4 = None at all  

6. **Q106 - Economic Situation of the Country**  
   - **Type:** Ordinal  
   - **Scale:** Respondents’ evaluation of the national economy.  
   - **Example Values:**
     - 1 = Very good  
     - 2 = Rather good  
     - 3 = Bad  
     - 4 = Very bad  

7. **Q260 - Education Level**  
   - **Type:** Ordinal  
   - **Scale:** Highest level of education completed.  
   - **Example Values:** *(Country-specific variations may exist)*
     - 1 = No formal education  
     - 2 = Primary education  
     - 3 = Secondary education  
     - 4 = University degree or higher  

8. **Q279 - Age**  
   - **Type:** Continuous (Numerical)  
   - **Scale:** Age in years (exact value).  
   - **Example Values:**  
     - 18, 25, 40, 60, etc.

## Notes:
- **Ordinal variables**: Have an inherent order but the distance between categories is not necessarily equal (e.g., trust levels, economic perception).  
- **Binary variables**: Represent a **yes/no** response (participation in voting or demonstrations).  
- **Continuous variables**: Numeric values that can take any number within a range (e.g., age).  

These variables allow for an in-depth analysis of how trust in institutions, economic perceptions, and demographic factors interact with political engagement in the context of perceived corruption.

