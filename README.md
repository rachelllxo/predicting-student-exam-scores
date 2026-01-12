# Predicting Student Exam Scores
## Dataset contains:   
Student id  
Age  
Gender  
Course    
Study hours    
Class attendance   
Internet access   
Sleep hours   
Sleep quality  
Study method   
Facility rating   
Exam difficulty  

## To predict: exam scores 

 ## About the Dataset  
 This dataset provides an extensive and realistic representation of various factors that contribute to student exam performance. It contains 20,000 records, each describing a student’s academic behavior, study habits, lifestyle routines, and exam conditions. These variables collectively help understand how different aspects of a student’s daily life and learning environment influence their exam outcomes.
 The dataset includes details such as daily study hours, class attendance percentage, sleep duration and quality, internet availability, study method, institutional facility rating, and exam difficulty level. These factors reflect a broad spectrum of influences commonly observed in educational settings. The exam score (0–100) is derived using a weighted formula that mimics real-life academic performance patterns.

For example:

Higher study hours and consistent attendance often correlate with stronger performance.
Better sleep quality and balanced rest contribute positively.
Coaching and mixed study methods typically help students achieve higher marks.
Limited internet access or poor institutional facilities may create a disadvantage.
Harder exam papers reduce achievable scores, while easier ones increase performance.

The dataset is fully synthetic yet designed to mirror logical and realistic student behavior. It contains no personally identifiable information and is suitable for educational research, statistical exploration, behavior analysis, institution-level studies, and general data-driven insights.

Whether used for visualizing score distributions, comparing study habits, evaluating lifestyle effects, or simply exploring student performance patterns, this dataset provides a well-structured and diverse foundation for understanding exam outcomes.

## Modeling Approach

Algorithm: Linear Regression

Training: Model trained on all features except student_id and age.

Evaluation:

Validation RMSE: 9.7

Observed that study hours, class attendance, and study method were the most influential features.

## Insights:

Students with higher study hours and consistent attendance generally score higher.

Balanced sleep with adequate study hours tends to improve scores.

Exam difficulty negatively impacts scores.  
## License

This project is open-source under the MIT License.

## Final Output: 
A CSV file with predicted exam scores along with student id.  
<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/674e0ab0-7d04-4ba1-907a-3bbdfbedac6a" />
