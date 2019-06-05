# boot-thymeleaf
<form th:object="${user}" 
                     th:action="@{'/users/{id}'(id=${user.id})}" 
                        th:method="put">
이거 고치면 작동
