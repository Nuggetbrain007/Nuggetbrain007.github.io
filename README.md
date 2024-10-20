<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thiệp Chúc Mừng 20/10</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f5f0ff; /* Màu nền sáng nhẹ */
        }

        .card {
            width: 60%;
            max-width: 700px;
            margin: 50px auto;
            background-color: #e5d5ff; /* Màu nền thiệp tím nhạt */
            border-radius: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 30px;
        }

        h1 {
            color: #9c27b0; /* Màu chữ tiêu đề tím đậm */
            font-size: 3rem;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.2rem;
            color: #555;
            margin: 15px 0;
        }

        .heart {
            font-size: 5rem;
            color: #ba68c8; /* Màu trái tim tím */
            animation: heartbeat 1.5s infinite;
        }

        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }

        .footer {
            margin-top: 20px;
            font-size: 1rem;
            color: #777;
        }

        .button {
            margin-top: 30px;
            padding: 10px 20px;
            font-size: 1rem;
            color: white;
            background-color: #9c27b0; /* Màu nút tím đậm */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #7b1fa2; /* Màu nút tím nhạt khi hover */
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Chúc Mừng 20/10 ❤️</h1>
        <p>Chúc cậu luôn xinh đẹp, hạnh phúc và gặp nhiều may mắn trong cuộc sống.</p>
        <p>Cảm ơn cậu vì đã luôn ở bên tớ. Mỗi ngày có cậu là một ngày thật đặc biệt!</p>
        <div class="heart">💖</div>
        <button class="button" onclick="alert('Tớ yêu cậu nhiều lắm!')">Nhấn để nhận bất ngờ!</button>
        <div class="footer">From: Tớ ❤️</div>
    </div>
</body>
</html>
