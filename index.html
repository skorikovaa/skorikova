<!DOCTYPE html>
<html>
<head>
    <title>TODO List</title>
</head>
<body>
    <h1>Список TODO пользователей</h1>
    <button onclick="getList()">Получить список</button>
    <table id="todoTable">
        <thead>
            <tr>
                <th>№</th>
                <th>Пользователь</th>
                <th>Задача</th>
                <th>Выполнено</th>
            </tr>
        </thead>
        <tbody id="todoBody"></tbody>
    </table>

    <script>
        function getList() {
            var xhr = new XMLHttpRequest();
            xhr.open("GET", "https://jsonplaceholder.typicode.com/todos", true);
            xhr.onreadystatechange = function() {
                if (xhr.readyState === 4 && xhr.status === 200) {
                    var todoData = JSON.parse(xhr.responseText);
                    getUsers(todoData);
                }
            };
            xhr.send();
        }

        function getUsers(todoData) {
            var xhr = new XMLHttpRequest();
            xhr.open("GET", "https://jsonplaceholder.typicode.com/users", true);
            xhr.onreadystatechange = function() {
                if (xhr.readyState === 4 && xhr.status === 200) {
                    var usersData = JSON.parse(xhr.responseText);
                    populateTable(todoData, usersData);
                }
            };
            xhr.send();
        }

        function populateTable(todoData, usersData) {
            var todoTable = document.getElementById("todoBody");
            for (var i = 0; i < todoData.length; i++) {
                var tr = document.createElement("tr");
                var user = usersData.find(user => user.id === todoData[i].userId);
                var completed = todoData[i].completed ? "Да" : "Нет";
                tr.innerHTML = `
                    <td>${i + 1}</td>
                    <td>${user.name}</td>
                    <td>${todoData[i].title}</td>
                    <td>${completed}</td>
                `;
                todoTable.append(tr);
            }
        }
    </script>
</body>
</html>