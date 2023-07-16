# Postman Homework 1

## EP_1
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]

![1](https://github.com/Nikita-Titkov/course_qa/assets/128616431/173c9e86-4c77-4438-8ffd-a2a587fb59ee)

## EP_2
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}

![2](https://github.com/Nikita-Titkov/course_qa/assets/128616431/79df0dd0-fe25-4a5d-a876-fe3fe73d606a)

## EP_3
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
![EP3 - My Workspace](https://github.com/Nikita-Titkov/course_qa/assets/128616431/f556920f-e4cd-4875-8adb-96aae434b8b7)

## EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
![4](https://github.com/Nikita-Titkov/course_qa/assets/128616431/ffd0b455-06e0-4fa0-8985-8cdda10d96e7)


## EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }

![5](https://github.com/Nikita-Titkov/course_qa/assets/128616431/0cd1858a-7306-47e5-95f3-c89247830051)

## EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}

![6](https://github.com/Nikita-Titkov/course_qa/assets/128616431/97c404df-4d2c-4de3-af45-194526e5f793)

## EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}


![7](https://github.com/Nikita-Titkov/course_qa/assets/128616431/9291ad13-20ab-43a4-ab67-1d64d4dadb2b)






