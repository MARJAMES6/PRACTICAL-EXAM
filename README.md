<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">





</head>
<style> 

body {
    
    background-color: black;
    margin: -2%;
    
}

#car-vh {
    
    height: 80vh;
    object-fit: fill;
    
}

#prod-center {
    
   background-color: red; 
   margin: auto;
    
}

#prod {
    
   background-color: white; 
   margin: auto;
   margin-top: 5%;
    
}






@media screen and (min-width: 772px) {
    
    #car-vh {
    
    height: 100vh;
    object-fit: fill;

    
    
}

}




@media screen and (max-width: 482px) {
    
    
    body {
    
    background-color: black;
    margin: -4%;
    
}
    
    #car-vh {
    
    height: 50vh;
    object-fit: fill;

    
    
}


}


</style> 
<body>
<div class = "container-fluid">





<nav class="navbar fixed-top navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">STARCARO </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="#">Home</a>
        <a class="nav-link active" href="#">Features</a>
        <a class="nav-link active" href="#">Pricing</a>
      </div>
    </div>
  </div>
</nav>





<div class = "row">
<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner" >
    <div class="carousel-item active">
      <img src="https://scontent.fmnl8-3.fna.fbcdn.net/v/t39.30808-6/463876185_552319621080835_504671444662346797_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=127cfc&_nc_eui2=AeFjTD0JoxzlMU6D8xh6VoGwimm5ogs4gHmKabmiCziAefJlwrqwL1-8LR15IF-u_xxJSXBahYhBas1Kb2IqGmog&_nc_ohc=EgRtX8f9ZmUQ7kNvgGk3XT4&_nc_zt=23&_nc_ht=scontent.fmnl8-3.fna&_nc_gid=AoJS94Df9jld9qHrsT-9WcA&oh=00_AYA3vPAb6STq8Z1qgyOl_SKMxuP42cucMSsp6PJCn5ZjgA&oe=6776D12D" class="d-block w-100" id = "car-vh">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://scontent.fmnl8-3.fna.fbcdn.net/v/t39.30808-6/463859993_552313061081491_6706458990546008549_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=127cfc&_nc_eui2=AeEIV2eICJsPfxVbtkBmVXZkap_qbnkHLPFqn-pueQcs8RoueHRfbOMgHtMI-qtNPPKs21HLHApfwXRiOA-V_YQN&_nc_ohc=S1GZLP3IDngQ7kNvgHglAr2&_nc_zt=23&_nc_ht=scontent.fmnl8-3.fna&_nc_gid=AQanoXN3n5Dncd9oKXdQION&oh=00_AYAWQMeIPHmxorpOYJ-7vWi_bpyEqYIyIKFTPl7rs_JC_Q&oe=6776C44E" class="d-block w-100" id = "car-vh">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Some representative placeholder content for the second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://scontent.fmnl8-1.fna.fbcdn.net/v/t39.30808-6/463891756_552313157748148_8335296357383299645_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=127cfc&_nc_eui2=AeGNTDZ8x5xTURFk2qm1y1vXOFjycX1pOY84WPJxfWk5jwvnSuY0hbjdFB7ovTGI8Yt1wXDnhx80_yrijr6QQfXD&_nc_ohc=1Fjs8LTbANsQ7kNvgG1HIJ-&_nc_zt=23&_nc_ht=scontent.fmnl8-1.fna&_nc_gid=A9XjF0vjvu2qp8v111q_2o3&oh=00_AYDva2RyJKBpnoVfKGPBs6c_JkaJFQw30gPltXrsz3vIdA&oe=6776B4C8" class="d-block w-100" id = "car-vh">
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>




<div class = "row" id = "prod-center">
    
    
    
<div class="card" style="width: 18rem;" id = "prod">
  <img src="https://th.bing.com/th/id/OIP.wcsbyeq3bRnCZrmLR4rhogHaEK?rs=1&pid=ImgDetMain" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">CARAJILLO</h5>
    <p class="card-text">A simple cocktail made from espresso and Licor 43.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>








</div>





<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>