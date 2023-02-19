<!DOCTYPE html>
<html>
<head>
<title>Alygnt - Home</title>
<link rel="icon" type="image/x-icon" href="https://Alygnt.github.io/logo/favicon.ico">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://Alygnt.github.io/index.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Raleway", sans-serif}
</style>
</head>

<!-- add in head: --> <script src="https://Alygnt.github.io/nav/jquery-1.10.2.js"></script>
<!--Navigation bar-->
<div id="nav-placeholder">

</div>

<script>
$(function(){
  $("#nav-placeholder").load("https://Alygnt.github.io/nav/nav.html");
});
</script>
<!--end of Navigation bar-->

<body class="w3-light-grey">
<!-- w3-content defines a container for fixed size centered content,
and is wrapped around the whole page content, except for the footer in this example -->
<div class="w3-content" style="max-width:1400px">

<!-- Header spacing-->
<header class="w3-container w3-center w3-padding-32">
  <h1><b> </b></h1>
</header>
<header class="w3-container w3-center w3-padding-32">
  <h5><b> </b></h5>
</header>
<!--END Header spacing-->

<!-- Alygnt circle logo -->
<p align="center">
<a href="#" ><img align="center" src="https://raw.githubusercontent.com/Alygnt/Alygnt.github.io/main/logo/Alygnt_logo_circle.png" width="150"></a>
</p>
<!-- END Alygnt circle logo  -->

<!-- Alygnt text logo -->
<p align="center">
<a href="#" ><img align="centre" src="https://raw.githubusercontent.com/Alygnt/Alygnt.github.io/main/logo/Alygnt_text_transbg.png"  width="100"></a>
</p>
<!-- END Alygnt text logo -->

<!-- logo comment -->
<header class="w3-container w3-center">
<p>Welcome to the world of <span class="w3-tag">Neeraj</span></p>
</header>
<!-- END logo comment -->

<!-- Header Text transition-->
<header class="w3-container w3-center w3-padding-32">
<div class="container-md" role="main">
  <div class="row">
    <div class="col-xl-8 offset-xl-2 col-lg-10 offset-lg-1">

<!-- Typed.js -->
<script src="https://Alygnt.github.io/TypeTransition/jquery-1.11.2.min.js"></script> <!-- Typed.js uses old jquery ver -->
<script src="https://Alygnt.github.io/TypeTransition/typed.js" type="text/javascript"></script>
<script>
  $(function(){
    $(".typed").typed({
      strings: ["write about Technology.","try to develop Technology.","create awesome Tools.","create scary tools.","kill bugs.","Exploit others."],
      typeSpeed: 100,
      loop: true,
      backDelay: 1000

    });
  });
</script>

<div class="mobile-js-hide">
  <div class="row">
    <div class="col-sm-12">
      <div class="text-center">
          <h1>I <span class="typed" style="color:#890000";></span></h1>
      </div>
    </div>
  </div>
</div>
</header>

<!-- END w3-content -->
</div>

</body>

<!--Footer-->
<div id="footer-placeholder">

</div>

<script>
$(function(){
  $("#footer-placeholder").load("https://Alygnt.github.io/footer/footer.html");
});
</script>
<!--end of Footer-->

</html>
