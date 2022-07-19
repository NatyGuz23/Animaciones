# Animaciones

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animaciones</title>
    <link rel="stylesheet" href="css/animaciones.css">
</head>
<body>
    <div>
    <I><h1>Natalia</h1></I>
    </div>
    <p>
        <I>  Natalita, está linda la mar,
            y el viento
            lleva esencia sutil de azahar;
            yo siento
            en el alma una alondra cantar;
            tu acento.
           Natalita, te voy a contar
            un cuento.</I>
    </p>
</body>
</html>

CSS

@keyframes animacion-cuadrado {
    /*from{
        background-color: red;
    }

    to {
        background-color: blue;
    }*/

    0% {
        top: 0;
        left: 0;
        background-color: red;
    }

    25% {
        top: 0;
        left: calc(100% - 100px);
        background-color: green;
    }

    50% {
        top: 50vh;
        left: calc(100% - 100px);
        background-color: blue;
        border-radius: 50%;
    }

    75% {
        top: 50vh;
        left: 0;
        background-color: violet;
        border: 2px solid red;
    }

    100% {
        top: 0;
        left: 0;
        background-color: red;
    }

}

div {
    position: relative;
    width: 100px;
    height: 100px;
    background-color: darkorange;
    animation-name:animacion-cuadrado ;
    animation-duration: 5s;
    color: black;
    box-shadow: 1px 2px 100px black;
    animation-delay: 1s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-direction: alternate;
}
div h1 {
    color: white;
}
p b {
    color: blueviolet;
}
p {
    color: darkorange;
}
