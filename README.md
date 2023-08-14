
<!DOCTYPE html>
<html lang="en">
<style>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f2f2f2;
    padding: 10px;
    text-align: center;
}

main {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

section {
    margin-bottom: 30px;
}

h1, h2 {
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}


</style>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All About Apples</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>All About Apples</h1>
    </header>
    <main>
        <section id="how-to-eat">
            <h2>How to Eat an Apple</h2>
            <p>Here are some common ways to eat an apple:</p>
            <ul>
                <li>Wash the apple thoroughly under running water.</li>
                <li>Eat the apple as a whole, including the skin, which contains many nutrients.</li>
                <li>Slice the apple and eat the slices.</li>
                <li>Make applesauce or apple juice.</li>
                <li>Use apples in various recipes like salads or desserts.</li>
            </ul>
        </section>
        <section id="how-many-times">
            <h2>How Many Times Should You Eat Apples a Day?</h2>
            <p>The recommended daily consumption of apples varies depending on factors such as age, health status, and overall diet. In general, consuming one to two apples per day is considered beneficial for most individuals.</p>
        </section>
        <!-- Add more sections about apple varieties, health benefits, etc., if desired -->
<button id="changeColorBtn">Change Text Color</button>
    </main>

    <footer>
        <p>&copy; 2023 YourName. All rights reserved.</p>
    </footer>
<!-- Inside the <body> tag, just before the </body> closing tag -->


<script>

// Add this script at the end of the <body> tag, just before the </body> closing tag

    const changeColorBtn = document.getElementById('changeColorBtn');
    const body = document.body;

    changeColorBtn.addEventListener('click', () => {
        const randomColor = getRandomColor();
        body.style.color = randomColor;
    });

    function getRandomColor() {
        const letters = '0123456789ABCDEF';
        let color = '#';
        for (let i = 0; i < 6; i++) {
            color += letters[Math.floor(Math.random() * 16)];
        }
        return color;
    }


</script>

</body>
</html>
