<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css" type="text/css">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Pizza Prime</title>
</head>
<body>
  <style>
    *{
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}
footer{
  background-color: #363636;
  color: #fff;
  padding: 20px;
  text-align: center;
  margin-top: 50px;
  font-size: 20px;
}
#copy{
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
  
}
header{
  font-family: Arial, Helvetica, sans-serif
  text-align: center;
  background-color: brown;
  padding:20px;
  margin-top:0%;
}
.menu{
  font-family: Arial, Helvetica, sans-serif;
  text-align:center;
  background-color: brown;
  margin-top:0%;
  padding: 21px;
  color: #fff
}
#contatos{
  background-color: brown;
  color: #fff;
  padding: 20px;
  text-align: start;
  margin-top: 50px;
  font-size: 20px;
}
#card{
font-size: 9px;
}
#sobre{
  background-color: brown;  
  color: #fff;
  padding: 20px;
  text-align: start;
  margin-top: 50px;
  font-size: 20px;
}

  </style>
  <header>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Pizza Prime</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Início</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" aria-curtent="page" href="#">Nossas Pizzas</a>
        </li>
        <li class="nav-item">
          <a class="nav-link acrive" aria-current="page" href="#">Sobre nós</a>
        </li>
        <li class="nav-item">
          <a class="nav-link acrive" aria-current="page" href="#">Contatos</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </header>
  
  <div class="menu">
    <h1>Pizza Prime</h1>
    <p>A melhor da região</p>
  </div>
  
  <br>
  
  <section>
    
    <h1 class="text-center" id="pizzas">Nossas Pizzas</h1>
    <br>
    <div class="row">
      <div class="col-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRAbaBsDKIz2MCgjBguhnA6JfTDGuL-M2y6eQ&usqp=CAU" alt="Pizza 3" class="card-img">
        <div class="card" id="card">
          <h5>Pizza</h5>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec justo eget arcu iaculis mattis vulputate aliquam ex.</p>
        </div>
      </div>
      <div class="col-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVoiPDaeQ_JZZAWxahIHLlyXxU1B6irRXGkw&usqp=CAU" alt="Pizza 2" class="card-img">
        <div class="card" id="card">
          <h5>Pizza</h5>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec justo eget arcu iaculis mattis vulputate aliquam ex.</p>
         </div>
      </div>
      <div class="col-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTuA_dHdISVOL8nlNBT3PutZDnGQDoqcNJkkA&usqp=CAU" alt="Pizza 3" class="card-img">
        <div class="card" id="card">
          <h5>Pizza</h5>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec justo eget arcu iaculis mattis vulputate aliquam ex.</p>
        </div>
      </div>
      <div class="col-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQusAsjcCIfxLhvg0BsdOcxLJLPQmHuLAUdUA&usqp=CAU" alt="Pizza 2" class="card-img">
        <div class="card" id="card">
          <h5>Pizza</h5>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec justo eget arcu iaculis mattis vulputate aliquam ex.</p>
         </div>
      </div>
      <div class="col-4">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSW1619b-iIvsbSZesO6lmLLZUwIoriH2pB3g&usqp=CAU" alt="Pizza 3" class="card-img">
          <div class="card" id="card">
            <h5>Pizza</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec justo eget arcu iaculis mattis vulputate aliquam ex.</p>
          </div>
        </div>
        <div class="col-4">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRcbIUTn_EpqiBzAhLOdNHyaa8WR5B05grCpzQkJGjOdPmpIePUKwf2ll0&s=10" alt="Pizza 2" class="card-img">
          <div class="card" id="card">
            <h5>Pizza</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas nec justo eget arcu iaculis mattis vulputate aliquam ex.</p>
          </div>
        </div>
    </div>
    <br>
    
  <section>
    
    <h1 class="text-center">Tabela de valores</h1>
    <br>
<table class="table table-bordered border-secondary">
  <tr>
    <th>Sabor</th>
    <th>Valor</th>
  </tr>
  <tr>
    <td>Peperoni</td>
    <td>29,99 R$</td>
  </tr>
  <tr>
    <td>Mussarela</td>
    <td>29,99 R$</td>
  </tr>
  
<br>

  </section>
  
  <section id="sobre">
    <h1 class="text-center">Sobre nós</h1>
    <p>Bem-vindo à Pizza Prime, onde qualidade é a essência. Nossas pizzas são obras-primas culinárias, preparadas com ingredientes frescos e variedade de sabores. Oferecemos um ambiente acolhedor e atendimento caloroso. Além de pizzas incríveis, temos acompanhamentos, saladas e sobremesas deliciosas. Acompanhe com nossa seleção de vinhos e bebidas refrescantes. Na Pizza Prime, a qualidade é tradição. Venha nos visitar e experimente uma experiência gastronômica única.</p>
    <br>
  </section>
  
  <br>

<section>
  <div id="contatos">
    <h1 class="text-center">Contatos</h1>
    <br>
    <h4 id="email">E-Email</h4>
    <p>pizzaprime@gmail.com</p>
    <hr>
    <h4 id="telefone">Telefones</h4>
    <p>+55 (99) 9 9999-9999</p>
    <p>+55 (88) 8 8888-8888</p>
    <hr>
    <h4 id="endereco">Endereço</h4>
    <p>Rua Pizza, N°314</p>
    <hr>
  </div>
</section>

  
  <footer>
    <p id="copy">&copy; 2023 | Reynan Lima</p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>
  
</body>
</html>

*{
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}
footer{
  background-color: #363636;
  color: #fff;
  padding: 20px;
  text-align: center;
  margin-top: 50px;
  font-size: 20px;
}
#copy{
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
  
}
header{
  font-family: Arial, Helvetica, sans-serif
  text-align: center;
  background-color: brown;
  padding:20px;
  margin-top:0%;
}
.menu{
  font-family: Arial, Helvetica, sans-serif;
  text-align:center;
  background-color: brown;
  margin-top:0%;
  padding: 21px;
  color: #fff
}
#contatos{
  background-color: brown;
  color: #fff;
  padding: 20px;
  text-align: start;
  margin-top: 50px;
  font-size: 20px;
}
#card{
font-size: 9px;
}
#sobre{
  background-color: brown;  
  color: #fff;
  padding: 20px;
  text-align: start;
  margin-top: 50px;
  font-size: 20px;
}
