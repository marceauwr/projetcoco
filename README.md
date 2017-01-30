# projetcoco

<!DOCTYPE html>
<html lang="fr" class="no-js">
  <head>
    <meta charset="utf-8" />
  <meta http-equiv="x-ua-compatible" content="ie=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="styles/foundation.min.css" />
    <link rel="stylesheet" href="styles/slick.css" />
    <link rel="stylesheet" href="styles/slick-theme.css" />
    <link rel="stylesheet" href="styles/style.css" />
  </head>
  <body>
    <header>
      <nav class="row">
        <ul class="menu">
          <li class="columns medium-3"><a href="#" title="Page d'accueil"><img src="" alt="Logo Vaïvai"></a></li>
          <li class="columns medium-3"><a href="#">événement</a></li>
          <li class="columns medium-3"><a href="#">produit</a></li>
          <li class="columns medium-3"><a href="#">histoire</a></li>
        </ul>
    </header>
    <main>
      <div class="carouselProduits row">
        <div class="carouselProduits-slide">
          <a href="#" title="vaivai_huile-coco-desodorisee_200ml_2016_produit"></a><img src="https://www.vaivai.fr/resources/files/2016/09/vaivai_huile-coco-desodorisee_200ml_2016_produit-350x220.png" alt="vaivai_huile-coco-desodorisee_200ml_2016_produit" />
          <p>
            VAIVAI
          </p>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="Vaivai, eau de coco fraicheur - 1l"><img src="https://www.vaivai.fr/resources/files/2016/08/Vaivai_Eau-de-coco_fraicheur_1L-350x220.png" alt="Vaivai, eau de coco fraicheur - 1l" /></a>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="vaivai_coco_creation_mangue-1L_2016_produit"><img src="https://www.vaivai.fr/resources/files/2016/08/vaivai_coco_creation_mangue-1L_2016_produit-350x220.png" alt="vaivai_coco_creation_mangue-1L_2016_produit" /></a>
        </div>
        <div class="carouselProduits-slide">
         <a href="#" title="vaivai_coco_creation_citron-menthe-1L_2016_produit"><img   src="https://www.vaivai.fr/resources/files/2016/08/vaivai_coco_creation_citron-menthe-1L_2016_produit-350x220.png" alt="vaivai_coco_creation_citron-menthe-1L_2016_produit" /></a>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="vaivai_coco_creation_fraise-1L_2016_produit"><img src="https://www.vaivai.fr/resources/files/2016/08/vaivai_coco_creation_fraise-1L_2016_produit-350x220.png" alt="vaivai_coco_creation_fraise-1L_2016_produit" /></a>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="vaivai_Coco_fruit_EDC-Passion-1L_2016_produit"><img src="https://www.vaivai.fr/resources/files/2016/08/vaivai_Coco_fruit_EDC-Passion-1L_2016_produit-350x220.png" alt="vaivai_Coco_fruit_EDC-Passion-1L_2016_produit" /></a>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="vaivai_huile-coco-nature_200ml_2016_produit"><img src="https://www.vaivai.fr/resources/files/2016/08/vaivai_huile-coco-nature_200ml_2016_produit-350x220.png" alt="vaivai_huile-coco-nature_200ml_2016_produit" /></a>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="vaivai_EDC-1L_2016_produit"><img src="https://www.vaivai.fr/resources/files/2016/07/vaivai_EDC-1L_2016_produit-350x220.png" alt="vaivai_EDC-1L_2016_produit" /></a>
        </div>
        <div class="carouselProduits-slide">
          <a href="#" title="carouselProduits-slide"><img src="https://www.vaivai.fr/resources/files/2016/07/vaivai_petales-coco-nature_2016_produit-350x220.png" alt="vaivai_petales-coco-nature_2016_produit" class="carouselProduits-slide" /></a>
        </div>
      </div>
    </main>
    <script src="scripts/vendor/jquery.js"></script>
    <script src="scripts/vendor/what-input.js"></script>
    <script src="scripts/vendor/foundation.min.js"></script>
    <script src="scripts/vendor/slick.min.js"></script>
    <script>
      $(document).foundation();

      $(document).ready(function(){
        $('.carouselProduits').slick({
          autoplay: true,
          dots : true,
          autoplaySpeed: 2000,
          centerMode: true,
          centerPadding: '40px',
          slidesToShow: 3,
          responsive: [
            {
              breakpoint: 768,
              settings: {
                arrows: false,
                centerMode: true,
                centerPadding: '40px',
                slidesToShow: 3
              }
            },
            {
              breakpoint: 480,
              settings: {
                arrows: false,
                centerMode: true,
                centerPadding: '40px',
                slidesToShow: 1
              }
            }
          ]
        });
      });
    </script>
  </body>  
</html>
