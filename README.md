# School District Analysis

## Project Overview
The project was to build reporting for school board members to review the school district's testing assessments after discovering evidence of academic dishonesty with Thomas High School 9th graders reading & math grades appear to have been altered. The school board asked for the analysis report to remove Thomas High School 9th graders reading & math grades and re-evaluate school district's assessments.

The project analysis results are categorized into the following:
  - Overall District Summary
  - Overall School Summary
  - High and Low Performing Schools
  - Math and Reading Scores by Grade
  - Scores by School Spending
  - Scores by School Size
  - Scores by School Type

## School District Analysis Results:
  - Overall District Summary:
    Indicates minimal data with no effects to the overall district summary:
    
    - Overall District Summary
    ![district summary](https://user-images.githubusercontent.com/92836648/143784006-f50c9501-99a5-4c87-ae83-58a89b858773.png)
    
      - Code evaluations
        
        ![district summary passing math_reading_percentage](https://user-images.githubusercontent.com/92836648/143784789-d4c1ae36-04b4-42d3-9e3f-7eb05aba3e35.png)
        ![district summary overall_passing_percentage](https://user-images.githubusercontent.com/92836648/143784788-a3dcb99b-a0d3-427f-90f3-141712d6b430.png)
      
    - Overall District Summary without Thomas High School 9th grader scores
    ![district summary without ths_9](https://user-images.githubusercontent.com/92836648/143784469-9f722a15-9033-49cd-8776-9a5795d8d89d.png)
    
      - Code evaluations
        
        ![district summary without ths_9 new student count](https://user-images.githubusercontent.com/92836648/143784792-0207778e-225d-46b6-a851-b4bcc2585ea6.png)
        ![district summary passing without ths_9 math_reading_percentage](https://user-images.githubusercontent.com/92836648/143784791-7960acc4-df19-430d-ab39-1074086dceec.png)
        ![district summary without ths_9 overall_passing_percentage](https://user-images.githubusercontent.com/92836648/143784793-2c8e6332-820b-4b9e-bc69-f16c794875f1.png)
        
  - Overall School Summary:
    Indicates a signifficant drop in % Passing Math, % Passing Reading, and % Overall with dataframes values evaluated from original analysis, THS 9th grade scores set to NaN,
    but analysis without THS 9th grade scores show minimal changes:
    
      |               | Original Analysis | THS 9th grade scores (NaN)  | Analysis without THS 9th grade scores |
      |---------------|-------------------|-----------------------------|---------------------------------------|
      |%Passing Math    | 93.2% | 66.9% | 93.1% |
      |%Passing Reading | 97.3% | 69.6% | 97.0% |
      |%Overall Passing | 90.9% | 65.0% | 90.6% |

      - Original Analysis
      
        ![school summary](https://user-images.githubusercontent.com/92836648/143785727-d953082e-ddce-45cb-bc8e-07a10de97f42.png)
        
      - THS 9th grade scores (NaN)

        ![school summary with ths_9_nan](https://user-images.githubusercontent.com/92836648/143785725-09d05c59-8e94-45c7-a58f-e75a664fec2d.png)
        
      - Analysis without THS 9th grade scores
      
        ![school summary without ths_9_nan](https://user-images.githubusercontent.com/92836648/143785726-b7c04231-a871-4f28-9459-873668c0189c.png)
        
   - High and Low Performing Schools:

      - 5 Highest Performing Schools
        
        ![Top 5 High Performing Schools](https://user-images.githubusercontent.com/92836648/143786938-9f2a40de-8a07-4b70-b7ff-8aaad8987a76.png)

      - 5 Lowest Performing Schools

        ![Low 5 High Performing Schools](https://user-images.githubusercontent.com/92836648/143786943-ef8a20b9-4505-42f9-9d35-891e6ae039fd.png)
        
   - Math and Reading Scores by Grade:

      - Math Scores

        ![Math scores by grade](https://user-images.githubusercontent.com/92836648/143787084-41bfe3a7-8344-4c9e-836e-c9c77c0f80db.png)
        
      - Reading Scores

        ![Reading scores by grade](https://user-images.githubusercontent.com/92836648/143787089-3ebc6c06-be5f-4c90-b1b5-0573ce60d598.png)
        
   - Scores by School Spending:

        ![scores by school spending](https://user-images.githubusercontent.com/92836648/143786947-f721ea5b-35f8-4ea1-ac9d-f7196b90941c.png)
        
   - Scores by School Size:

        ![scores by school size](https://user-images.githubusercontent.com/92836648/143786946-0b3077f8-88f4-4137-a66c-4039185e5c44.png)
        
   - Scores by School Type:
        
        ![scores by school type](https://user-images.githubusercontent.com/92836648/143786948-8ce4b7e7-6851-4f09-ac4f-5bccafe3bbbd.png)


## Summary:
The revised coding `PyCitySchools_Challenge` for handle Thomas High School 9th grade scores required first to identify and change math and reading scores to NaN values, second filter out dataframe information pertaining to THS 9th grader scores, third to recount the total student minus THS 9th graders, and fourth re-evaluate the all different report outputs with removed THS 9th grade scores.
