# Forma rectagulo

# Extensión
HTML Content

# Medida 
```DAX
Medida = 
VAR titulo = " Mayu La Mejor" 
RETURN
"
<!DOCTYPE html>
<html lang='es'>
<head>
<meta charset='UTF-8'>
<title>Animación CSS</title>
<style>
  body {
    background: #FFFFFF;
    color: #f1f5f9;
    font-family: Arial, sans-serif;
  }

  .marquee {
    overflow: hidden;
    white-space: nowrap;
    box-sizing: border-box;
    border: 2px solid #FFFFFF;
    border-radius: 8px;
    background: #1e293b;
    padding: 10px;
  }

  .marquee span {
    display: inline-block;
    padding-left: 100%; /* espacio inicial para que arranque desde la derecha */
    animation: scroll 15s linear infinite;
    font-size: 1.5rem;
    font-weight: bold;
    color: #ffffff;
  }

  @keyframes scroll {
    from { transform: translateX(0); }
    to   { transform: translateX(-100%); }
  }
</style>
</head>
<body>
<div class='marquee'>
  <span>" & titulo & "</span>
  <span>" & titulo & "</span>
</div>

</body>
</html>
"

```