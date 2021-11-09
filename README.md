# activity-analysis
analysis of the activity of students of the online course "Introduction to Data Analysis in R", thanks to the stepik team for providing anonymized data.
Описание данных:

events_train.csv - данные о действиях, которые совершают студенты со стэпами

    step_id - id стэпа
    user_id - анонимизированный id юзера
    timestamp - время наступления события в формате unix date
    action - событие, возможные значения: 

    discovered - пользователь перешел на стэп
    viewed - просмотр шага,
    started_attempt - начало попытки решить шаг, ранее нужно было явно нажать на кнопку - начать решение, перед тем как приступить к решению практического шага
    passed - удачное решение практического шага

submissions_train.csv - данные о времени и статусах сабмитов к практическим заданиям

    step_id - id стэпа
    timestamp - время отправки решения в формате unix date
    submission_status - статус решения
    user_id - анонимизированный id юзера

