# Hello Everyone 👋

## 👨🏻‍💻 &nbsp;About Me
My name is **Catur Angga Adiyaksa**. I'm an *Undergraduate Student* at BIU Bina Insani Uneversity. I am a founder  *CAA* and Leader at [CAA](https://caa.web.id).

I am a hard worker and can create simple websites. During more than a year of learning programming, I managed to create several websites and understand the programming languages such as Java, JavaScript, and Python. As an informatics engineering student, I am committed to learning and developing skills in software engineering, and web development.

Want to know more, please visit my [personal website](https://caturanggaadiyaksa.my.id/).





- <a href="https://www.instagram.com/angga_adiyaksa.id/"><img src="https://img.shields.io/badge/instagram%20@angga_adiyaksa.id-DD2476?style=for-the-badge&logo=instagram&logoColor=white"/></a>
- <a href="https://www.instagram.com/angga_adiyaksa.id/"><img src="https://img.shields.io/badge/facebook%20@caturanggaadiyaksa-344E86?style=for-the-badge&logo=facebook&logoColor=white"/></a>
- <a href="https://www.instagram.com/angga_adiyaksa.id/"><img src="https://img.shields.io/badge/twitter%20@caturangga-0D95E8?style=for-the-badge&logo=twitter&logoColor=white"/></a>
- <a href="https://caa.web.id/"><img height="30px" src="https://img.shields.io/badge/My%20Website:%20caa.web.id-8E2DE2?style=for-the-badge&logo=google%20chrome&logoColor=white"/></a>

<img align="center" src="https://github.com/saviomartin/saviomartin/blob/master/assets/skills.png?raw=true">

![HTML5](https://img.shields.io/badge/html%205-grey?style=for-the-badge&logo=html5&logoColor=white&labelColor=8E2DE2)
![CSS3](https://img.shields.io/badge/css%203-grey?style=for-the-badge&logo=css3&logoColor=white&labelColor=8E2DE2)
![Sass](https://img.shields.io/badge/sass-grey?style=for-the-badge&logo=sass&logoColor=white&labelColor=8E2DE2)
![JavaScript](https://img.shields.io/badge/-JavaScript-grey?style=for-the-badge&logo=javascript&logoColor=white&labelColor=8E2DE2)
<br>
![bootstrap](https://img.shields.io/badge/-bootstrap-grey?style=for-the-badge&logo=bootstrap&logoColor=white&labelColor=8E2DE2)
![materializecss](https://img.shields.io/badge/Materialize%20css-grey?style=for-the-badge&logo=google&logoColor=white&labelColor=8E2DE2)
![node](https://img.shields.io/badge/-node-grey?style=for-the-badge&logo=node.js&logoColor=white&labelColor=8E2DE2)
![php](https://img.shields.io/badge/-php-grey?style=for-the-badge&logo=php&logoColor=white&labelColor=8E2DE2)
<br>
![mongodb](https://img.shields.io/badge/-mongodb-grey?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=8E2DE2)
![firebase](https://img.shields.io/badge/-firebase-grey?style=for-the-badge&logo=firebase&logoColor=white&labelColor=8E2DE2)
![git](https://img.shields.io/badge/-git-grey?style=for-the-badge&logo=git&logoColor=white&labelColor=8E2DE2)
![github](https://img.shields.io/badge/-github-grey?style=for-the-badge&logo=github&logoColor=white&labelColor=8E2DE2)
<br>
![python](https://img.shields.io/badge/-python-grey?style=for-the-badge&logo=python&logoColor=white&labelColor=8E2DE2)
![jquery](https://img.shields.io/badge/-jquery-grey?style=for-the-badge&logo=jquery&logoColor=white&labelColor=8E2DE2)
![MarkDown](https://img.shields.io/badge/-Markdown-grey?style=for-the-badge&logo=Markdown&logoColor=white&labelColor=8E2DE2)
![git](https://img.shields.io/badge/-git-grey?style=for-the-badge&logo=git&logoColor=white&labelColor=8E2DE2)




## ⚙️ &nbsp;GitHub Statistics
<p align="center">
<a href="https://github.com/caturanggadiyaksa">
  <img height="190em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=caturanggadiyaksa&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="190em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=caturanggadiyaksa&layout=compact&langs_count=8&theme=tokyonight"/>
  <img height="190em" src="https://github-readme-streak-stats.herokuapp.com/?user=caturanggadiyaksa&theme=tokyonight">
</a>
</p>

## ❤ &nbsp;Views and Followers
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=caturanggadiyaksa&label=Profile%20views&color=0e75b6&style=flat" alt="caturanggadiyaksa" />
  <a href="https://github.com/caturanggadiyaksa?tab=followers">
    <img src="https://img.shields.io/github/followers/caturanggadiyaksa?label=Followers&style=social" alt="GitHub Badge">
  </a>
</p>



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>map jakarta</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link
      href="https://fonts.googleapis.com/css?family=Open+Sans"
      rel="stylesheet"
    />
    <script src="https://api.tiles.mapbox.com/mapbox-gl-js/v2.9.2/mapbox-gl.js"></script>
    <link
      href="https://api.tiles.mapbox.com/mapbox-gl-js/v2.9.2/mapbox-gl.css"
      rel="stylesheet"
    />
    <style>
      body {
        margin: 0;
        padding: 0;
      }
      #map {
        position: absolute;
        top: 0;
        bottom: 0;
        width: 100%;
      }
      .marker {
        background-image: url('mapbox-icon.png');
        background-size: cover;
        width: 50px;
        height: 50px;
        border-radius: 50%;
        cursor: pointer;
      }
      .mapboxgl-popup {
        max-width: 200px;
      }
      .mapboxgl-popup-content {
        text-align: center;
        font-family: 'Open Sans', sans-serif;
      }
    </style>
  </head>
  <body>
    <div id="map"></div>
  
    <script>
      mapboxgl.accessToken = 'pk.eyJ1IjoiY2F0dXJhbmdnYSIsImEiOiJjbDR5N3JrZW0wMzJhM2JxdmFyaWdtb3AxIn0.jBPID5RxfBeVaR0bC-vTuQ';
      const defaultLocation = [106.82756851648378, -6.175543308496231]


      var map = new mapboxgl.Map({
                container: 'map',
                center: defaultLocation,
                zoom: 11.15,
                //style: 'mapbox://styles/mapbox/streets-v11'

                });
                const style = "dark-v10"
                //light-v10, outdoors-v11, satellite-v9, streets-v11, dark-v10
                map.setStyle(`mapbox://styles/mapbox/${style}`)
                map.addControl(new mapboxgl.NavigationControl())
      
      
      
                /*const geojson = {
        'type': 'FeatureCollection',
        'features': [
          {
            'type': 'Feature',
            'geometry': {
              'type': 'Point',
              'coordinates': [-77.032, 38.913]
            },
            'properties': {
              'title': 'Mapbox',
              'description': 'Washington, D.C.'
            }
          },
          {
            'type': 'Feature',
            'geometry': {
              'type': 'Point',
              'coordinates': [-122.414, 37.776]
            },
            'properties': {
              'title': 'Mapbox',
              'description': 'San Francisco, California'
            }
          }
        ]
      };
      */

     /* const map = new mapboxgl.Map({
        container: 'map',
        style: 'mapbox://styles/mapbox/light-v10',
        //center: [-96, 37.8],
        zoom: 3
        
      });*/

      // add markers to map
      for (const feature of geojson.features) {
        // create a HTML element for each feature
        const el = document.createElement('div');
        el.className = 'marker';

        // make a marker for each feature and add it to the map
        new mapboxgl.Marker(el)
          .setLngLat(feature.geometry.coordinates)
          .setPopup(
            new mapboxgl.Popup({ offset: 25 }) // add popups
              .setHTML(
                `<h3>${feature.properties.title}</h3><p>${feature.properties.description}</p>`
              )
          )
          .addTo(map);
      }
    </script>
  </body>
</html>

