# SQL

1. Выведите все записи из таблицы salaries

select * from salaries;

![1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/4dce9bf4-d29a-4c4d-a4fb-c65061be92d1)

2. Выведите уникальные значения столбца emp_no из таблицы salaries

select distinct emp_no from salaries

![2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/a38db99d-bcb6-47a2-a611-31eaf3232d70)

3. Выведите записи с зарплатой больше 50000 и меньше 70000 из таблицы salaries

select * from salaries where salary > '50000' and salary < '70000'

![3](https://github.com/Nikita-Titkov/course_qa/assets/128616431/a14c3476-69af-4fe7-a633-16ede941e755)

4.Выведите записи, где зарплата равна 60000 или 70000 из таблицы salaries

 select* from salaries where salary = '60000' or salary = '70000'

 ![4](https://github.com/Nikita-Titkov/course_qa/assets/128616431/1d5911e9-6869-4b1e-9937-e6a2675388fc)

5. Выведите записи, где зарплата не равна 50000 из таблицы salaries

select * from salaries where salary = '50000'

![5](https://github.com/Nikita-Titkov/course_qa/assets/128616431/2cf102a2-0427-4763-a63a-8dd179550292)

6. Отсортируйте записи по столбцу from_date в порядке возрастания из таблицы salaries

Отсортируйте записи по столбцу from_date в порядке возрастания из таблицы salaries

select * from salaries order by from_date asc

![6](https://github.com/Nikita-Titkov/course_qa/assets/128616431/c1cab07b-b7e0-44c5-b9f7-024663f663e1)

7. Вставьте новую запись в таблицу salaries

insert into salaries (emp_no, salary, from_date, to_date) values ('51', '55000', '2045-10-16', '9999-01-01')

![7](https://github.com/Nikita-Titkov/course_qa/assets/128616431/2d5ccdd1-66bc-4012-ab49-a4daa89d2538)

8. Выведите записи, где значение столбца to_date равно NULL из таблицы salaries

select * from salaries where to_date is null

![8](https://github.com/Nikita-Titkov/course_qa/assets/128616431/abdaf82e-cdf3-426f-98b9-84fa50fbf251)

9. Обновите значение столбца salary на 90000 для записи, где emp_no равно 100 из таблицы salaries

update salaries
set salary = 90000
where emp_no = 100

![9](https://github.com/Nikita-Titkov/course_qa/assets/128616431/d7cde8a9-dd3a-4e6f-91ec-3d15efeecd64)

10. Удалите записи, где значение столбца salary меньше 50000 из таблицы salaries

delete from salaries
where salary < 50000

![10](https://github.com/Nikita-Titkov/course_qa/assets/128616431/554604ab-1b3e-4840-83ae-69b6c12d5b09)

11. Выведите только уникальные значения столбца emp_no из таблицы salaries, отсортированные в порядке убывания

select distinct * from salaries order by emp_no desc

![11](https://github.com/Nikita-Titkov/course_qa/assets/128616431/26bf9a3b-7d11-4bc3-846e-d070320f06a4)

12. Выведите записи из таблицы salaries, где зарплата равна 60000 и to_date не равно NULL

select * from salaries where salary = '60000' and to_date is not null

![12](https://github.com/Nikita-Titkov/course_qa/assets/128616431/29463699-7f63-4d7e-b675-f37eb95cc0b4)

13. Выведите записи из таблицы salaries, где зарплата равна 50000 или emp_no равно 100

select * from salaries where salary = '50000' or emp_no = '100'

![13](https://github.com/Nikita-Titkov/course_qa/assets/128616431/8f0675f3-73b0-4fd6-998b-68510a09fc9c)

14. Отобразите записи из таблицы salaries, где from_date позже '2022-01-01' и to_date раньше '2023-01-01'

select * from salaries where from_date > '2022-01-01' and to_date < '2023-01-01'

![14](https://github.com/Nikita-Titkov/course_qa/assets/128616431/e00c87f2-c4a9-4640-92c2-0b905d5e4a0f)

15. Выведите записи из таблицы salaries, отсортированные по столбцу salary в порядке убывания, а затем по столбцу from_date в порядке возрастания

select * from salaries order by salary desc, from_date asc

![15](https://github.com/Nikita-Titkov/course_qa/assets/128616431/753aab76-d1ac-4e20-8d59-79c1d536ff0d)

16. Вставьте новую запись в таблицу salaries с автоматически сгенерированным значением emp_no:–VALUES (DEFAULT);

insert into salaries (emp_no, salary, from_date, to_date)
values (default, '515000', '2023-01-01', '2023-12-31')  

![16](https://github.com/Nikita-Titkov/course_qa/assets/128616431/4d7a3052-446c-4c34-881f-5ffbf01cd5d0)

17. Обновите значение столбца to_date на '2022-12-31' для всех записей, где salary меньше 60000

update salaries
set to_date = '2022-12-31'
where salary < '60000'

![17](https://github.com/Nikita-Titkov/course_qa/assets/128616431/47f3e7b2-db74-4dcb-af1c-e1b2692efe39)

18. Удалите все записи из таблицы salaries, где to_date равно NULL

delete from salaries
where to_date is null

![18](https://github.com/Nikita-Titkov/course_qa/assets/128616431/65523d56-9b03-4242-9736-6a451f4f5b4c)

19. Выведите записи из таблицы salaries, где зарплата равна NULL

select * from salaries where salary is null

![19](https://github.com/Nikita-Titkov/course_qa/assets/128616431/27596e4c-f09f-434a-a404-ba988348dc99)

20. Выведите только первые 10 записей из таблицы salaries

select * from salaries limit 10

![21](https://github.com/Nikita-Titkov/course_qa/assets/128616431/db01ad41-bc58-4c1e-b630-14ffc19ebd31)

21. Выведите записи из таблицы salaries, где зарплата не равна 50000 и from_date больше '2022-01-01'

select * from salaries where salary <> '50000' and from_date > '2022-01-01'

![22](https://github.com/Nikita-Titkov/course_qa/assets/128616431/85a0cc64-fa07-4654-9d6f-11cf876dff27)

22. Выведите записи из таблицы salaries, где emp_no входит в список (100, 200, 300)

select * from salaries where emp_no in (100, 200, 300)

![23](https://github.com/Nikita-Titkov/course_qa/assets/128616431/7fea4ba5-7e30-47a0-9b28-a1d82d406cf4)

23. Выведите записи из таблицы salaries, где emp_no не входит в список (100, 200, 300)

select * from salaries where emp_no not in (100, 200, 300)

![24](https://github.com/Nikita-Titkov/course_qa/assets/128616431/21f57268-81ff-4c9e-a10e-043e9de71804)

24. Отобразите записи из таблицы salaries, отсортированные по столбцу emp_no и from_date в порядке возрастания

select * from salaries order by emp_no, from_date asc

![25](https://github.com/Nikita-Titkov/course_qa/assets/128616431/538c4992-4fbc-4a35-9941-535d6b06c264)

25. Выведите записи из таблицы salaries, где зарплата равна 50000 и сотрудник был нанят после 1 января 2000 года

select * from salaries where salary = '50000' and from_date > '2000-01-01'

![27](https://github.com/Nikita-Titkov/course_qa/assets/128616431/3c761fe8-ea15-41df-bb21-13d376b239a5)

26. Выведите записи из таблицы salaries, где зарплата превышает 50000

select * from salaries where salary > '50000'

![28](https://github.com/Nikita-Titkov/course_qa/assets/128616431/5ff8865c-62e9-4cce-9a61-2c7c5cb79354)

27. Выведите только уникальные значения зарплаты из таблицы salaries

select distinct salary from salaries

![29](https://github.com/Nikita-Titkov/course_qa/assets/128616431/7fbc06e8-4b47-44bf-8b53-711819769584)

28. Выведите все записи из таблицы employees

    select * from employees

    ![30](https://github.com/Nikita-Titkov/course_qa/assets/128616431/da6ff846-ec30-4bdd-a1f0-28ba22a865d1)

29. Выведите только уникальные значения столбца emp_no из таблицы employees:

select distinct emp_no from employees

![31](https://github.com/Nikita-Titkov/course_qa/assets/128616431/9d827052-6b10-4cd1-9435-b9ac4ac15ba9)

30. Выведите записи из таблицы employees, где пол (gender) равен 'M' и дата найма (hire_date) больше '2000-01-01':

select * from employees where gender = 'M' and hire_date > '2000-01-01'

![32](https://github.com/Nikita-Titkov/course_qa/assets/128616431/440aa8bc-c37e-4a3a-8cea-07779efa5ed2)

31. Выведите записи из таблицы employees, где пол (gender) равен 'M' или дата найма (hire_date) меньше '1995-01-01'

select * from employees where gender = 'M' and hire_date < '1995-01-01'

![33](https://github.com/Nikita-Titkov/course_qa/assets/128616431/76e0e41e-dcfd-46d3-a0b6-cafdaf51da01)

32. Выведите записи из таблицы employees, где пол (gender) не равен 'F':

select * from employees where gender <> 'F'

![34](https://github.com/Nikita-Titkov/course_qa/assets/128616431/96a5e35d-adab-4c23-9195-c102aef1e345)

33. Отсортируйте записи из таблицы employees по столбцу hire_date в порядке возрастания:

select * from employees order by hire_date asc

![35](https://github.com/Nikita-Titkov/course_qa/assets/128616431/9ad3679a-0f7f-4d2e-80aa-770dba0c3da4)

34. Вставьте новую запись в таблицу employees:

insert into employees (emp_no, birth_date, first_name, last_name, gender, hire_date)
values ('51', '1984-06-17', 'Sam', 'Loudermilk', 'M', '2017-05-05')

![36](https://github.com/Nikita-Titkov/course_qa/assets/128616431/6d6425bf-b0c5-41b8-a874-5cc5b0ba1a85)

35. Выведите записи из таблицы employees, где значение столбца last_name равно NULL:

select * from employees where last_name is null

![37](https://github.com/Nikita-Titkov/course_qa/assets/128616431/01f1cd4a-b539-4acb-b3f1-6009252acd7c)

36. Обновите значение столбца first_name на 'Jane' для записи, где emp_no равно 10:

update employees
set first_name = 'Jane'
where emp_no = 10

![38](https://github.com/Nikita-Titkov/course_qa/assets/128616431/1c298958-5481-43a8-9485-d2fbc8cea7c9)

37. Удалите записи из таблицы employees, где значение столбца gender равно 'F'

delete from employees
where gender = 'F'

![39](https://github.com/Nikita-Titkov/course_qa/assets/128616431/ee3b66dd-3a63-4d4b-aeae-7033cadb040a)






















