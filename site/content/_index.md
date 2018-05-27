---
image: /img/header.jpg
title: Fiesta Balonowa
subtitle: Podniebne widowisko
contents:
  - background_color: has-background-warning has-text-dark
    left_column: '**LEWA KOLUMNA**'
    right_column: '# _PRAWA KOLUMNA_'
  - background_color: is-info
    left_column: LEWA KOLUMNA
    right_column: >-
      <div id="map" style="height: 400px; width: 100%;"></div>


      \    <script>


      \    function initMap() {


      \    var wachock = { lat: 51.073593, lng: 21.012333 };


      \    var map = new google.maps.Map(document.getElementById('map'), {


      \    zoom: 10,


      \    center: wachock


      \    });


      \    var marker = new google.maps.Marker({


      \    position: wachock,


      \    map: map


      \    });


      \    }


      \    </script>


      \    <script async defer
      src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDg5-xaX2hVK_qPu2OIxwgzNZBt4tTpVk4&callback=initMap">


      \    </script>
    section-title: Tytuł sekcji
  - background_color: has-background-success has-text-white
    left_column: LEWA KOLUMNA
    section-title: Tytuł 2
---

