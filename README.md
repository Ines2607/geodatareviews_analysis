# geodatareviews_analysis
 Этот проект анализирует новый открытый датасет с отзывами от Яндекс Карт (доступен тут: https://github.com/yandex/geo-reviews-dataset-2023#geo-reviews-dataset-2023). Зачем он нужен:
  - дает первое представление о его возможностях и ограничениях
  - формирует более "чистый" датасет с исходными данными - датасет больше 25 MB, поэтому необходимо запустить код в ноутбуке. 
  - формирует geojson с выборкой на 2400 адресов - "georeviews_wth_geometry.geojson"
  - формирует датасет с частотой рубрик по регионам - "most_popular_pois_by_region.csv"
  - показывает возможность преобразования адресов в координаты в Python
