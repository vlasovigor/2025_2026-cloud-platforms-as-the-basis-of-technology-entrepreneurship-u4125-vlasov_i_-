**University:** ITMO University  
**Faculty:** [FTMI]  
**Course:** Облачные платформы как основа технологического предпринимательства  
**Year:** 2025/2026  
**Group:** U4125  
**Author:** Vlasov Igor Alekseevich  
**Lab:** Lab2  
**Date of create:** 05.05.2026  
**Date of finished:** TBD

## Отчет по лабораторной работе "Исследование Cloud Run"  
**Цель работы**  
Ознакомиться с работой Cloud Run


**Ход работы:**

Создан сервис из демо-образа hello
<img width="1645" height="731" alt="image" src="https://github.com/user-attachments/assets/d51a03b6-4a50-418a-aa4c-188878d87df2" />

Сервис протестирован и открывается по url
<img width="1878" height="844" alt="image" src="https://github.com/user-attachments/assets/334312c4-677d-497c-8b9d-1636114b5202" />

На странице с логами отображаются запросы и их параметры:
<img width="1622" height="614" alt="image" src="https://github.com/user-attachments/assets/77404e1b-29b9-4b48-84df-58f32bd90be3" />

Метрики собираются:
<img width="1671" height="772" alt="image" src="https://github.com/user-attachments/assets/4bd9ea41-5656-4975-abca-9dbd3fc4fd1f" />


Для тестирования была развернута новая ревизия с портом 8090:
<img width="1653" height="801" alt="image" src="https://github.com/user-attachments/assets/8c63a270-4c23-42dc-a5b2-7e3f08711202" />

Также изучена возможность разделения траифка между ревизиями
<img width="1648" height="610" alt="image" src="https://github.com/user-attachments/assets/1b34c0c4-44bb-4479-9795-4961a1770a91" />
<img width="898" height="316" alt="image" src="https://github.com/user-attachments/assets/672937d8-1fa9-467a-87d1-80bf448ef659" />
<img width="992" height="383" alt="image" src="https://github.com/user-attachments/assets/14da190b-a6a4-4087-8864-0e977dffdc47" />

После работы все запущенные серисы были удалены.

**Выводы:**
В ходе лабораторной работы были изучены возможности запуска сервисов посредством Cloud Run, а также дополнительные возможности отслеживания метрик, логгирования, а также настройки балансировки трафика между версиями.
