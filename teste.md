.hidden-link {
  text-decoration: none;
  display: block;
  width: 100%;
  height: 100%;
}

.hidden-link img {
  display: block;
}

.hidden-link:hover img {
  opacity: 0.5; /* Define a opacidade da imagem quando o mouse está sobre ela */
}

.hidden-link:hover::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
<!DOCTYPE html>
<html>
<head>
<style>
.hidden-link {
  text-decoration: none;
  display: block;
  width: 100%;
  height: 100%;
}

.hidden-link img {
  display: block;
}

.hidden-link:hover img {
  opacity: 0.5; /* Define a opacidade da imagem quando o mouse está sobre ela */
}

.hidden-link:hover::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
</head>
<body>
<div style="max-width:100%; padding:0px;">
<h1>⁝1º Semestre</h1>
<h2>Introdução a Redes, Hardware, Virtualização e Programação</h2>
<table>
<tr>
<td align="center">
<h2>Virtualização</h2>
<a href="https://www.virtualbox.org" class="hidden-link">
<img align="center" alt="Virtual Box" height="70" width="70" src="https://www.vectorlogo.zone/logos/virtualbox/virtualbox-icon.svg" />
</a>
<a href="https://www.vmware.com" class="hidden-link">
<img align="center" alt="VMWare" height="70" width="130" src="https://vectorwiki.com/images/WP5h6__vmware.svg
