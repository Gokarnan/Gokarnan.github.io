<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Page</title>
    <style>
        /* Reset default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Create a beautiful gradient background */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #ffffff;
            overflow: hidden;
        }

        /* Main design card container */
        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 3rem 2rem;
            border-radius: 20px;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
            text-align: center;
            max-width: 90%;
            width: 500px;
            animation: fadeIn 1.5s ease-out;
        }

        /* Large welcome title */
        h1 {
            font-size: 2.8rem;
            margin-bottom: 1.5rem;
            letter-spacing: 1px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }

        /* Divider line design */
        .divider {
            height: 4px;
            width: 60px;
            background-color: #ff758f;
            margin: 0 auto 1.5rem auto;
            border-radius: 2px;
        }

        /* Author text style */
        p {
            font-size: 1.2rem;
            font-weight: 300;
            letter-spacing: 0.5px;
            opacity: 0.9;
        }

        /* Highlight your name */
        .name {
            font-weight: 600;
            color: #ff758f;
            display: block;
            margin-top: 0.5rem;
            font-size: 1.5rem;
            text-transform: uppercase;
        }

        /* Smooth fade-in animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <!-- The visible page content -->
    <div class="card">
        <h1>Welcome to My Page</h1>
        <div class="divider"></div>
        <p>This page was proudly made by:</p>
        <span class="name">Gokarnan</span>
    </div>

</body>
</html>

