# mi-primera-web
Mi primera página web hecha con HTML
<!DOCTYPE html>
<html>
<head>
    <title>Matias | Programador</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: linear-gradient(135deg, #1f1f1f, #2c3e50);
            color: white;
        }

        header {
            text-align: center;
            padding: 50px;
        }

        section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
        }

        .card {
            background: #34495e;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        a {
            color: #00ffcc;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Hola, soy Matias 👋</h1>
    <p>Programador en formación 💻</p>
</header>

<section>
    <div class="card">
        <h2>Sobre mí</h2>
        <p>Tengo 16 años y estoy aprendiendo programación. Me enfoco en mejorar cada día y construir proyectos reales.</p>
    </div>
    <div class="card">
    <h2>Contacto</h2>

    <p>📧 Email: 
        <a href="mailto:matiasvillegas112009@gmail.com">
            matiasvillegas112009@gmail.com
        </a>
    </p>

    <br>

    <button onclick="window.open('https://github.com/Matias1129')">
        Ver mi GitHub
    </button>
</div>

  

    
