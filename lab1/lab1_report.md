**University:** ITMO University  
**Faculty:** [FTMI]  
**Course:** Облачные платформы как основа технологического предпринимательства  
**Year:** 2025/2026  
**Group:** U4125  
**Author:** Vlasov Igor Alekseevich  
**Lab:** Lab1  
**Date of create:** 05.05.2026  
**Date of finished:** TBD

## Отчет по лабораторной работе "Обзор Google Cloud и исследование основных сервисов"  
**Цель работы**  
Ознакомиться с основными возможностями и преимуществами облачной платформы Google Cloud.  

**Ход работы**
1. Заполнил форму и получил доступ к аккаунту в Google Cloud.
2. Создан Сервисный аккаунт с ролью Storage Admin
<img width="807" height="105" alt="image" src="https://github.com/user-attachments/assets/25a7fa42-059e-4c9e-99d9-c79a187b3ab8" />
3. Создана виртуальная машина с Machine type e2-micro в режиме spot с использованием сервисного аккаунта, созданного на первом шаге.
<img width="759" height="188" alt="image" src="https://github.com/user-attachments/assets/29948187-3e58-4bdd-8e7f-b54fd81b3f1a" />
<img width="753" height="365" alt="image" src="https://github.com/user-attachments/assets/d39fd503-0731-456c-b8e7-c7cc79f7f026" />
<img width="1430" height="526" alt="image" src="https://github.com/user-attachments/assets/1356e982-a9e9-4d35-88bc-770d0ee506d4" />
<img width="1125" height="37" alt="image" src="https://github.com/user-attachments/assets/fc662db7-3376-4b38-adcd-0a7103c2d1c5" />

4. Бакет "lab1-bucket-itmo" был найден
 <img width="555" height="445" alt="image" src="https://github.com/user-attachments/assets/af8363b4-005e-4a9a-bfd1-4ad796d3bfd9" />

5. Файлы были скопированы из бакета на виртуальную машину: 
<img width="605" height="515" alt="image" src="https://github.com/user-attachments/assets/8323cf6c-0c72-41ea-b9cc-0735f1d19a51" />

6. После была заменена роль для аккаунта на Compute Viewer
<img width="1548" height="651" alt="image" src="https://github.com/user-attachments/assets/fc25b483-d68e-4622-95c5-829eea2a3e0f" />
<img width="915" height="162" alt="image" src="https://github.com/user-attachments/assets/80df3a69-3791-41a6-bfa1-c6dc8204f955" />

7. Сразу после изменения типа аккаунта копирования также возможно:
<img width="578" height="326" alt="image" src="https://github.com/user-attachments/assets/8964a1ba-1f39-484d-909d-9aaf12b03015" />

8. Спустя некоторое время копирование было запрещено.
9. Виртаульная машина удалена после использования
<img width="1337" height="298" alt="image" src="https://github.com/user-attachments/assets/efe6d8b0-ed96-4a9d-84cc-8314ac33382d" />

10. На основании этого можно сделать вывод, что в зависимости от ролей сервисного аккаунта предоставляется доступ к общему хранилищу проекта, а именно:
- Storage Admin предоставляет полный доступ к Cloud Storage.
- Compute Viewer не предоставляет доступ к Cloud Storage.

**Вывод:**
В ходе лабораторной работы удалось ознакомиться с базовыми возможностями Google Cloude, создать сервисный аккаунт, назначить и изменить роль, а также создать и удалить виртуальную машину.
