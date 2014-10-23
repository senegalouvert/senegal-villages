senegal-villages
================

Les villages du senegal , leur nom, les regions d'appartenance , les cordonnes geographiques , et autres informations utiles


install
============

	cd scripts/lib
      npm install
      cd ../..
      //Note that your csv file has fields latitude and longitude
      node scripts/lib/csv2geojson data/villages.csv > data/villages.geojson
