# Postman HW_2

## http://162.55.220.72:5005/first

1. Отправить запрос.
2. Статус код 200
3. Проверить, что в body приходит правильный string.
![P1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/8b5470cf-80fe-4c6b-aea5-9697ee0ff124)
![P1 1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/fe9012bc-1937-45e8-b110-7c1f15bee772)

## http://162.55.220.72:5005/user_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Проверить, что name в ответе равно name s request (name вбить руками.)
5. Проверить, что age в ответе равно age s request (age вбить руками.)
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)
7. Спарсить request.
8. Проверить, что name в ответе равно name s request (name забрать из request.)
9. Проверить, что age в ответе равно age s request (age забрать из request.)
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
11. Вывести в консоль параметр family из response.
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)
![P2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/e28fb4fc-d425-49f8-8dc1-13295e05afda)
![P2 2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/a954642a-ac91-4392-a4f1-756f9789d038)
![P2 3](https://github.com/Nikita-Titkov/course_qa/assets/128616431/5037be4d-b4da-4475-8626-6aa13ec089e6)

## http://162.55.220.72:5005/object_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age s request (age забрать из request.)
7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
8. Вывести в консоль параметр family из response.
9. Проверить, что у параметра dog есть параметры name.
10. Проверить, что у параметра dog есть параметры age.
11. Проверить, что параметр name имеет значение Luky.
12. Проверить, что параметр age имеет значение 4.
![P3 1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/0ea54318-1f93-4556-b7a5-a397edcfb9d6)
![P3 2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/81b0488b-6c27-4ede-98fc-7349ac7ec9a4)
![P3 3](https://github.com/Nikita-Titkov/course_qa/assets/128616431/98daac49-d848-43e2-a41f-0025618bf98a)
![P3 4](https://github.com/Nikita-Titkov/course_qa/assets/128616431/01367649-19a4-4aa1-8290-3518e2327251)

##http://162.55.220.72:5005/object_info_4
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age из request (age забрать из request.)
7. Вывести в консоль параметр salary из request.
8. Вывести в консоль параметр salary из response.
9. Вывести в консоль 0-й элемент параметра salary из response.
10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.
11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.
12. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)
13. Создать в окружении переменную name
14. Создать в окружении переменную age
15. Создать в окружении переменную salary
16. Передать в окружение переменную name
![P4 1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/c643833b-2b62-4911-9acd-0c00016c3b98)
![P4 2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/8fbee644-2405-4e1f-a757-fc3668919225)
![P4 3](https://github.com/Nikita-Titkov/course_qa/assets/128616431/04358f17-b05e-412b-9628-70535df7b18c)

## http://162.55.220.72:5005/user_info_2
1. Вставить параметр salary из окружения в request
2. Вставить параметр age из окружения в age
3. Вставить параметр name из окружения в name
4. Отправить запрос.
5. Статус код 200
6. Спарсить response body в json.
7. Спарсить request.
8. Проверить, что json response имеет параметр start_qa_salary
9. Проверить, что json response имеет параметр qa_salary_after_6_months
10. Проверить, что json response имеет параметр qa_salary_after_12_months
11. Проверить, что json response имеет параметр qa_salary_after_1.5_year
12. Проверить, что json response имеет параметр qa_salary_after_3.5_years
13. Проверить, что json response имеет параметр person
14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request.)
15. Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request.)
16. Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request.)
17. Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request.)
18. Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request.)
19. Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request.)
20. Проверить, что что параметр u_age равен age из request (age забрать из request.)
21. Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request.)
![P5 1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/5c1a1a5b-463f-4ea2-8584-a90da3afaeb3)
![P5 2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/db579518-5d42-4779-8ac5-d5a4b0901c46)
![P5 3](https://github.com/Nikita-Titkov/course_qa/assets/128616431/490f0d4a-3c6a-4258-a592-c7077e909545)
![P5 4](https://github.com/Nikita-Titkov/course_qa/assets/128616431/820d137d-1198-4f0b-9902-9f967dc2e612)











