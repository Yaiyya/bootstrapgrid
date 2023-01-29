# bootstrapgrid
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistema grid de Bootstrap</title>
    <link rel="stylesheet" href="../11-bootstrap-grid/ejerciciobootstrap-grid.css">
    <link  href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
    crossorigin="anonymous"
    />
</head>
<body>
    <div class="contenedor">
        <div class="row">
        <div class="sm">Mueve el querer sus alas con gran fuerza tras el loor de aquella que yo canto. Al comenzar, levántase un espanto tal que es peor del seso si se esfuerza</div>
    </div>
        <div class="row">
        <div class="md">Mueve el querer sus alas con gran fuerza tras el loor de aquella que yo canto. Al comenzar, levántase un espanto tal que es peor del seso si se esfuerza</div>
        <div class="row">
        <div class="lg">Mueve el querer sus alas con gran fuerza tras el loor de aquella que yo canto. Al comenzar, levántase un espanto tal que es peor del seso si se esfuerza</div>
    </div>
        <div class="row">
        <div class="xl">Mueve el querer sus alas con gran fuerza tras el loor de aquella que yo canto. Al comenzar, levántase un espanto tal que es peor del seso si se esfuerza</div>
    </div>
</body>
<script
src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
crossorigin="anonymous"
></script>
</html>


.row div{
    margin:0.25rem;
}


.sm {
    background-color: cyan;
    border: 2rem;
}
.md:hover{
    background-color: red;
    transition: all 4sg;
}
.lg{
    background-color: yellow;
    padding: 15px;
    font-family: Arial;
    width: 300px;
    

}
.xl{
    background-color: green;
    padding: 20%;
    margin: 4px;
    display: flex;
    justify-content: center;
    align-items: center;

}

