<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>AI Text Checker</title>
</head>
<body>

<h1>Проверка текста</h1>

<textarea id="text" placeholder="Вставьте текст сюда"></textarea>

<button onclick="checkText()">Проверить</button>

<div id="result"></div>

<script>
function checkText() {
    const text = document.getElementById("text").value;

    if (!text.trim()) {
        document.getElementById("result").innerText =
            "Введите текст.";
        return;
    }

    document.getElementById("result").innerText =
        "Текст получен. Анализ будет здесь.";
}
</script>

</body>
</html>
