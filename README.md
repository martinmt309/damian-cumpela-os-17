# damian-cumpela-os-17
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Animada para Damián</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea, #764ba2);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            background-color: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            animation: fadeIn 1s ease-out;
        }

        h1 {
            font-size: 2.5rem;
            color: #333;
            margin: 0 0 10px;
            animation: slideIn 0.8s ease-out;
        }

        p {
            font-size: 1.2rem;
            color: #555;
            margin: 0 0 20px;
        }

        .button {
            background-color: #764ba2;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .button:hover {
            transform: scale(1.05);
            background-color: #667eea;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateY(-20px); }
            to { transform: translateY(0); }
        }
    </style>
</head>
<body>
    <audio autoplay loop>
        <source src="los_niños_maravilla.mp3" type="audio/mpeg">
        Tu navegador no soporta la reproducción de audio.
    </audio>    
    <div class="container">
        <h1>¡Hola, Damián!</h1>
        <p>Esta página está dedicada a ti, por ser un amigo increíble y siempre estar ahí. ¡Gracias por todo!</p>
        <button class="button">¡Eres el mejor!</button>
    </div>
</body>
</html>
