# Color-changing-button

#html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Changing Button</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <button class="color-button">Hover Over Me!</button>
    </div>
</body>
</html>









#css


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
    font-family: 'Arial', sans-serif;
}

.container {
    text-align: center;
}

.color-button {
    background-color: #4CAF50;
    color: white;
    padding: 15px 32px;
    font-size: 16px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.2s ease;
}

.color-button:hover {
    background-color: #ff5722;
    transform: scale(1.1);
}


![image](https://github.com/user-attachments/assets/8ba47b5f-225c-4d83-b2d8-d582ac11e014)

![image](https://github.com/user-attachments/assets/f8f5badc-31da-42a7-92b2-7615f4587f5b)

