# База данных "Онлайн-школа"
Данный проект представляет собой базу данных для онлайн-школы, созданную с использованием SQLite и Python.
База данных предназначена для хранения информации об учениках, курсах и их записях на обучение. Она позволяет отслеживать, какой ученик на какой курс записан, а также даты начала и окончания обучения.
## Структура BD
База данных состоит из трёх основных таблиц:
###  Students (Ученики)
Содержит информацию об учениках:
- id — уникальный идентификатор ученика  
- name — имя ученика  
- age — возраст ученика  
###  Courses (Курсы)
Содержит информацию о курсах:
- id — уникальный идентификатор курса  
- title — название курса  
- mentor — преподаватель курса  
### Enrollments (Записи на курсы)
Связывает учеников и курсы:
- id_order — уникальный номер записи  
- id_student — ID ученика  
- id_course — ID курса  
- start_date — дата начала обучения  
- end_date — дата окончания обучения  
## Связи между таблицами
- Каждый ученик может быть записан на несколько курсов  
- Каждый курс может иметь несколько учеников  
- Таблица enrollments реализует связь "многие ко многим"

- <img width="760" height="827" alt="С" src="https://github.com/user-attachments/assets/45b511cd-8d9a-4e99-aa03-b75306a9d95b" />
<img width="1133" height="772" alt="2026-04-29_19-38-32" src="https://github.com/user-attachments/assets/0d8b9894-2517-4aa8-9c04-42e0fe530a0b" />
<img width="884" height="882" alt="2026-04-29_19-40-53" src="https://github.com/user-attachments/assets/880c35ef-30e3-4c50-8e02-a76763bcfbbc" />
<img width="951" height="584" alt="2026-04-29_19-41-54" src="https://github.com/user-attachments/assets/fe3aef16-6293-4abc-80b1-7bb80e6d7a97" />
<img width="1000" height="959" alt="2026-04-29_19-43-31" src="https://github.com/user-attachments/assets/752d7159-db24-4765-b6e8-c642183ec6af" />
<img width="1021" height="584" alt="2026-04-29_19-44-28" src="https://github.com/user-attachments/assets/630fe19d-b9e7-4afc-a244-d55cef7c59cd" />


