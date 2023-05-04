# CHILE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>chile</title>
    <link rel="stylesheet" href="assest/css/style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
    crossorigin="anonymous">

    <script src="https://kit.fontawesome.com/9b4f22cdd1.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js"
    integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s"
    crossorigin="anonymous"></script>
</head>

<body> 
  <!--aqui inicia mi prueba 2-->
  <!--aqui va el navbar-->
  <header>
  <nav class="navbar navbar-expand-lg">
    <div class="container px-2 py-3">
        <a class="navbar-brand text-white" href="#">
            <img src="assest/img/icono.png" alt="icono viajes">
        </a>
    <button class="navbar-toggler navbar-dark border-light" type="button" data-bs-toggle="collapse" data-bs-target="#">
     <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav m-auto">
            <li class="nav-item">
                <a class="nav-link text-white active" aria-current="page" href="#"> Inicio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white" href="#" >Quienes somos</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white" href="#" >Destacados</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white" href="#" >Contactos</a>
            </li>
        </ul>
    </div>
    </div>
  </nav>
</header>

<!--aquí va el carousel-->
<section>
<div id="carouselintro" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="assest/img/carousel2.jpg" class="d-block w-100">
    </div>
    <div class="carousel-item">
      <img src="assest/img/carousel3.jpg" class="d-block w-100">
    </div>
    <div class="carousel-item">
      <img src="assest/img/card4.jpg" class="d-block w-1000">
    </div>
  </div>
  <button class="carousel-control-prev"type="button" data-bs-target="#carouselintro"data-bs-slide="Previous">
    <span class="carousel-control-prev-icon"></span>
  
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselintro" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
</section>

<!--aqui va la grilla ¿quienes somos?-->
<section>
  <h1> ¿Quiénes somos?</h1> 

<div class="card-group">
    <div class="card">
    <img class="card-header"img src="assest/img/plane-graphic-clipart-design-free-png.webp" 
    class="card-img-top" alt="icono avión">
    
    <div class="card-body">
      <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Incidunt modi sunt consequatur doloribus voluptatum obcaecati, nihil sapiente, ad velit impedit ratione, officia odit. Ipsum iste minima pariatur ut ipsam modi.</p>
    </div>
  </div>

  <div class="card">
    <img class="card-header" img src="assest/img/illustration-of-mountains-png.webp"
     class="card-img-top" alt="icono de montaña">

    <div class="card-body">
      <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, incidunt sapiente itaque dolor aperiam aspernatur doloremque quod! Debitis earum autem dolorum accusamus assumenda. Similique saepe repellat pariatur facilis, repellendus reiciendis.</p>
    </div>
  </div>

  <div class="card">
    <img class="card-header"img src="assest/img/icono.png" class="card-img-top">
    <div class="card-body">
      <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laboriosam cum cumque harum, esse autem optio temporibus corporis facere saepe quos corrupti voluptatem rem blanditiis non ipsum neque iste deleniti architecto.</p>
    </div>
  </div>
</div>
</section>



<!--aqui va la grilla destacados-->
<section>  
  <h2>Destacados</h2>
  <div class="row row-cols-1 row-cols-sm-4 g-4">
    <div class="col">
      <div class="card">
        <img src="assest/img/Laguna_Santa_Rosa,_III_Región,_Chile.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Laguna santa Rosa en Antofagasta</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card">
        <img src="assest/img/card4.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Jardín Botánico en Valdivia</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card">
        <img src="assest/img/card1.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Lago Pehoé en Torres del Paine</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card">
        <img src="assest/img/card3.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Laguna Mistanki en San Pedro de Atacama</h5>
          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!--aqui va formulario-->
<section>
  <h3> Contacto</h3>
<div class="mb-3">
    <label for="exampleFormControlInput1" class="form-label">Nombre</label>
    <input type="name" class="form-control" id="exampleFormControlInput1" placeholder="Nombre">
  </div>
  <div class="mb-3">
    <label for="exampleFormControlInput1" class="form-label">asunto</label>
    <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="asunto">
  </div> 
  <div class="mb-3">
    <label for="exampleFormControlTextarea1" class="form-label">mensaje</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
    <a href="#" class="btn btn-primary">Enviar</a>
  </div>
</section>

<!--aqui va rrss-->
<footer>
  <div class="container-fluid redes sociales">
    <div class="row">
      <div class="row-cols-sm-3 py-4 px3">
      </div>
      <i class="fa-brands fa-square-facebook fa-3x px-3"></i>
      <i class="fa-brands fa-instagram fa-3x px-3"></i>
      <i class="fa-brands fa-linkedin-in fa-3x px-3"></i>
      <i class="fa-brands fa-twitter fa-3x px-3"></i>
    </div>
  </div>
</footer>


<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js"
integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s"
crossorigin="anonymous"></script>


</body>
</html>
