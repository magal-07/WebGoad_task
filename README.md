# WebGoad_task
# Звіт з виконання практичних завдань у WebGoat

## Частина 1. A01: Broken Access Control — Hijack a session

<img width="1280" height="912" alt="1" src="https://github.com/user-attachments/assets/d4064dfd-8210-426c-8f56-c0128a6da016" />

<img width="956" height="1121" alt="2" src="https://github.com/user-attachments/assets/8b2f9ee6-63f4-4a29-84d1-7e1a59d9a32a" />

<img width="949" height="1099" alt="3" src="https://github.com/user-attachments/assets/7ef85c4d-234f-4496-bda1-fced7c22ad83" />

<img width="643" height="514" alt="image" src="https://github.com/user-attachments/assets/fcc859bf-6efe-44c8-b809-c71a22f99ded" />


<img width="963" height="1093" alt="image" src="https://github.com/user-attachments/assets/31ce2397-75ab-4add-a255-d34d897dcfd2" />

<img width="1280" height="799" alt="image" src="https://github.com/user-attachments/assets/b33cf39e-df13-43d8-8b85-2d2e991016ba" />

<img width="1280" height="616" alt="image" src="https://github.com/user-attachments/assets/37e680a8-6acf-4ce0-b9d9-2f136375e3e1" />

Дадаткове завдання 
<img width="1280" height="771" alt="image" src="https://github.com/user-attachments/assets/aff2d03a-6de9-4d1f-b3ca-abc0b0ce895c" />
<img width="1280" height="684" alt="image" src="https://github.com/user-attachments/assets/0019fc45-9704-497d-a68f-f8b8f7bd66aa" />
' UNION SELECT userid, user_name, password, cookie, null, null, null FROM user_system_data --
<img width="684" height="737" alt="image" src="https://github.com/user-attachments/assets/f2b61752-514a-46d1-bfab-7f86f7e1fbb6" />

<img width="957" height="970" alt="image" src="https://github.com/user-attachments/assets/443a467c-3fe8-435d-b333-278ffc7aa867" />
Дослідження форми реєстрації:
У завданні SQL Injection  перевірено механізм реєстрації користувача.

Встановлено, що :

Якщо умова істинна (TRUE) — User ... already exists.

Якщо умова хибна (FALSE) — User ... created.

Аналіз HTTP-запиту:
У Burp Suite зафіксовано запит створення користувача:

Метод: PUT

URL: /WebGoat/SqlInjectionAdvanced/register

Автоматизація посимвольного витягування пароля (Python):
Оскільки сервер самостійно закриває лапку в кінці запиту, використано конструкцію:
tom' AND substring(password,1,1)='a
<img width="921" height="921" alt="image" src="https://github.com/user-attachments/assets/d920c80b-3719-43e0-8969-2fbb10e656e1" />

<img width="922" height="917" alt="image" src="https://github.com/user-attachments/assets/2f7b4b30-6d7f-4f27-a43d-ec66f505e678" />
Для автоматизації перебору створено та виконано Python-скрипт
<img width="600" height="636" alt="image" src="https://github.com/user-attachments/assets/2c1c14ad-a84a-4e54-84a3-bef39cdda40b" />

<img width="507" height="453" alt="image" src="https://github.com/user-attachments/assets/1fd410b9-1ed1-4bc2-9b60-db188db73531" />
<img width="919" height="662" alt="image" src="https://github.com/user-attachments/assets/9da8a05c-3795-4cb9-a7c4-289aeb887cce" />



