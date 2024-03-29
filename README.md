# Arch12
Урок 12. Принципы тестирования приложений

План тестирования облачного сервиса и приложения по управлению роботом-пылесосом

1. Unit – тесты: Пишутся по мере написания кода на классы и методы API облачного сервиса, API обновления, авторизации и мобильного приложения.
2. E2E-тестирование: Проводим после завершения работы над кодом. Тестируем каждую систему на работоспособность. При этом воздействуем на систему через ее самые внешние интерфейсы и проверяем ожидаемую реакцию системы через эти же интерфейсы. Таблица 1. Протокол тестирования API облачной системы
   
<img width="380" alt="265516565-cec00f77-1c06-4597-a28c-d6cb2f973cca" src="https://github.com/OSADOK/Arch12/assets/114491935/74564a2a-855b-40a8-b090-7bfc7d8165dd">

3. UAT – тестирование: готовый программный продукт тестирует ограниченный круг пользователей. Тестируется каждый case из UseCase диаграммы. При этом группа людей изучает эффективность сервиса, его функционала. UAT нужен для того, чтобы понять: а) как ведет себя продукт в реальных условиях, соответствует ли результат задумке; б) выявить, были ли добавлены все возможные функции; в) проверить, есть ли ошибки, которые будут мешать пользователю.
   
Таблица 2. UAT – тестирование приложения робота-пылесоса

<img width="593" alt="265516757-d03d4266-c661-4e24-8d48-39e2287b4c6e" src="https://github.com/OSADOK/Arch12/assets/114491935/1a036829-8d5d-4765-941c-688b09127d4f">
<img width="591" alt="265516670-66c285c7-01f1-475c-b98e-d16bc588598c" src="https://github.com/OSADOK/Arch12/assets/114491935/fbcb6723-d7d7-4acb-92b2-f723e46e043b">
<img width="591" alt="265516840-ba6ba31b-2795-4f69-95fe-761cfb4d39a7" src="https://github.com/OSADOK/Arch12/assets/114491935/d0249798-8305-4b6c-aba0-92f9627775ab">
<img width="588" alt="265516903-4b669a20-0ae7-4b1b-b8e5-f72f020feffc" src="https://github.com/OSADOK/Arch12/assets/114491935/13a0b1e9-6193-44f9-8d3f-7540d01a0511">
<img width="593" alt="265516981-fc00f990-5454-430c-a62e-1d5704093ed8" src="https://github.com/OSADOK/Arch12/assets/114491935/e8daadb2-8ae8-476b-8f98-84dde132c6e0">




