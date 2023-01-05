<div class='sidebar'>
  <div class='heading'>
    <h1>Find our Beers</h1>
  </div>
  <div id='listings' class='listings'></div>
</div>
<div id="map" class="map"></div>

<script>
  mapboxgl.accessToken = 'pk.eyJ1IjoicGFsYWZpbmEiLCJhIjoiY2w0YTduMndpMTk2bzNqb3J6b2drbjZydyJ9.SQyZ4b4VKcVFQPMcTz0Vug';

  const map = new mapboxgl.Map({
    container: 'map',
    style: 'mapbox://styles/mapbox/light-v10',
    center: [-80.367, 25.798],
    zoom: 13,
    scrollZoom: false
});

const stores = {
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          -80.366726,
          25.798836

        ]
      },
      "properties": {
        "phoneFormatted": "(305) 646-1339",
        "phone": "3056461339",
        "address": "2685 NW 105th Ave",
        "city": "Doral",
        "country": "United States",
        "crossStreet": "at NW 27th St",
        "postalCode": "33172",
        "state": "FL",
        "text": "Tripping Animals Brewing Co.",
        "notice": "Call ahead to ensure they have what you are looking for."
      }
    },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.726396,
    28.243072 ]
   },
   "properties": {


     "address": "2250 Town Center Ave # 101",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32940",
     "state": "FL",
     "text": "28 North Gastropub",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },

    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.142996,
    26.057059 ]
   },
   "properties": {


     "address": "236 N Federal Highwayunit# 104",
     "city": "Dania Beach",
     "country": "United States",
     "postalCode": "33004",
     "state": "FL",
     "text": "3 Sons Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.631956,
    27.777052 ]
   },
   "properties": {


     "address": "400 Beach Dr Ne",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "400 Beach Seafood & Tap House",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.610212,
    28.325404 ]
   },
   "properties": {


     "address": "382 N Orlando Ave",
     "city": "Cocoa Beach",
     "country": "United States",
     "postalCode": "32931",
     "state": "FL",
     "text": "4Th Street Fillin Station",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.450479,
    28.010065 ]
   },
   "properties": {


     "address": "6809 N Nebraska Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "7Venth Sun Brewery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.460842,
    30.288229 ]
   },
   "properties": {


     "address": "13529 Beach Blvd#205B",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32224",
     "state": "FL",
     "text": "9 Zero Pour",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.541435,
    27.33821 ]
   },
   "properties": {


     "address": "1445 2Nd Streetunit 103/333",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34236",
     "state": "FL",
     "text": "99 Bottles",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.352609,
    25.746171 ]
   },
   "properties": {


     "address": "9700 Sw 24Th Street Suite D",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33165",
     "state": "FL",
     "text": "A Mari Mix",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.360108,
    28.513893 ]
   },
   "properties": {


     "address": "2610 S Fern Creek Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Aardvark Beverages Inc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.65414,
    30.310598 ]
   },
   "properties": {


     "address": "1461 Hendricks Avenue",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32207",
     "state": "FL",
     "text": "Aardwolf Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.303239,
    29.028686 ]
   },
   "properties": {


     "address": "117 N Woodland Blvd",
     "city": "Deland",
     "country": "United States",
     "postalCode": "32720",
     "state": "FL",
     "text": "Abbey Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.140084,
    25.789072 ]
   },
   "properties": {


     "address": "1115- 1117 16 Street",
     "city": "Miami Beach",
     "country": "United States",
     "postalCode": "33139",
     "state": "FL",
     "text": "Abbey Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.698147,
    28.232131 ]
   },
   "properties": {


     "address": "55 Interlachen Rd",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32940",
     "state": "FL",
     "text": "Abc #017",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.492025,
    27.945084 ]
   },
   "properties": {


     "address": "3015 W Kennedy Blvd",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33601",
     "state": "FL",
     "text": "Abc #019",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.964043,
    29.012389 ]
   },
   "properties": {


     "address": "2360 Highway 44",
     "city": "New Smyrna Beacah",
     "country": "United States",
     "postalCode": "32168",
     "state": "FL",
     "text": "Abc #027",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.640113,
    28.824562 ]
   },
   "properties": {


     "address": "19065 Us Highway 441",
     "city": "Mt Dora",
     "country": "United States",
     "postalCode": "32757",
     "state": "FL",
     "text": "Abc #028",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.638448,
    27.804271 ]
   },
   "properties": {


     "address": "3535 4Th Street No",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "32859",
     "state": "FL",
     "text": "Abc #035",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.793309,
    27.8405 ]
   },
   "properties": {


     "address": "11153 Park Blvd",
     "city": "Seminole",
     "country": "United States",
     "postalCode": "33772",
     "state": "FL",
     "text": "Abc #038",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.971185,
    29.154311 ]
   },
   "properties": {


     "address": "3332 S Atlantic Ave",
     "city": "Daytona Beach",
     "country": "United States",
     "postalCode": "32118",
     "state": "FL",
     "text": "Abc #041",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.939522,
    27.965132 ]
   },
   "properties": {


     "address": "4319 S Fl Ave",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33813",
     "state": "FL",
     "text": "Abc #053",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.365645,
    28.60116 ]
   },
   "properties": {


     "address": "401 N Orlando Ave",
     "city": "Winter Park",
     "country": "United States",
     "postalCode": "32751",
     "state": "FL",
     "text": "Abc #071",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.164486,
    28.564843 ]
   },
   "properties": {


     "address": "14806 E Colonial Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32826",
     "state": "FL",
     "text": "Abc #080",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.23814,
    28.656981 ]
   },
   "properties": {


     "address": "801 Oviedo Mall Blvd",
     "city": "Oviedo",
     "country": "United States",
     "postalCode": "32765",
     "state": "FL",
     "text": "Abc #081",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.40815,
    27.77329 ]
   },
   "properties": {


     "address": "6178 N Us Hwy 441",
     "city": "Apollo Beach",
     "country": "United States",
     "postalCode": "33572",
     "state": "FL",
     "text": "Abc #086",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.613546,
    28.014449 ]
   },
   "properties": {


     "address": "11615 W Hillsborough Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33635",
     "state": "FL",
     "text": "Abc #094",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.505587,
    28.080674 ]
   },
   "properties": {


     "address": "14729 N Dale Mabry",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33618",
     "state": "FL",
     "text": "Abc #095",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.619173,
    28.18934 ]
   },
   "properties": {


     "address": "11868 State Road 54",
     "city": "Odessa",
     "country": "United States",
     "postalCode": "33556",
     "state": "FL",
     "text": "Abc #107",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.303272,
    29.00416 ]
   },
   "properties": {


     "address": "1400 S Woodland Blvd",
     "city": "Deland",
     "country": "United States",
     "postalCode": "32720",
     "state": "FL",
     "text": "Abc #131",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.49499,
    27.893303 ]
   },
   "properties": {


     "address": "3110 W Gandy Blvd",
     "city": "Tapma",
     "country": "United States",
     "postalCode": "33601",
     "state": "FL",
     "text": "Abc #132",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.420444,
    28.347472 ]
   },
   "properties": {


     "address": "3300 N John Young Pkwy",
     "city": "Kissimmee",
     "country": "United States",
     "postalCode": "34741",
     "state": "FL",
     "text": "Abc #134",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.348182,
    28.785709 ]
   },
   "properties": {


     "address": "980 Rinehart Rd",
     "city": "Lake Mary",
     "country": "United States",
     "postalCode": "32746",
     "state": "FL",
     "text": "Abc #137",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.354484,
    28.184038 ]
   },
   "properties": {


     "address": "1845 Bruce B Downs",
     "city": "Wesley Chapel",
     "country": "United States",
     "postalCode": "33544",
     "state": "FL",
     "text": "Abc #138",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.010725,
    29.123433 ]
   },
   "properties": {


     "address": "1198 Dunlawton Ave",
     "city": "Port Orange",
     "country": "United States",
     "postalCode": "32127",
     "state": "FL",
     "text": "Abc #142",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.37664,
    28.51161 ]
   },
   "properties": {


     "address": "2726 S Orange Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Abc #145",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.104056,
    26.258706 ]
   },
   "properties": {


     "address": "1350 Ne 23Rd Street",
     "city": "Pompano Beach",
     "country": "United States",
     "postalCode": "33062",
     "state": "FL",
     "text": "Abc #157",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.117367,
    26.933595 ]
   },
   "properties": {


     "address": "1260 Indiantown Road",
     "city": "Jupiter",
     "country": "United States",
     "postalCode": "33458",
     "state": "FL",
     "text": "Abc #162",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.20765,
    28.533533 ]
   },
   "properties": {


     "address": "750 S Alafaya Trl",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32828",
     "state": "FL",
     "text": "Abc #163",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.211301,
    29.555593 ]
   },
   "properties": {


     "address": "224 Palm Coast Pkwy Ne",
     "city": "Palm Coast",
     "country": "United States",
     "postalCode": "32137",
     "state": "FL",
     "text": "Abc #197",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.10076,
    26.80891 ]
   },
   "properties": {


     "address": "4155 Northlake Blvd",
     "city": "Palm Beach Gardens",
     "country": "United States",
     "postalCode": "33420",
     "state": "FL",
     "text": "Abc #201",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.229333,
    30.541458 ]
   },
   "properties": {


     "address": "5454 Thomasville Road",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32312",
     "state": "FL",
     "text": "Abc #215",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.227817,
    30.427172 ]
   },
   "properties": {


     "address": "3025 Apalachee Pkwy",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32301",
     "state": "FL",
     "text": "Abc #217",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.079196,
    26.704884 ]
   },
   "properties": {


     "address": "1027 N Florida Mango Rdsuite 4",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33409",
     "state": "FL",
     "text": "Accomplice Brewery & Ciderworks",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.140509,
    25.780278 ]
   },
   "properties": {


     "address": "955 Alton Road",
     "city": "Miami Beach",
     "country": "United States",
     "postalCode": "33139",
     "state": "FL",
     "text": "Airmail",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.346568,
    28.55198 ]
   },
   "properties": {


     "address": "609 Irvington Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Ala Cart",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.680585,
    30.314491 ]
   },
   "properties": {


     "address": "1035 Park Street",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32204",
     "state": "FL",
     "text": "Alewife",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.686159,
    28.306726 ]
   },
   "properties": {


     "address": "3188 Lake Washington Rd",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32936",
     "state": "FL",
     "text": "American Liquor",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.135547,
    26.119462 ]
   },
   "properties": {


     "address": "721 E Las Olas Blvd",
     "city": "Fort Lauderdale",
     "country": "United States",
     "postalCode": "33316",
     "state": "FL",
     "text": "American Social - Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.636306,
    27.768762 ]
   },
   "properties": {


     "address": "280 3Rd St S.",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "American Spirits - St Pete",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.760905,
    28.155043 ]
   },
   "properties": {


     "address": "735 Dodecanese Blvd #50",
     "city": "Tarpon Springs",
     "country": "United States",
     "postalCode": "34689",
     "state": "FL",
     "text": "Anclote Brew",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.383192,
    25.656066 ]
   },
   "properties": {


     "address": "12045 Sw 117Th Ave",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33186",
     "state": "FL",
     "text": "Arcade Odyssey",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.396907,
    28.449919 ]
   },
   "properties": {


     "address": "1317 Florida Mall Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32809",
     "state": "FL",
     "text": "Arlia",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.16419,
    25.688526 ]
   },
   "properties": {


     "address": "658 Crandon Blvd Suite120",
     "city": "Key Biscayne",
     "country": "United States",
     "postalCode": "33149",
     "state": "FL",
     "text": "Artisan Kitchen And Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.376412,
    28.543792 ]
   },
   "properties": {


     "address": "151 E Washington Streetsuite C101",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "B. Nice Patio Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.50018,
    28.384209 ]
   },
   "properties": {


     "address": "8516 Palm Pkwy",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32836",
     "state": "FL",
     "text": "Backstage Billiards",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.190163,
    25.773768 ]
   },
   "properties": {


     "address": "\"19 Se 2 Ave",
     "city": " Suite 4/4-1\"",
     "country": "Miami",
     "postalCode": "United States",
     "state": "33131",
     "text": "FL",
     "notice": "Balloo - Downtown Boys"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.351473,
    28.543909 ]
   },
   "properties": {


     "address": "2406 E Washington St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Barley & Vine Biergarten",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.243244,
    25.727805 ]
   },
   "properties": {


     "address": "3035 Fuller Street",
     "city": "Coconut Grove",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Barracuda Bar & Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.822103,
    28.560222 ]
   },
   "properties": {


     "address": "\"7965 State Road 50",
     "city": " A500\"",
     "country": "Groveland",
     "postalCode": "United States",
     "state": "34736",
     "text": "FL",
     "notice": "Barrels And Boards"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.443896,
    27.958625 ]
   },
   "properties": {


     "address": "1403 E 5Th Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33605",
     "state": "FL",
     "text": "Barriehaus Beer Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.278876,
    26.306896 ]
   },
   "properties": {


     "address": "6240 Coral Ridge Drsuite # 109",
     "city": "Coral Springs",
     "country": "United States",
     "postalCode": "33076",
     "state": "FL",
     "text": "Basser'S Fine Wine Inc.",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.257493,
    25.751492 ]
   },
   "properties": {


     "address": "141 Giralda Avenue",
     "city": "Coral Gables",
     "country": "United States",
     "postalCode": "33134",
     "state": "FL",
     "text": "Bay 13 Brewery And Kitchen",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.194757,
    25.802334 ]
   },
   "properties": {


     "address": "\"2637 North Miami Avenue",
     "city": " #102\"",
     "country": "Miami",
     "postalCode": "United States",
     "state": "33127",
     "text": "FL",
     "notice": "Beaker And Gray"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.313588,
    25.780755 ]
   },
   "properties": {


     "address": "7250 Nw 11Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33126",
     "state": "FL",
     "text": "Beat Culture Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.693736,
    30.310967 ]
   },
   "properties": {


     "address": "1271 King St",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32204",
     "state": "FL",
     "text": "Beer 30 - King Street",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.660419,
    30.309557 ]
   },
   "properties": {


     "address": "1543 San Marco Blvd",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32207",
     "state": "FL",
     "text": "Beer 30 #2 - San Marco",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.096282,
    26.94185 ]
   },
   "properties": {


     "address": "221 Center St",
     "city": "Jupiter",
     "country": "United States",
     "postalCode": "33458",
     "state": "FL",
     "text": "Beer City",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.26,
    30.44 ]
   },
   "properties": {


     "address": "1350 Mahan Dr. Suite C3",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32308",
     "state": "FL",
     "text": "Beer Stop Tallahassee",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.068905,
    26.464344 ]
   },
   "properties": {


     "address": "145 And 147 Ne 4Th Avenue",
     "city": "Delray Beach",
     "country": "United States",
     "postalCode": "33483",
     "state": "FL",
     "text": "Beer Trade Co - Delray Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.681685,
    28.580347 ]
   },
   "properties": {


     "address": "16355 Vetta Drive",
     "city": "Montverde",
     "country": "United States",
     "postalCode": "34756",
     "state": "FL",
     "text": "Bella Colina Country Club",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.729664,
    28.765052 ]
   },
   "properties": {


     "address": "280 Silverado Street",
     "city": "Tavares",
     "country": "United States",
     "postalCode": "32778",
     "state": "FL",
     "text": "Bella Nonna",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.583107,
    28.476821 ]
   },
   "properties": {


     "address": "13424 Summerport Village Parkway",
     "city": "Windermere",
     "country": "United States",
     "postalCode": "34786",
     "state": "FL",
     "text": "Bella Tuscany Ristorante Italiano",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.051989,
    26.675379 ]
   },
   "properties": {


     "address": "250 Southern Blvd",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33405",
     "state": "FL",
     "text": "Berto'S Bait & Tackle",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.191446,
    25.768569 ]
   },
   "properties": {


     "address": "75 Se 6Th Street Suite 103",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33131",
     "state": "FL",
     "text": "Better Days",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.284941,
    28.596274 ]
   },
   "properties": {


     "address": "7600 University Blvd",
     "city": "Winter Park",
     "country": "United States",
     "postalCode": "32792",
     "state": "FL",
     "text": "Big C Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.100621,
    26.189708 ]
   },
   "properties": {


     "address": "218 Commercial Blvdste 102",
     "city": "Lauderdale By The Sea",
     "country": "United States",
     "postalCode": "33308",
     "state": "FL",
     "text": "Billy Jacks Shack",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.1996,
    25.800033 ]
   },
   "properties": {


     "address": "232 24Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Bonci",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.341027,
    27.923764 ]
   },
   "properties": {


     "address": "10256 Causeway Blvdunit 101",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33619",
     "state": "FL",
     "text": "Bootleggers Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.19962,
    25.80336 ]
   },
   "properties": {


     "address": "2838 Nw 2Nd Ave Bldg 2",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Bottled Blonde Miami",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.287218,
    25.70418 ]
   },
   "properties": {


     "address": "7221 Sw 58Th Avenue",
     "city": "South Miami",
     "country": "United States",
     "postalCode": "33143",
     "state": "FL",
     "text": "Bougainvilleas Old Florida Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.154285,
    28.510058 ]
   },
   "properties": {


     "address": "\"3801 Avalon Park East Blvd",
     "city": " Ste 120\"",
     "country": "Orlando",
     "postalCode": "United States",
     "state": "32828",
     "text": "FL",
     "notice": "Bowigens Beer Company - Avalon Park"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.199078,
    25.803438 ]
   },
   "properties": {


     "address": "2817 Nw 2Nd Ave",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Boxelder",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.090509,
    26.536601 ]
   },
   "properties": {


     "address": "950 N Congress Avesuite J100",
     "city": "Boynton Beach",
     "country": "United States",
     "postalCode": "33426",
     "state": "FL",
     "text": "Brass Tap - Boynton Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.50472,
    28.04038 ]
   },
   "properties": {


     "address": "10019 N Dale Mabry Hwy",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33618",
     "state": "FL",
     "text": "Brass Tap - Carrollwood",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.138205,
    26.128931 ]
   },
   "properties": {


     "address": "551 North Federal Hwy Suite 600",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33301",
     "state": "FL",
     "text": "Brass Tap - Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.210768,
    29.556506 ]
   },
   "properties": {


     "address": "250 Palm Coast Parkway Ne Suite 201",
     "city": "Flagler Beach",
     "country": "United States",
     "postalCode": "32137",
     "state": "FL",
     "text": "Brass Tap - Palm Coast",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.33687,
    26.00271 ]
   },
   "properties": {


     "address": "624 Sw145Th Terrace",
     "city": "Pembroke Pines",
     "country": "United States",
     "postalCode": "33027",
     "state": "FL",
     "text": "Brass Tap - Pembroke Pines",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.277112,
    30.457131 ]
   },
   "properties": {


     "address": "1321 Thomasville Roadunit E",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32303",
     "state": "FL",
     "text": "Brass Tap - Tallahassee",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.201559,
    28.556695 ]
   },
   "properties": {


     "address": "781 N Alafaya Trl",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32828",
     "state": "FL",
     "text": "Brass Tap - Waterford Lakes",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.129963,
    29.486001 ]
   },
   "properties": {


     "address": "819 N Oceanshore Blvd",
     "city": "Flagler Beach",
     "country": "United States",
     "postalCode": "32126",
     "state": "FL",
     "text": "Break Awayz At The Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.405074,
    28.293957 ]
   },
   "properties": {


     "address": "7 E Dakin Ave",
     "city": "Kissimmee",
     "country": "United States",
     "postalCode": "34741",
     "state": "FL",
     "text": "Breeze",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.744687,
    27.941907 ]
   },
   "properties": {


     "address": "2241 Nursery Rd",
     "city": "Clearwater",
     "country": "United States",
     "postalCode": "33764",
     "state": "FL",
     "text": "Brew Garden Taphouse And Eatery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.640218,
    27.874371 ]
   },
   "properties": {


     "address": "11270 4Th St Nsuite 202",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33716",
     "state": "FL",
     "text": "Brewers Tasting Room",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.32291,
    29.86526 ]
   },
   "properties": {


     "address": "1974 Us 1 South",
     "city": "Saint Augustine",
     "country": "United States",
     "postalCode": "32086",
     "state": "FL",
     "text": "Brewz N Dawgz",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.120342,
    26.136519 ]
   },
   "properties": {


     "address": "1930 E Sunrise Blvdsuite #7-8",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33304",
     "state": "FL",
     "text": "Brgr Stop - Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.621645,
    28.035004 ]
   },
   "properties": {


     "address": "4700 Babcock St Ne",
     "city": "Palm Bay",
     "country": "United States",
     "postalCode": "32905",
     "state": "FL",
     "text": "Broken Barrel Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.352263,
    28.283998 ]
   },
   "properties": {


     "address": "2264 E Irlo Bronson Memorial Hwy",
     "city": "Kissimmee",
     "country": "United States",
     "postalCode": "34744",
     "state": "FL",
     "text": "Bronson Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.578572,
    28.091622 ]
   },
   "properties": {


     "address": "8729 Gunn Highway",
     "city": "Odessa",
     "country": "United States",
     "postalCode": "33556",
     "state": "FL",
     "text": "Bru Florida Growler Bar - Odessa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.354017,
    28.195064 ]
   },
   "properties": {


     "address": "2653 Bruce B Downs Blvd",
     "city": "Wesley Chapel",
     "country": "United States",
     "postalCode": "33544",
     "state": "FL",
     "text": "Bru Florida Growler Bar - Wesley Chapel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.7274,
    28.80264 ]
   },
   "properties": {


     "address": "143 E Main St",
     "city": "Tavares",
     "country": "United States",
     "postalCode": "32778",
     "state": "FL",
     "text": "Bru Tap House",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.37212,
    28.540119 ]
   },
   "properties": {


     "address": "420 E Church Street#118",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "Bynx",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.473096,
    28.011032 ]
   },
   "properties": {


     "address": "6905 North Orleans Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "C1949",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.473183,
    28.463691 ]
   },
   "properties": {


     "address": "6550 Adventure Way",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32819",
     "state": "FL",
     "text": "Cabana Bay Beach Resort",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.784297,
    28.013427 ]
   },
   "properties": {


     "address": "587 Main Street",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Caledonia Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.767548,
    27.76937 ]
   },
   "properties": {


     "address": "145 107Th Ave",
     "city": "Treasure Island",
     "country": "United States",
     "postalCode": "33706",
     "state": "FL",
     "text": "Captain Bills Beach Kitchen",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.24118,
    27.183509 ]
   },
   "properties": {


     "address": "1725 Se Federal Hwy",
     "city": "Stuart",
     "country": "United States",
     "postalCode": "34994",
     "state": "FL",
     "text": "Casa Tequila - Stuart",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.240333,
    27.2454 ]
   },
   "properties": {


     "address": "911 Ne Jensen Beach Blvd",
     "city": "Jensen Beach",
     "country": "United States",
     "postalCode": "34957",
     "state": "FL",
     "text": "Castaways Isle - Jensen Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.32572,
    25.84591 ]
   },
   "properties": {


     "address": "8001 Nw 79Th Ave",
     "city": "Medley",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "Cayman Spirits Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.316621,
    25.730576 ]
   },
   "properties": {


     "address": "4233 Sw 75Th Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33155",
     "state": "FL",
     "text": "Ceiba",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.541209,
    28.317979 ]
   },
   "properties": {


     "address": "721 Front St",
     "city": "Celebration",
     "country": "United States",
     "postalCode": "34747",
     "state": "FL",
     "text": "Celebration Town Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.26613,
    28.811581 ]
   },
   "properties": {


     "address": "114 S Palmetto Ave",
     "city": "Sanford",
     "country": "United States",
     "postalCode": "32771",
     "state": "FL",
     "text": "Celery City Craft",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.733377,
    26.377129 ]
   },
   "properties": {


     "address": "10441 Packing House Lane",
     "city": "Bonita Springs",
     "country": "United States",
     "postalCode": "34135",
     "state": "FL",
     "text": "Ceremony Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.768475,
    28.555529 ]
   },
   "properties": {


     "address": "\"639 8Th Street",
     "city": " Suite 12\"",
     "country": "Clermont",
     "postalCode": "United States",
     "state": "34711",
     "text": "FL",
     "notice": "Charcuterie And Chill"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.376281,
    25.756839 ]
   },
   "properties": {


     "address": "11200 Sw 8Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33199",
     "state": "FL",
     "text": "Chartwells At Fiu Panther Stadium",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.352924,
    25.598171 ]
   },
   "properties": {


     "address": "18419 South Dixie Hwy",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33101",
     "state": "FL",
     "text": "Checkers Liquors & Lounge Viii -Pba Acct",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.353708,
    25.687749 ]
   },
   "properties": {


     "address": "9881 & 9883 Sw 88Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33176",
     "state": "FL",
     "text": "Checkers Liquors Xxvi",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.308906,
    25.912893 ]
   },
   "properties": {


     "address": "15301 Nw 67Th Avenue",
     "city": "Miami Lakes",
     "country": "United States",
     "postalCode": "33014",
     "state": "FL",
     "text": "Chela'S Beer Garden",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.050801,
    26.714266 ]
   },
   "properties": {


     "address": "195 N Narcissus Ave",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33401",
     "state": "FL",
     "text": "City Of West Palm Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.522101,
    28.370285 ]
   },
   "properties": {


     "address": "1486 East Buena Vista Drive",
     "city": "Lake Buena Vista",
     "country": "United States",
     "postalCode": "32830",
     "state": "FL",
     "text": "City Works Eatery And Pour House",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.115128,
    26.889595 ]
   },
   "properties": {


     "address": "1200 Town Center Dr Ste 101",
     "city": "Jupiter",
     "country": "United States",
     "postalCode": "33458",
     "state": "FL",
     "text": "Civil Society Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.257577,
    25.751185 ]
   },
   "properties": {


     "address": "146 Giralda Avenue",
     "city": "Coral Gables",
     "country": "United States",
     "postalCode": "33134",
     "state": "FL",
     "text": "Clutch Burger",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -86.091954,
    30.313231 ]
   },
   "properties": {


     "address": "5221 E County Highway 30A",
     "city": "Santa Rosa Beach",
     "country": "United States",
     "postalCode": "32459",
     "state": "FL",
     "text": "Coastal Dune Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.932662,
    28.009359 ]
   },
   "properties": {


     "address": "1221 S Fl Ave",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33803",
     "state": "FL",
     "text": "Cob & Pen",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.266813,
    28.81119 ]
   },
   "properties": {


     "address": "115 Magnolia Ave",
     "city": "32771",
     "country": "United States",
     "postalCode": "32771",
     "state": "FL",
     "text": "Community Brewhouse",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.262792,
    30.436279 ]
   },
   "properties": {


     "address": "1235 Apalachee Pkwy",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32301",
     "state": "FL",
     "text": "Community Coop Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.262792,
    30.436279 ]
   },
   "properties": {


     "address": "1235 Apalachee Parkway",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32301",
     "state": "FL",
     "text": "Community Coop Market-Aots",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.365887,
    28.618043 ]
   },
   "properties": {


     "address": "106 Lake Ave",
     "city": "Maitland",
     "country": "United States",
     "postalCode": "32751",
     "state": "FL",
     "text": "Copper Rocket Pub",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.569156,
    28.090497 ]
   },
   "properties": {


     "address": "205 5Th Ave",
     "city": "Indialantic",
     "country": "United States",
     "postalCode": "32903",
     "state": "FL",
     "text": "Copperhead Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.281788,
    25.822717 ]
   },
   "properties": {


     "address": "78 Canal Street",
     "city": "Miami Springs",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "Crackers",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.932662,
    28.009359 ]
   },
   "properties": {


     "address": "3234 S Fl Ave",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33803",
     "state": "FL",
     "text": "Craft & Kitchen - Lakeland Beer Rev",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.157999,
    26.11438 ]
   },
   "properties": {


     "address": "557 Sw 12Th Avenue",
     "city": "Fort Lauderdale",
     "country": "United States",
     "postalCode": "33312",
     "state": "FL",
     "text": "Craft Beer Cartel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.117612,
    26.15997 ]
   },
   "properties": {


     "address": "2301 Ne 26 Street",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33305",
     "state": "FL",
     "text": "Craft Beer Cellar - Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.435365,
    27.394027 ]
   },
   "properties": {


     "address": "8141 Lakewood Main Stsuite 103",
     "city": "Lakewood Ranch",
     "country": "United States",
     "postalCode": "34202",
     "state": "FL",
     "text": "Craft Growlers To Go",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.410131,
    25.653018 ]
   },
   "properties": {


     "address": "12323 Sw 133 Ctunit 17",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33186",
     "state": "FL",
     "text": "Crafty Beer Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.814175,
    26.567977 ]
   },
   "properties": {


     "address": "8500 Penzance Blvd",
     "city": "Fort Myers",
     "country": "United States",
     "postalCode": "33912",
     "state": "FL",
     "text": "Crazy Dingo Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.623618,
    28.079357 ]
   },
   "properties": {


     "address": "923 & 925 New Haven Ave",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "Crush Eleven",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.115035,
    26.889966 ]
   },
   "properties": {


     "address": "1203 Town Center Dr Ste 116",
     "city": "Jupiter",
     "country": "United States",
     "postalCode": "33458",
     "state": "FL",
     "text": "Das Beergarden",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.389043,
    28.56277 ]
   },
   "properties": {


     "address": "1215 Edgewater Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32804",
     "state": "FL",
     "text": "Digress Wine",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.512322,
    27.270173 ]
   },
   "properties": {


     "address": "2881 Clark Rd Units 19 & 20",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34231",
     "state": "FL",
     "text": "Dive Wine & Spirits",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.055573,
    26.667317 ]
   },
   "properties": {


     "address": "5101 South Dixie Highway",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33405",
     "state": "FL",
     "text": "Dixie Bar & Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.697183,
    28.021785 ]
   },
   "properties": {


     "address": "868 Jupiter Blvd Nwsuite 1",
     "city": "Palm Bay",
     "country": "United States",
     "postalCode": "32907",
     "state": "FL",
     "text": "Diya Food Store",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.570516,
    28.090077 ]
   },
   "properties": {


     "address": "249 5Th Avesuite B",
     "city": "Indialantic",
     "country": "United States",
     "postalCode": "32903",
     "state": "FL",
     "text": "Djons Village Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.214345,
    25.767978 ]
   },
   "properties": {


     "address": "541 Sw 12Th Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33130",
     "state": "FL",
     "text": "Doce Provisions",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.365229,
    25.817451 ]
   },
   "properties": {


     "address": "5001 Nw 104Th Avenue",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33178",
     "state": "FL",
     "text": "Doral Park Country Club",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.685801,
    28.100187 ]
   },
   "properties": {


     "address": "7856 Ellis Rd",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32904",
     "state": "FL",
     "text": "Downtown Discount Produce",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.61023,
    28.32478 ]
   },
   "properties": {


     "address": "350 N Orlando Ave",
     "city": "Cocoa Beach",
     "country": "United States",
     "postalCode": "32931",
     "state": "FL",
     "text": "Drift House - Cocoa Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.38709,
    28.582742 ]
   },
   "properties": {


     "address": "549 W Par Street",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32804",
     "state": "FL",
     "text": "Dubsdread Golf Club",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.789462,
    28.014043 ]
   },
   "properties": {


     "address": "927-929 Broadway",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Dunedin House Of Beer",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.223148,
    25.773498 ]
   },
   "properties": {


     "address": "1701 W Flagler Stunit 101",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33135",
     "state": "FL",
     "text": "Edukos Beer House",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.13466,
    26.11948 ]
   },
   "properties": {


     "address": "817 East Las Olas Blvd",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33301",
     "state": "FL",
     "text": "El Camino - Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.722925,
    28.548312 ]
   },
   "properties": {


     "address": "1391 Citrus Tower Blvd",
     "city": "Clermont",
     "country": "United States",
     "postalCode": "34711",
     "state": "FL",
     "text": "Ellie Lou'S Brews & Bbq - Clermont",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.539816,
    28.529823 ]
   },
   "properties": {


     "address": "336 Moore Rd",
     "city": "Ocoee",
     "country": "United States",
     "postalCode": "34761",
     "state": "FL",
     "text": "Ellie Lous Brews & Bbq - Ocoee",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.296287,
    28.456786 ]
   },
   "properties": {


     "address": "\"7500 Tpc Blvd",
     "city": " Suite 7 & 8\"",
     "country": "Orlando",
     "postalCode": "United States",
     "state": "32822",
     "text": "FL",
     "notice": "Ellipsis Brewing"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.40717,
    30.287596 ]
   },
   "properties": {


     "address": "1500 Beach Blvd #217",
     "city": "Jacksonville Beach",
     "country": "United States",
     "postalCode": "32250",
     "state": "FL",
     "text": "Engine 15 Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.646852,
    27.771777 ]
   },
   "properties": {


     "address": "56 Dr Mlk Jr Blvd North",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33705",
     "state": "FL",
     "text": "Engine No 9",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.370797,
    28.549231 ]
   },
   "properties": {


     "address": "522 East Amelia Street",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Eola General",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.371605,
    28.54211 ]
   },
   "properties": {


     "address": "430 E Central Blvd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "Eola Wine Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.650137,
    28.181726 ]
   },
   "properties": {


     "address": "9945 Trinity Blvd#108/107",
     "city": "Trinity",
     "country": "United States",
     "postalCode": "34655",
     "state": "FL",
     "text": "Escape Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.606216,
    28.077974 ]
   },
   "properties": {


     "address": "843 E New Haven Ave",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "Executive Cigar Shop And Lounge Inc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.47646,
    25.4508 ]
   },
   "properties": {


     "address": "12 Ne 3 St Unit# 30",
     "city": "Florida City",
     "country": "United States",
     "postalCode": "33034",
     "state": "FL",
     "text": "Exit One Taproom",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.13571,
    26.16656 ]
   },
   "properties": {


     "address": "830 E Oakland Park Blvdsuite 101",
     "city": "Oakland Park",
     "country": "United States",
     "postalCode": "33334",
     "state": "FL",
     "text": "Fat Tap Beer Bar And Eatery Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.543979,
    28.481031 ]
   },
   "properties": {


     "address": "4757 The Grove Drivesuite 100",
     "city": "Windermere",
     "country": "United States",
     "postalCode": "34786",
     "state": "FL",
     "text": "Feather & Quill Eatery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.286517,
    30.433935 ]
   },
   "properties": {


     "address": "415 Saint Francis Stunit 113",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32301",
     "state": "FL",
     "text": "Fermentation Lounge @ All Saints",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.431859,
    25.742577 ]
   },
   "properties": {


     "address": "14690 Sw 26Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33175",
     "state": "FL",
     "text": "Finka Table & Tap",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.192732,
    25.851603 ]
   },
   "properties": {


     "address": "8303 Ne 2 Ave",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33138",
     "state": "FL",
     "text": "Fire Kitchen & Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.608103,
    28.35695 ]
   },
   "properties": {


     "address": "102 Dixie Ln",
     "city": "Cocoa Beach",
     "country": "United States",
     "postalCode": "32931",
     "state": "FL",
     "text": "Florida Key Lime Pie Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.23929,
    25.735489 ]
   },
   "properties": {


     "address": "2859 Bird Ave Suite 1",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Fly Buy",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.677321,
    27.789403 ]
   },
   "properties": {


     "address": "Th Avenue North",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33713",
     "state": "FL",
     "text": "Flying Boat Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.035158,
    29.094823 ]
   },
   "properties": {


     "address": "8780 Se 71St Ct",
     "city": "Ocala",
     "country": "United States",
     "postalCode": "34472",
     "state": "FL",
     "text": "Flying Boat Tap Room",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.193852,
    25.784585 ]
   },
   "properties": {


     "address": "1035 N Miami Ave Unit 103",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33136",
     "state": "FL",
     "text": "Fooq'S",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.351012,
    25.701452 ]
   },
   "properties": {


     "address": "8701 Sunset Drive",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33173",
     "state": "FL",
     "text": "Foremost Sunset Corners",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.191563,
    25.758736 ]
   },
   "properties": {


     "address": "1441 Brickell Ave",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33131",
     "state": "FL",
     "text": "Four Seasons Hotel Miami",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.350922,
    28.524381 ]
   },
   "properties": {


     "address": "2415 Curry Ford Road",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Freehand Goods",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.126467,
    25.804478 ]
   },
   "properties": {


     "address": "2727 Indian Creek Drive",
     "city": "Miami Beach",
     "country": "United States",
     "postalCode": "33139",
     "state": "FL",
     "text": "Freehand Miami - Indian Creek Hotel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.189631,
    25.771195 ]
   },
   "properties": {


     "address": "333 Se 2Nd Ave Suite 3200",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33131",
     "state": "FL",
     "text": "Freehold - Miami",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.485072,
    28.514775 ]
   },
   "properties": {


     "address": "2461 S Hiawassee Rd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32835",
     "state": "FL",
     "text": "Friendly Confines - Metro West",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.644711,
    28.799721 ]
   },
   "properties": {


     "address": "411 North Donnelly Street",
     "city": "Mount Dora",
     "country": "United States",
     "postalCode": "32757",
     "state": "FL",
     "text": "Frog And Monkey Restaurant & Pub",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.301561,
    28.992159 ]
   },
   "properties": {


     "address": "2075 S Woodland Blvd",
     "city": "Deland",
     "country": "United States",
     "postalCode": "32720",
     "state": "FL",
     "text": "Gaff'S Meat - Deland",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.268007,
    27.894309 ]
   },
   "properties": {


     "address": "1028 E Bloomingdale Blvd",
     "city": "Valrico",
     "country": "United States",
     "postalCode": "33596",
     "state": "FL",
     "text": "Gasparilla Pizzeria & Growlers",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.374085,
    28.495127 ]
   },
   "properties": {


     "address": "4721 S Orange Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Gatlin Hall Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.370563,
    28.564197 ]
   },
   "properties": {


     "address": "529 Virginia Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Gb'S Bottle Shop & Tasting Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.124625,
    25.807161 ]
   },
   "properties": {


     "address": "3120 Collins Ave",
     "city": "Miami Beach",
     "country": "United States",
     "postalCode": "33140",
     "state": "FL",
     "text": "Generator",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.257849,
    27.200628 ]
   },
   "properties": {


     "address": "615 Sw Anchorge Waysuite 2",
     "city": "Stuart",
     "country": "United States",
     "postalCode": "34994",
     "state": "FL",
     "text": "Gilbert'S Coffee Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.139359,
    26.135447 ]
   },
   "properties": {


     "address": "900 N Flagler Drive Unit 905",
     "city": "Fort Lauderdale",
     "country": "United States",
     "postalCode": "33304",
     "state": "FL",
     "text": "Glitch Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.372644,
    28.564444 ]
   },
   "properties": {


     "address": "1407 N Orange Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32804",
     "state": "FL",
     "text": "Gnarly Barley",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.707675,
    27.740512 ]
   },
   "properties": {


     "address": "2960 Beach Blvd S",
     "city": "Gulf Port",
     "country": "United States",
     "postalCode": "33707",
     "state": "FL",
     "text": "Golden Dinosaurs Vegan Deli",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.198484,
    25.79971 ]
   },
   "properties": {


     "address": "178 - 188 Nw 24Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Gramps Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.870942,
    26.64426 ]
   },
   "properties": {


     "address": "1412 Dean Street Suite 100",
     "city": "Fort Myers",
     "country": "United States",
     "postalCode": "33901",
     "state": "FL",
     "text": "Green Cup Cafe",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.585619,
    28.138285 ]
   },
   "properties": {


     "address": "855 E Eau Gallie Blvd",
     "city": "Indian Harbour Beach",
     "country": "United States",
     "postalCode": "32937",
     "state": "FL",
     "text": "Green Turtle Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.24564,
    30.496344 ]
   },
   "properties": {


     "address": "3305 Capital Circle Neste 104",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32308",
     "state": "FL",
     "text": "Growler Country",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.364265,
    28.562888 ]
   },
   "properties": {


     "address": "1321 N Mills Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Guesthouse",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.368337,
    26.029341 ]
   },
   "properties": {


     "address": "16642 Sheridan Street",
     "city": "Pembroke Pines",
     "country": "United States",
     "postalCode": "33331",
     "state": "FL",
     "text": "Gypsy Moon Vapin Brews",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.622319,
    28.516236 ]
   },
   "properties": {


     "address": "16112 Marsh Rd Unit 401",
     "city": "Winter Garden",
     "country": "United States",
     "postalCode": "34787",
     "state": "FL",
     "text": "Hagan O'Reilly'S Irish Pub & Restaurant",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.448554,
    28.430285 ]
   },
   "properties": {


     "address": "9650 Universal Blvd Ste 143",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32819",
     "state": "FL",
     "text": "Half Barrel Beer Project",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.450967,
    28.001241 ]
   },
   "properties": {


     "address": "5921 N Nebraska Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "Hampton Station",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.632592,
    27.764486 ]
   },
   "properties": {


     "address": "540 1St St S.E.",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "Hangar Restaurant & Flight Lounge",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.19381,
    25.765006 ]
   },
   "properties": {


     "address": "900 South Miami Avenue#125",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33130",
     "state": "FL",
     "text": "Happea'S",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.289829,
    25.763504 ]
   },
   "properties": {


     "address": "5792 Sw 8Th Street",
     "city": "West Miami",
     "country": "United States",
     "postalCode": "33144",
     "state": "FL",
     "text": "Happy Wine",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.433568,
    25.598034 ]
   },
   "properties": {


     "address": "18151 Sw 149 Ave",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33187",
     "state": "FL",
     "text": "Hate Mondays",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.673181,
    27.771286 ]
   },
   "properties": {


     "address": "2927 Central Ave",
     "city": "Saint Petersburg",
     "country": "United States",
     "postalCode": "33713",
     "state": "FL",
     "text": "Hawthorne Bottle Shoppe",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.343803,
    28.568257 ]
   },
   "properties": {


     "address": "3201 Corrine Drbooth #3",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Hinckley'S Fancy Meats Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.625325,
    28.474072 ]
   },
   "properties": {


     "address": "16016 New Independance Pkwy #100",
     "city": "Winter Garden",
     "country": "United States",
     "postalCode": "34787",
     "state": "FL",
     "text": "Home State Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.215946,
    25.797662 ]
   },
   "properties": {


     "address": "1200 Nw 22Nd Street #100",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33142",
     "state": "FL",
     "text": "Hometown Barbecue",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.068559,
    26.470048 ]
   },
   "properties": {


     "address": "440 Ne 5Th Ave",
     "city": "Delray Beach",
     "country": "United States",
     "postalCode": "33483",
     "state": "FL",
     "text": "Hopportunities Taproom",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.790125,
    28.016116 ]
   },
   "properties": {


     "address": "1006 Broadway Street",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Hopscotch Cafe",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.017753,
    29.119498 ]
   },
   "properties": {


     "address": "1396 Dunlawton Ave",
     "city": "Port Orange",
     "country": "United States",
     "postalCode": "32127",
     "state": "FL",
     "text": "Houligans A Spirited Sports Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.427294,
    28.36964 ]
   },
   "properties": {


     "address": "13526 Village Park Dr Ste 208",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32837",
     "state": "FL",
     "text": "House Of Beer",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.772738,
    28.713702 ]
   },
   "properties": {


     "address": "101 S Palm Ave",
     "city": "Howey In The Hills",
     "country": "United States",
     "postalCode": "34737",
     "state": "FL",
     "text": "Howey Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.445879,
    25.672502 ]
   },
   "properties": {


     "address": "10131 Sw 154 Circle Court 104",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33196",
     "state": "FL",
     "text": "Hybrid House Coffee & Beer",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.649454,
    27.771346 ]
   },
   "properties": {


     "address": "1049 Central Ave",
     "city": "Saint Petersburg",
     "country": "United States",
     "postalCode": "33705",
     "state": "FL",
     "text": "Independent - St Pete",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.463804,
    27.986147 ]
   },
   "properties": {


     "address": "5016 N Fl Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33603",
     "state": "FL",
     "text": "Independent - Tampa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.710236,
    28.011228 ]
   },
   "properties": {


     "address": "2481 Mcmullen Booth Rdsuite D",
     "city": "Clearwater",
     "country": "United States",
     "postalCode": "33759",
     "state": "FL",
     "text": "Infinity Pizza",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.054974,
    26.86388 ]
   },
   "properties": {


     "address": "12772 Us Highway 1",
     "city": "Juno Beach",
     "country": "United States",
     "postalCode": "33408",
     "state": "FL",
     "text": "Inlet Beach Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.605286,
    28.077739 ]
   },
   "properties": {


     "address": "2023 Melbourne Ct",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "Iron Oak Post",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.564941,
    27.277243 ]
   },
   "properties": {


     "address": "5110 Ocean Blvd",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34242",
     "state": "FL",
     "text": "Island House Tap And Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.610681,
    28.345669 ]
   },
   "properties": {


     "address": "3267 Rolling Oaks Blvd",
     "city": "Kissimmee",
     "country": "United States",
     "postalCode": "34747",
     "state": "FL",
     "text": "Island Wing Company Grill & Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.302766,
    29.02887 ]
   },
   "properties": {


     "address": "114 E Indiana Avenue",
     "city": "Deland",
     "country": "United States",
     "postalCode": "32724",
     "state": "FL",
     "text": "Issues",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.192478,
    25.812614 ]
   },
   "properties": {


     "address": "\"140 Ne 39Th Street",
     "city": " #136\"",
     "country": "Miami",
     "postalCode": "United States",
     "state": "33137",
     "text": "FL",
     "notice": "Itamae"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.27755,
    30.455053 ]
   },
   "properties": {


     "address": "1123 Thomasville Roadsuite C",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32303",
     "state": "FL",
     "text": "Izzy Pub & Sushi Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.618563,
    30.198602 ]
   },
   "properties": {


     "address": "9825 San Jose Blvd Suite 18",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32257",
     "state": "FL",
     "text": "Jax Craft Beer",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.610321,
    28.322303 ]
   },
   "properties": {


     "address": "210 N Orlando Ave",
     "city": "Cocoa Beach",
     "country": "United States",
     "postalCode": "32931",
     "state": "FL",
     "text": "Jazzys Mainely Lobster & Seafood",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.266681,
    26.662441 ]
   },
   "properties": {


     "address": "13889 Wellington Tracesuite A-20",
     "city": "Wellington",
     "country": "United States",
     "postalCode": "33414",
     "state": "FL",
     "text": "Jo Jo'S Raw Bar & Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.30139,
    25.69314 ]
   },
   "properties": {


     "address": "8247 S Dixie Hwy",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33101",
     "state": "FL",
     "text": "Joanna'S Marketplace",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.586096,
    28.565467 ]
   },
   "properties": {


     "address": "28 W Plant St",
     "city": "Winter Garden",
     "country": "United States",
     "postalCode": "34787",
     "state": "FL",
     "text": "Jrs Attic Door",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.449816,
    28.014096 ]
   },
   "properties": {


     "address": "6203 N Fl Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "Jug & Bottle Dept",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.234448,
    29.227791 ]
   },
   "properties": {


     "address": "6998 N Us Hwy 27Suite 112",
     "city": "Ocala",
     "country": "United States",
     "postalCode": "34482",
     "state": "FL",
     "text": "Juniper General Store",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.42823,
    28.401489 ]
   },
   "properties": {


     "address": "4040 Central Fl Pkwy",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32837",
     "state": "FL",
     "text": "Jw Marriott Orlando Grande Lakes",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.680641,
    30.320798 ]
   },
   "properties": {


     "address": "580 College Street",
     "city": "Jacksonville",
     "country": "United States",
     "postalCode": "32204",
     "state": "FL",
     "text": "Kanine Social Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.413967,
    25.647965 ]
   },
   "properties": {


     "address": "12805 Sw 136Th Ave",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33186",
     "state": "FL",
     "text": "Keg South",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.197968,
    27.860219 ]
   },
   "properties": {


     "address": "5622 Lithia Pinecrest Rd",
     "city": "Lithia",
     "country": "United States",
     "postalCode": "33547",
     "state": "FL",
     "text": "Kennys Liquor - Lithia",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.398733,
    27.636982 ]
   },
   "properties": {


     "address": "1937 Old Dixie Hwy",
     "city": "Vero Beach",
     "country": "United States",
     "postalCode": "32960",
     "state": "FL",
     "text": "Kilted Mermaid",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.426635,
    28.370904 ]
   },
   "properties": {


     "address": "13500 S John Young Parkway",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32837",
     "state": "FL",
     "text": "King Crab Orlando",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.402955,
    28.377754 ]
   },
   "properties": {


     "address": "12975 S Orange Blossom Trl",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32837",
     "state": "FL",
     "text": "Knightly Spirits At Obt",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.24064,
    25.728479 ]
   },
   "properties": {


     "address": "2911 Grand Ave#400D",
     "city": "Coconut Grove",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Kush - Coconut Grove",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.194689,
    25.795966 ]
   },
   "properties": {


     "address": "2003 North Miami Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Kush - Wynwood",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.141103,
    26.134903 ]
   },
   "properties": {


     "address": "901 Progresso Dr #101",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33304",
     "state": "FL",
     "text": "Laserwolf",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.16226,
    26.061884 ]
   },
   "properties": {


     "address": "1825 Griffin Rd",
     "city": "Dania Beach",
     "country": "United States",
     "postalCode": "33004",
     "state": "FL",
     "text": "Le Meridien Dania Beach At Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.455469,
    27.964667 ]
   },
   "properties": {


     "address": "2210 N Central Avenue",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33602",
     "state": "FL",
     "text": "Lee'S Grocery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.314344,
    25.732117 ]
   },
   "properties": {


     "address": "7360 Sw 41 Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33155",
     "state": "FL",
     "text": "Lincoln'S Beard Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.641308,
    27.766864 ]
   },
   "properties": {


     "address": "400 6Th. St. S",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "Lingr Restaurant",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.462007,
    27.339482 ]
   },
   "properties": {


     "address": "5403 Fruitville Road",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "33149",
     "state": "FL",
     "text": "Liquor Locker",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.08015,
    26.93292 ]
   },
   "properties": {


     "address": "103 So Us Hwy 1",
     "city": "Jupiter",
     "country": "United States",
     "postalCode": "33477",
     "state": "FL",
     "text": "Little Moirs Food Shack",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.592787,
    28.034165 ]
   },
   "properties": {


     "address": "2600 Palm Bay Rd",
     "city": "Palm Bay",
     "country": "United States",
     "postalCode": "32905",
     "state": "FL",
     "text": "Little Store Palm Bay",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.283362,
    28.248412 ]
   },
   "properties": {


     "address": "1023 New York Ave",
     "city": "St Cloud",
     "country": "United States",
     "postalCode": "34769",
     "state": "FL",
     "text": "Loading...Gastrobrunch",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.378945,
    28.543056 ]
   },
   "properties": {


     "address": "49 N Orange Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "Lodge",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.245145,
    25.727623 ]
   },
   "properties": {


     "address": "3190 Commodore Plaza",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Lokal Burgers And Beers",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.242587,
    25.727657 ]
   },
   "properties": {


     "address": "3413 Main Highway",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Los Felix",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.192073,
    25.887459 ]
   },
   "properties": {


     "address": "12207 Ne 3Th Court",
     "city": "North Miami",
     "country": "United States",
     "postalCode": "33161",
     "state": "FL",
     "text": "Lost City Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.957415,
    28.018299 ]
   },
   "properties": {


     "address": "2101 S. Florida Avenue",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33803",
     "state": "FL",
     "text": "Lovebird",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.471297,
    28.025671 ]
   },
   "properties": {


     "address": "1213 W Waters Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "Lowry Parcade & Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.767216,
    28.019738 ]
   },
   "properties": {


     "address": "1410 Main Street",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Luekens - Dunedin",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.759877,
    28.148306 ]
   },
   "properties": {


     "address": "41522 Us Hwy 19Nunit # 1",
     "city": "Tarpon Springs",
     "country": "United States",
     "postalCode": "34689",
     "state": "FL",
     "text": "Luekens Liquors - Tarpon Springs",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.787513,
    27.835562 ]
   },
   "properties": {


     "address": "6950 Seminole Blvd",
     "city": "Seminole",
     "country": "United States",
     "postalCode": "33772",
     "state": "FL",
     "text": "Luekens Wine & Spirits - Seminole",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.781316,
    28.052166 ]
   },
   "properties": {


     "address": "2660 Bayshore Blvd",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Madison Ave Pizza",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.64611,
    28.799624 ]
   },
   "properties": {


     "address": "237 W 4Th Ave",
     "city": "Mt Dora",
     "country": "United States",
     "postalCode": "32757",
     "state": "FL",
     "text": "Maggie'S Attic",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.459724,
    27.957501 ]
   },
   "properties": {


     "address": "1420 N Florida Avenue",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33602",
     "state": "FL",
     "text": "Magnanimous Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.190102,
    25.77533 ]
   },
   "properties": {


     "address": "207 Ne 1St Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33132",
     "state": "FL",
     "text": "Mama Tried - Downtown Fun",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.540339,
    27.340351 ]
   },
   "properties": {


     "address": "428 N Lemon Ave",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34236",
     "state": "FL",
     "text": "Mandeville Beer Garden",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.763505,
    28.030115 ]
   },
   "properties": {


     "address": "1560 Coachlight Way",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Mangos And Marley Cafe",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.190163,
    25.773768 ]
   },
   "properties": {


     "address": "21 Se 2Nd Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33131",
     "state": "FL",
     "text": "Margot",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.284603,
    30.462591 ]
   },
   "properties": {


     "address": "1700 North Monroe Streetsuite #6",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32303",
     "state": "FL",
     "text": "Market Liquor #2",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.349348,
    28.538884 ]
   },
   "properties": {


     "address": "2603 E South St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Market On South",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.372141,
    25.86532 ]
   },
   "properties": {


     "address": "10205 Nw 108Th Ave Suite 1",
     "city": "Medley",
     "country": "United States",
     "postalCode": "33178",
     "state": "FL",
     "text": "Market Street Ltd",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.34735,
    25.608071 ]
   },
   "properties": {


     "address": "17395 S Dixie Hwy",
     "city": "Palmetto Bay",
     "country": "United States",
     "postalCode": "33157",
     "state": "FL",
     "text": "Maxwell Bros",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.230708,
    25.750337 ]
   },
   "properties": {


     "address": "2229 Coral Way",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33145",
     "state": "FL",
     "text": "Meat And Bone Inc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.62181,
    28.088521 ]
   },
   "properties": {


     "address": "1317 S Babcock Street",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "Melbourne Liquor",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.245929,
    25.750373 ]
   },
   "properties": {


     "address": "3201 Coral Way",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33145",
     "state": "FL",
     "text": "Mendez Fuel Holdings Llc-Mobil (Pba)",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.636411,
    28.80019 ]
   },
   "properties": {


     "address": "458 N Highland St",
     "city": "Mt Dora",
     "country": "United States",
     "postalCode": "32757",
     "state": "FL",
     "text": "Mermaid Juice",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.45073,
    28.009547 ]
   },
   "properties": {


     "address": "6719 N Nebraska Ave Ste A",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "Mermaid Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.084155,
    29.193336 ]
   },
   "properties": {


     "address": "3818 Ne 7Th Street",
     "city": "Ocala",
     "country": "United States",
     "postalCode": "34470",
     "state": "FL",
     "text": "Metro Craft Beer Headquarters",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.196119,
    25.801046 ]
   },
   "properties": {


     "address": "55 Nw 25Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Miami Beer Ventures Llc-Veza Sur Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.62197,
    28.083533 ]
   },
   "properties": {


     "address": "1600 S Babcock St",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "Midtown Liquor",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.281109,
    25.820901 ]
   },
   "properties": {


     "address": "70 Curtiss Parkway",
     "city": "Miami Springs",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "Milams Market #2",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.245799,
    25.736348 ]
   },
   "properties": {


     "address": "2969 Sw 32 Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Milams Market #3",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.324743,
    25.662482 ]
   },
   "properties": {


     "address": "11701 South Dixie Hwy",
     "city": "Pinecrest",
     "country": "United States",
     "postalCode": "33156",
     "state": "FL",
     "text": "Milams Market #7",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.85051,
    28.675946 ]
   },
   "properties": {


     "address": "2800 Us Hwy 1Unit B",
     "city": "Mims",
     "country": "United States",
     "postalCode": "32754",
     "state": "FL",
     "text": "Mim'S Liquor",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.684859,
    27.996385 ]
   },
   "properties": {


     "address": "3054 Cypress Gardens Rd",
     "city": "Winter Haven",
     "country": "United States",
     "postalCode": "33884",
     "state": "FL",
     "text": "Mm Vapor Cafe Winter Haven",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.316689,
    26.155887 ]
   },
   "properties": {


     "address": "2602 Sawgrass Mills Circlesuite #1219",
     "city": "Sunrise",
     "country": "United States",
     "postalCode": "33323",
     "state": "FL",
     "text": "Mojitobar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.768507,
    28.554989 ]
   },
   "properties": {


     "address": "793 Montrose Street",
     "city": "Clermont",
     "country": "United States",
     "postalCode": "34711",
     "state": "FL",
     "text": "Montrose Street Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.084251,
    26.957156 ]
   },
   "properties": {


     "address": "235 South Us Hwy 1",
     "city": "Tequesta",
     "country": "United States",
     "postalCode": "33469",
     "state": "FL",
     "text": "Mood",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.690429,
    28.123493 ]
   },
   "properties": {


     "address": "3945 W Eau Gallie Blvdsuite 109",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32934",
     "state": "FL",
     "text": "Mr Brews Taphouse",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.064794,
    29.193826 ]
   },
   "properties": {


     "address": "1700 Volusia Ave",
     "city": "Daytona Beach",
     "country": "United States",
     "postalCode": "32100",
     "state": "FL",
     "text": "Mr Dunderbaks - Daytona Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.515296,
    27.259183 ]
   },
   "properties": {


     "address": "6639 Superior Ave",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34231",
     "state": "FL",
     "text": "Munchies 420 Cafe",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.404658,
    28.053662 ]
   },
   "properties": {


     "address": "4801 E Fowler Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33617",
     "state": "FL",
     "text": "Museum Of Science & Industry Foundation",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.137072,
    29.185919 ]
   },
   "properties": {


     "address": "46 S Magnolia Avesuite B",
     "city": "Ocala",
     "country": "United States",
     "postalCode": "34471",
     "state": "FL",
     "text": "Mutiny Bar Ocala",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.946971,
    26.562304 ]
   },
   "properties": {


     "address": "1404 Cape Coral Parkway East A&B",
     "city": "Cape Coral",
     "country": "United States",
     "postalCode": "33904",
     "state": "FL",
     "text": "Nice Guys Pizza",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.238113,
    25.736851 ]
   },
   "properties": {


     "address": "2950 Sw 27Th Avenue Suite 100",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Nightlife Brewing Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.95686,
    28.026946 ]
   },
   "properties": {


     "address": "1212 South Florida Ave",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33803",
     "state": "FL",
     "text": "Nineteen 61",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.282279,
    28.24834 ]
   },
   "properties": {


     "address": "1021 B Pennsylvania Ave",
     "city": "St. Cloud",
     "country": "United States",
     "postalCode": "34769",
     "state": "FL",
     "text": "No Coins Required",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.947948,
    26.562943 ]
   },
   "properties": {


     "address": "1319 Cape Coral Parkway Esuite #1",
     "city": "Cape Coral",
     "country": "United States",
     "postalCode": "33904",
     "state": "FL",
     "text": "No. 3 Craft Brews & Beer Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.062473,
    26.739623 ]
   },
   "properties": {


     "address": "933 28Th Street",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33407",
     "state": "FL",
     "text": "Northwood Art And Music Warehouse",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.635109,
    27.771428 ]
   },
   "properties": {


     "address": "199 Central Avenue",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "Oak & Stone - Downtown St Pete",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.573755,
    27.498845 ]
   },
   "properties": {


     "address": "1201 1St Avenue W",
     "city": "Bradenton",
     "country": "United States",
     "postalCode": "34205",
     "state": "FL",
     "text": "Oak & Stone Of Bradenton",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.46314,
    27.390636 ]
   },
   "properties": {


     "address": "5405 University Parkway Unit 101",
     "city": "Bradenton",
     "country": "United States",
     "postalCode": "34201",
     "state": "FL",
     "text": "Oak & Stone Of Sarasota",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.487581,
    27.26968 ]
   },
   "properties": {


     "address": "4067 Clark Road",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34236",
     "state": "FL",
     "text": "Oak & Stone On Clark Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.22117,
    26.68113 ]
   },
   "properties": {


     "address": "11051 Southern Blvdste 210",
     "city": "Royal Palm Beach",
     "country": "United States",
     "postalCode": "33411",
     "state": "FL",
     "text": "Oak Bistro And Wine Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.193038,
    25.850545 ]
   },
   "properties": {


     "address": "8250 Ne 2Nd Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33138",
     "state": "FL",
     "text": "Offsite",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.638135,
    27.791929 ]
   },
   "properties": {


     "address": "2131 4Th Street North",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33704",
     "state": "FL",
     "text": "Old Northeast Rally",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.225844,
    30.542983 ]
   },
   "properties": {


     "address": "2910 Kerry Forest Pkwyste A7 A8 A9",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32309",
     "state": "FL",
     "text": "Ology Brewing - Billback",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.474943,
    27.93752 ]
   },
   "properties": {


     "address": "1501 West Swann Avenue",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33606",
     "state": "FL",
     "text": "On Swann",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.719257,
    28.249995 ]
   },
   "properties": {


     "address": "5738 Main St",
     "city": "New Port Richey",
     "country": "United States",
     "postalCode": "34652",
     "state": "FL",
     "text": "Ordinance One",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.468212,
    27.266141 ]
   },
   "properties": {


     "address": "5070 Clark Rd",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34233",
     "state": "FL",
     "text": "Origin Craft Beer & Pizza - Palmer Ranch",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.457853,
    27.390445 ]
   },
   "properties": {


     "address": "8193 Tourist Center Drive",
     "city": "Bradenton",
     "country": "United States",
     "postalCode": "34201",
     "state": "FL",
     "text": "Origin Craft Beer & Pizza - Utc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.532925,
    27.316723 ]
   },
   "properties": {


     "address": "1837 & 1839 Hillview Street",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34239",
     "state": "FL",
     "text": "Origin Craftbeer And Pizza Cafe",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.326803,
    28.56809 ]
   },
   "properties": {


     "address": "4899 New Broad St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32814",
     "state": "FL",
     "text": "Osprey Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.363784,
    28.627257 ]
   },
   "properties": {


     "address": "111 South Orlando Avesuite A & B",
     "city": "Maitland",
     "country": "United States",
     "postalCode": "32751",
     "state": "FL",
     "text": "Outpost Kitchen Bar & Provisions",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.290578,
    30.435179 ]
   },
   "properties": {


     "address": "603 West Gaines Streetsuite 7",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32304",
     "state": "FL",
     "text": "Oyster City Brewing - Tallahassee",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.662305,
    27.987884 ]
   },
   "properties": {


     "address": "3085 Jupiter Blvd Seunit 8 & 9",
     "city": "Palm Bay",
     "country": "United States",
     "postalCode": "32909",
     "state": "FL",
     "text": "Palm Bay Liquor Store",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.105998,
    26.145466 ]
   },
   "properties": {


     "address": "3109 East Sunrise Blvd",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33304",
     "state": "FL",
     "text": "Park & Ocean",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.279631,
    28.371618 ]
   },
   "properties": {


     "address": "6941 Lake Nona Blvdsuite 100",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32827",
     "state": "FL",
     "text": "Park Pizza & Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.071244,
    26.460425 ]
   },
   "properties": {


     "address": "32 Se 2Nd Avenue",
     "city": "Delray Beach",
     "country": "United States",
     "postalCode": "33444",
     "state": "FL",
     "text": "Park Tavern - Delray",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.347886,
    28.279378 ]
   },
   "properties": {


     "address": "2334 E Irlo Bronson Memorial Highway",
     "city": "Kissimmee",
     "country": "United States",
     "postalCode": "34744",
     "state": "FL",
     "text": "Partin Liquors - Kissimmee",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.718397,
    26.140114 ]
   },
   "properties": {


     "address": "4735 Santa Barbara Blvd #6",
     "city": "Naples",
     "country": "United States",
     "postalCode": "34104",
     "state": "FL",
     "text": "Peppers Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.2851,
    28.70423 ]
   },
   "properties": {


     "address": "\"855 E State Rd 434Units 1137",
     "city": " 1141",
     "country": " 1145 & 1149\"",
     "postalCode": "Winter Springs",
     "state": "United States",
     "text": "32708",
     "notice": "FL"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.283997,
    28.249141 ]
   },
   "properties": {


     "address": "918 New York Avea",
     "city": "St Cloud",
     "country": "United States",
     "postalCode": "34769",
     "state": "FL",
     "text": "Phyre Brewery & Tavern - Ny Ave",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.364614,
    28.563091 ]
   },
   "properties": {


     "address": "1326 N Mills Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Pig Floyd'S Urban Barbakoa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.184712,
    25.854457 ]
   },
   "properties": {


     "address": "8601 Biscayne Boulevard",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33138",
     "state": "FL",
     "text": "Pinch Restaurant",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.348117,
    30.126716 ]
   },
   "properties": {


     "address": "880 Hwy A1A Nsuite 7",
     "city": "Ponte Vedra Beach",
     "country": "United States",
     "postalCode": "32082",
     "state": "FL",
     "text": "Pinspiration (Jacksonville)",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.19803,
    25.799026 ]
   },
   "properties": {


     "address": "144 Nw 23 Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Pizza And Beer",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.335431,
    28.52385 ]
   },
   "properties": {


     "address": "3990 Curry Ford Rd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Pizza Bruno",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.089768,
    26.545749 ]
   },
   "properties": {


     "address": "1880 N. Congress Ave Unit 150",
     "city": "Boynton Beach",
     "country": "United States",
     "postalCode": "33426",
     "state": "FL",
     "text": "Pizza Rox",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.501665,
    28.384206 ]
   },
   "properties": {


     "address": "8562 Palm Pkwy",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32836",
     "state": "FL",
     "text": "Player 1 Video Game Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.364197,
    28.562014 ]
   },
   "properties": {


     "address": "1223 N Mills Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Pour Choice",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.447796,
    27.951052 ]
   },
   "properties": {


     "address": "1208 E Kennedy Blvdsuite 112",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33602",
     "state": "FL",
     "text": "Pour House At Grand Central Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.193613,
    25.864611 ]
   },
   "properties": {


     "address": "9722 Ne 2Nd Ave",
     "city": "Miami Shores Village",
     "country": "United States",
     "postalCode": "33138",
     "state": "FL",
     "text": "Proper Sausages",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.725591,
    28.354573 ]
   },
   "properties": {


     "address": "401 Delannoy Ave",
     "city": "Cocoa",
     "country": "United States",
     "postalCode": "32922",
     "state": "FL",
     "text": "Pub Americana - Cocoa Village",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.605658,
    28.078322 ]
   },
   "properties": {


     "address": "924 East New Haven Ave",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "Pub Americana - Melbourne",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.470169,
    28.432166 ]
   },
   "properties": {


     "address": "9101 International Dr Ste 1003",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32819",
     "state": "FL",
     "text": "Pub Orlando",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.578377,
    28.089187 ]
   },
   "properties": {


     "address": "8533 Gunn Hwy",
     "city": "Odessa",
     "country": "United States",
     "postalCode": "33556",
     "state": "FL",
     "text": "Pye Road Meadworks",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.460136,
    28.102412 ]
   },
   "properties": {


     "address": "16307 N Florida Ave",
     "city": "Lutz",
     "country": "United States",
     "postalCode": "33549",
     "state": "FL",
     "text": "Quality Foods Gourmet Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.672959,
    28.08858 ]
   },
   "properties": {


     "address": "1100 S Wickham Rd",
     "city": "West Melbourne",
     "country": "United States",
     "postalCode": "32904",
     "state": "FL",
     "text": "Quick Check Food Store",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.277489,
    30.445001 ]
   },
   "properties": {


     "address": "416 E Tennessee Street",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32301",
     "state": "FL",
     "text": "Quick N Save",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.119088,
    26.181694 ]
   },
   "properties": {


     "address": "4354 N Federal Highway",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33308",
     "state": "FL",
     "text": "Quvo Tacos & Craft Beer Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.415994,
    30.110634 ]
   },
   "properties": {


     "address": "295 Pine Lake Dr",
     "city": "Nocatee",
     "country": "United States",
     "postalCode": "32081",
     "state": "FL",
     "text": "Really Good Beer Stop",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.790162,
    28.011077 ]
   },
   "properties": {


     "address": "248 Scotland Street",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Reboot",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.347667,
    28.56758 ]
   },
   "properties": {


     "address": "2810 Corrine Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Redlight Redlight",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.622218,
    28.516939 ]
   },
   "properties": {


     "address": "16100 Marsh Rdsuite 201",
     "city": "Winter Garden",
     "country": "United States",
     "postalCode": "34787",
     "state": "FL",
     "text": "Regency Wine & Liquor",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.378717,
    28.555084 ]
   },
   "properties": {


     "address": "821 N Orange Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "Reyes Mezcalenn",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.269544,
    30.467202 ]
   },
   "properties": {


     "address": "1950 Thomasville Rdste G",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32303",
     "state": "FL",
     "text": "Riccardos Restaurant",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.615067,
    28.407379 ]
   },
   "properties": {


     "address": "523 Glen Cheek Dr",
     "city": "Port Canaveral",
     "country": "United States",
     "postalCode": "32920",
     "state": "FL",
     "text": "Rising Tide Tap & Table",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.157475,
    26.113779 ]
   },
   "properties": {


     "address": "608 Sw 12 Ave",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "33317",
     "state": "FL",
     "text": "Riverside Market - Ft Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.238502,
    26.1233 ]
   },
   "properties": {


     "address": "6900 Cypress Road",
     "city": "Plantation",
     "country": "United States",
     "postalCode": "33317",
     "state": "FL",
     "text": "Riverside Market - Plantation",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.309184,
    28.463773 ]
   },
   "properties": {


     "address": "6897 S Semoran Blvd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32822",
     "state": "FL",
     "text": "Rock & Brews - Orlando Airport",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.389883,
    28.194073 ]
   },
   "properties": {


     "address": "26000 State Road 56",
     "city": "Lutz",
     "country": "United States",
     "postalCode": "33559",
     "state": "FL",
     "text": "Rock & Brews - Wesley Chapel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.71518,
    28.321834 ]
   },
   "properties": {


     "address": "2153 Us Hwy #1",
     "city": "Rockledge",
     "country": "United States",
     "postalCode": "32955",
     "state": "FL",
     "text": "Rockledge Gardens",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.646893,
    27.797936 ]
   },
   "properties": {


     "address": "2842 9Th St. North",
     "city": "St Petesburg",
     "country": "United States",
     "postalCode": "33704",
     "state": "FL",
     "text": "Rollin Oats Market - St Pete",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.492509,
    27.952959 ]
   },
   "properties": {


     "address": "1021 N Macdill Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33607",
     "state": "FL",
     "text": "Rollin Oats Market - Tampa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.343972,
    28.52352 ]
   },
   "properties": {


     "address": "3076 Curry Ford Rd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Roque Pub",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.54206,
    28.54848 ]
   },
   "properties": {


     "address": "1568 Maguire Rd",
     "city": "Ocoee",
     "country": "United States",
     "postalCode": "34761",
     "state": "FL",
     "text": "Rusteak - Ocoee",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.349971,
    25.897298 ]
   },
   "properties": {


     "address": "3300 West 84 Street Unit 17",
     "city": "Hialeah",
     "country": "United States",
     "postalCode": "32018",
     "state": "FL",
     "text": "Safe House Smokes",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.571053,
    28.090675 ]
   },
   "properties": {


     "address": "145 Palmbay Rd Nesuite #118-119",
     "city": "West Melbourne",
     "country": "United States",
     "postalCode": "32904",
     "state": "FL",
     "text": "Sam'S Liquor",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.242844,
    25.727702 ]
   },
   "properties": {


     "address": "3426 Main Highway",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33133",
     "state": "FL",
     "text": "Sandbar Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.350467,
    28.545864 ]
   },
   "properties": {


     "address": "2432 E Robinson St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Sandwich Bar - The Nook",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.636393,
    27.771495 ]
   },
   "properties": {


     "address": "241 Central Ave",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "Sauvignon",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.74694,
    27.734873 ]
   },
   "properties": {


     "address": "6390 Gulf Blvd",
     "city": "St. Pete Beach",
     "country": "United States",
     "postalCode": "33706",
     "state": "FL",
     "text": "Sea Grapes",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.462471,
    28.408028 ]
   },
   "properties": {


     "address": "7007 Sea World Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32821",
     "state": "FL",
     "text": "Sea World",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.75282,
    26.274604 ]
   },
   "properties": {


     "address": "4835 Immokalee Rd",
     "city": "Naples",
     "country": "United States",
     "postalCode": "34110",
     "state": "FL",
     "text": "Seed To Table",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.785678,
    28.012808 ]
   },
   "properties": {


     "address": "500 Main St",
     "city": "Dunedin",
     "country": "United States",
     "postalCode": "34698",
     "state": "FL",
     "text": "Seeds",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.64539,
    28.80054 ]
   },
   "properties": {


     "address": "144 W 5Th Ave",
     "city": "Mt Dora",
     "country": "United States",
     "postalCode": "32757",
     "state": "FL",
     "text": "Serendipity Brews",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -84.239225,
    30.427566 ]
   },
   "properties": {


     "address": "2475 Apalachee Parkway Suite 102",
     "city": "Tallahassee",
     "country": "United States",
     "postalCode": "32301",
     "state": "FL",
     "text": "Seventh Hill Taproom",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.193232,
    25.764641 ]
   },
   "properties": {


     "address": "1001 S Miami Avenueaka 1095 S Miami Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33130",
     "state": "FL",
     "text": "Sexy Fish",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.211576,
    28.596613 ]
   },
   "properties": {


     "address": "12046 Collegiate Way",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32826",
     "state": "FL",
     "text": "Shamrock Beverage/The Public House",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.349174,
    25.811499 ]
   },
   "properties": {


     "address": "9420 Nw 41 St",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33178",
     "state": "FL",
     "text": "Shoma Bazaar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.593043,
    28.33592 ]
   },
   "properties": {


     "address": "7640 West Irlo Bronson Memorial Hwy",
     "city": "Kissimmee",
     "country": "United States",
     "postalCode": "34747",
     "state": "FL",
     "text": "Sickies Garage Burgers And Brews 1",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.303597,
    29.027944 ]
   },
   "properties": {


     "address": "100 South Woodland Blvd",
     "city": "Deland",
     "country": "United States",
     "postalCode": "32720",
     "state": "FL",
     "text": "Sidecar Bar And Home Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.460129,
    28.491633 ]
   },
   "properties": {


     "address": "4892 S Kirkman Rd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32811",
     "state": "FL",
     "text": "Sloppy Taco Palace",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.45968,
    28.004847 ]
   },
   "properties": {


     "address": "6310 N Florida Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33604",
     "state": "FL",
     "text": "Social House - Tampa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.678396,
    28.454196 ]
   },
   "properties": {


     "address": "16651 Schofield Rd",
     "city": "Clermont",
     "country": "United States",
     "postalCode": "34714",
     "state": "FL",
     "text": "Southern Hill Farms Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.40268,
    30.287006 ]
   },
   "properties": {


     "address": "1312 Beach Blvd",
     "city": "Jacksonville Beach",
     "country": "United States",
     "postalCode": "32250",
     "state": "FL",
     "text": "Southern Swells Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.424901,
    25.657007 ]
   },
   "properties": {


     "address": "14241 Sw 120Th St Ste 109",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33186",
     "state": "FL",
     "text": "Spanish Marie",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.690429,
    28.123493 ]
   },
   "properties": {


     "address": "3945 W Eau Gallie Blvd",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32934",
     "state": "FL",
     "text": "Spirited Spin Liquor Shop",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.626817,
    28.034736 ]
   },
   "properties": {


     "address": "1516 Palm Bay Road Ne",
     "city": "Palm Bay",
     "country": "United States",
     "postalCode": "32905",
     "state": "FL",
     "text": "Spirits2U",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.380767,
    25.732247 ]
   },
   "properties": {


     "address": "11481 Sw 40 St # 80",
     "city": "Md Miami",
     "country": "United States",
     "postalCode": "33165",
     "state": "FL",
     "text": "Sports Grill - Miami",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.328087,
    25.915203 ]
   },
   "properties": {


     "address": "15462 Nw 77 Court #230 & 240",
     "city": "Miami Lakes",
     "country": "United States",
     "postalCode": "33016",
     "state": "FL",
     "text": "Sports Grill - Miami Lakes",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.351028,
    28.545843 ]
   },
   "properties": {


     "address": "2414 E Robinson St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Sportstown Billiards",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.400063,
    25.684301 ]
   },
   "properties": {


     "address": "12690 Sw 88Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33186",
     "state": "FL",
     "text": "Sprouts Farmers Market - Miami",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.392331,
    27.315188 ]
   },
   "properties": {


     "address": "1481 Nw St. Lucie West Blvd",
     "city": "Port St Lucie",
     "country": "United States",
     "postalCode": "34986",
     "state": "FL",
     "text": "St Lucie Wine & Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.277486,
    28.246272 ]
   },
   "properties": {


     "address": "718 13Th Street",
     "city": "St Cloud",
     "country": "United States",
     "postalCode": "34769",
     "state": "FL",
     "text": "St. Cloud Levee Liquor & Gas",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.842594,
    27.895925 ]
   },
   "properties": {


     "address": "165 South Central Avenue",
     "city": "Bartow",
     "country": "United States",
     "postalCode": "33830",
     "state": "FL",
     "text": "Stanford Wines",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.265887,
    26.660081 ]
   },
   "properties": {


     "address": "13860 Wellington Traceunits 27-28-29",
     "city": "Wellington",
     "country": "United States",
     "postalCode": "33414",
     "state": "FL",
     "text": "Star Liquors #4",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.261508,
    25.836909 ]
   },
   "properties": {


     "address": "1000 E 16 Street",
     "city": "Hialeah",
     "country": "United States",
     "postalCode": "33010",
     "state": "FL",
     "text": "Stephen'S Delicatessen/ La Cocina",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.913299,
    26.54641 ]
   },
   "properties": {


     "address": "13451 Mcgregor Blvd #5-9",
     "city": "Fort Myers",
     "country": "United States",
     "postalCode": "33919",
     "state": "FL",
     "text": "Stillwater Grille",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.633023,
    27.77376 ]
   },
   "properties": {


     "address": "224 Beach Drive Ne",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "Stillwaters Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.869425,
    26.549035 ]
   },
   "properties": {


     "address": "13499 S Cleveland Ave Suite 245",
     "city": "Fort Myers",
     "country": "United States",
     "postalCode": "33907",
     "state": "FL",
     "text": "Stogie Pairing Cigar Lounge",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.056863,
    26.630115 ]
   },
   "properties": {


     "address": "1201 Us Hwy 1Suite 15",
     "city": "North Palm Beach",
     "country": "United States",
     "postalCode": "33458",
     "state": "FL",
     "text": "Stormhouse Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.439344,
    25.698731 ]
   },
   "properties": {


     "address": "15220 Sw 72Nd Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33193",
     "state": "FL",
     "text": "Strange Beast Brewpub & Pizzeria",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.585262,
    28.018339 ]
   },
   "properties": {


     "address": "2190 Port Malabar Blvd Ne",
     "city": "Palm Bay",
     "country": "United States",
     "postalCode": "32905",
     "state": "FL",
     "text": "Sunrise Food Mart #53",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.606024,
    28.377516 ]
   },
   "properties": {


     "address": "6615 N Atlantic Ave Ste B",
     "city": "Cape Canaveral",
     "country": "United States",
     "postalCode": "32920",
     "state": "FL",
     "text": "Sunseed Food Co-Op",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.705811,
    28.413307 ]
   },
   "properties": {


     "address": "3120 N Courtenay Pkwy",
     "city": "Merritt Island",
     "country": "United States",
     "postalCode": "32953",
     "state": "FL",
     "text": "Sunshine Food Mart",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.66826,
    28.37182 ]
   },
   "properties": {


     "address": "844 N Banana River Dr",
     "city": "Merritt Island",
     "country": "United States",
     "postalCode": "32952",
     "state": "FL",
     "text": "Sunshine Food Mart #844 (Chevron)",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.809535,
    28.530726 ]
   },
   "properties": {


     "address": "700 Columbia Blvd",
     "city": "Titusville",
     "country": "United States",
     "postalCode": "32780",
     "state": "FL",
     "text": "Sunshine Food Mart 122",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.200179,
    25.800907 ]
   },
   "properties": {


     "address": "251 Nw 25 Street",
     "city": "Miamifl",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Sunshine Kitchens - Kyu",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.331577,
    25.807214 ]
   },
   "properties": {


     "address": "3450 Nw 83Rd Avesuite 148",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33122",
     "state": "FL",
     "text": "Suviche Doral",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.194669,
    25.802913 ]
   },
   "properties": {


     "address": "2751 N Miami Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Suviche Wynwood",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.922891,
    28.008716 ]
   },
   "properties": {


     "address": "2972 Lakeland Highlands Rd",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33803",
     "state": "FL",
     "text": "Swan Brewing - Highlands",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.958049,
    28.046153 ]
   },
   "properties": {


     "address": "115 W Pine Street",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33815",
     "state": "FL",
     "text": "Swan Brewing - Pine Street",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.357777,
    28.592511 ]
   },
   "properties": {


     "address": "669 N Orange Ave",
     "city": "Winter Park",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "Swine & Sons",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.360509,
    28.512927 ]
   },
   "properties": {


     "address": "1508 E Michigan St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Swirlery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.385971,
    25.671307 ]
   },
   "properties": {


     "address": "11790 Sw 104 Streetste B1 - 101",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33186",
     "state": "FL",
     "text": "Tacos & Tattoos",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.35105,
    28.52438 ]
   },
   "properties": {


     "address": "2411 Curry Ford Rd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Tamale & Company Hourglass",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.441434,
    27.961368 ]
   },
   "properties": {


     "address": "1600 E 8Th Avesuite A123",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33605",
     "state": "FL",
     "text": "Tampa Bay Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.384601,
    25.688695 ]
   },
   "properties": {


     "address": "11735 Sherry Lane",
     "city": "Kendall",
     "country": "United States",
     "postalCode": "33183",
     "state": "FL",
     "text": "Tap 42 - Kendall",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.661019,
    27.771232 ]
   },
   "properties": {


     "address": "2061 Central Ave",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33713",
     "state": "FL",
     "text": "Taphouse 61",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.441434,
    27.961368 ]
   },
   "properties": {


     "address": "1600 E 8Th Avesuite E113",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33605",
     "state": "FL",
     "text": "Tappin Beer",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.130567,
    26.174106 ]
   },
   "properties": {


     "address": "1242 Ne 38 Street",
     "city": "Oakland Park",
     "country": "United States",
     "postalCode": "33334",
     "state": "FL",
     "text": "Tenth Level Tavern",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.223148,
    25.773498 ]
   },
   "properties": {


     "address": "1701 West Flagler Street Suite 101",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33135",
     "state": "FL",
     "text": "Thank You Miami",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.635039,
    27.773965 ]
   },
   "properties": {


     "address": "111 2Nd Avenue Nesuite 104",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "The Ale And The Witch",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.639874,
    27.779863 ]
   },
   "properties": {


     "address": "465 7Th Ave North",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33701",
     "state": "FL",
     "text": "The Bier Boutique",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.657416,
    27.770762 ]
   },
   "properties": {


     "address": "1752 Central Avenue",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33712",
     "state": "FL",
     "text": "The Burg Bar & Grill",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.302708,
    28.698997 ]
   },
   "properties": {


     "address": "278 East State Road 434",
     "city": "Winter Springs",
     "country": "United States",
     "postalCode": "32708",
     "state": "FL",
     "text": "The Can & Bottle Beer Shop",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.352858,
    28.523756 ]
   },
   "properties": {


     "address": "2230 Curry Ford Rd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "The Commission",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.191532,
    29.571385 ]
   },
   "properties": {


     "address": "101 Palm Harbor Pkwy Unit B121",
     "city": "Palm Coast",
     "country": "United States",
     "postalCode": "32137",
     "state": "FL",
     "text": "The Cork And Pint",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.807556,
    28.612232 ]
   },
   "properties": {


     "address": "330 S Washington Ave",
     "city": "Titusville",
     "country": "United States",
     "postalCode": "32796",
     "state": "FL",
     "text": "The Daley Trade Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.664663,
    27.770808 ]
   },
   "properties": {


     "address": "2300 Central Ave",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33712",
     "state": "FL",
     "text": "The Dog Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.335511,
    25.820026 ]
   },
   "properties": {


     "address": "8455 Nw 53 Street Ste G105 -G106",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "The Doral Yard",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.335511,
    25.820026 ]
   },
   "properties": {


     "address": "8455 W 53 Street Ste G105 -G106 And 5307 Paseo Blvd",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "The Doral Yard / Barbakoa By Finka",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.461147,
    27.96746 ]
   },
   "properties": {


     "address": "2612 N Tampa St",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33602",
     "state": "FL",
     "text": "The Heights Shuffle",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.269114,
    27.246472 ]
   },
   "properties": {


     "address": "\"3311",
     "city": " 3317",
     "country": " 3323 Nw Main Ave\"",
     "postalCode": "Jensen Beach",
     "state": "United States",
     "text": "34957",
     "notice": "FL"
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.283363,
    28.248268 ]
   },
   "properties": {


     "address": "1029 New York Ave",
     "city": "St Cloud",
     "country": "United States",
     "postalCode": "34769",
     "state": "FL",
     "text": "The Hunter Arms Hotel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.267274,
    28.811865 ]
   },
   "properties": {


     "address": "116 E 1St St",
     "city": "Sanford",
     "country": "United States",
     "postalCode": "32771",
     "state": "FL",
     "text": "The Imperial - Sanford",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.950544,
    28.046111 ]
   },
   "properties": {


     "address": "640 E Main Street",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33807",
     "state": "FL",
     "text": "The Joinery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.602212,
    28.079519 ]
   },
   "properties": {


     "address": "1218 E New Haven Ave",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32901",
     "state": "FL",
     "text": "The Mansion",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.343803,
    28.568257 ]
   },
   "properties": {


     "address": "3201 Corrine Drivesuite 109",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "The Neighbors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.734492,
    28.536482 ]
   },
   "properties": {


     "address": "2423 S Hwy 27",
     "city": "Clermont",
     "country": "United States",
     "postalCode": "34711",
     "state": "FL",
     "text": "The New Wine Regions Discount Wines",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.303236,
    29.029705 ]
   },
   "properties": {


     "address": "145 N Woodland Blvd",
     "city": "Deland",
     "country": "United States",
     "postalCode": "32720",
     "state": "FL",
     "text": "The Parched Oak",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.458591,
    27.946178 ]
   },
   "properties": {


     "address": "200 North Tampa Stsuite G118",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33602",
     "state": "FL",
     "text": "The Pint And Brew - Downtown Tampa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.029014,
    29.230357 ]
   },
   "properties": {


     "address": "101 2Nd Street Unit 104",
     "city": "Holly Hill",
     "country": "United States",
     "postalCode": "32117",
     "state": "FL",
     "text": "The Red Pig Brewpub",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.44225,
    27.960437 ]
   },
   "properties": {


     "address": "1518 East 7Th Avenue",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33605",
     "state": "FL",
     "text": "The Reservoir Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.429297,
    28.405282 ]
   },
   "properties": {


     "address": "4012 Central Fl Pkwy",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32837",
     "state": "FL",
     "text": "The Ritz-Carlton Orlando Grande Lakes",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.295172,
    27.892949 ]
   },
   "properties": {


     "address": "827 W Bloomingdale Ave",
     "city": "Brandon",
     "country": "United States",
     "postalCode": "33511",
     "state": "FL",
     "text": "The Stein & Vine",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.364199,
    28.555468 ]
   },
   "properties": {


     "address": "807 N Mills Ave",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "The Strand",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.370104,
    28.540842 ]
   },
   "properties": {


     "address": "100 S Eola Dr Ste 103",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "The Stubborn Mule",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.016508,
    28.863207 ]
   },
   "properties": {


     "address": "2518 Burnsed Blvd.Unit 417",
     "city": "The Villages",
     "country": "United States",
     "postalCode": "32163",
     "state": "FL",
     "text": "The Sunny Pint",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.315596,
    25.820071 ]
   },
   "properties": {


     "address": "5100 Nw 72 Avenue",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "The Tank Brewing Co.",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.268804,
    28.811574 ]
   },
   "properties": {


     "address": "125 West First St",
     "city": "Sanford",
     "country": "United States",
     "postalCode": "32771",
     "state": "FL",
     "text": "The Tennessee Truffle",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.610727,
    28.318669 ]
   },
   "properties": {


     "address": "249 Minutemen Causeway Suite. R.",
     "city": "Cocoa Beach",
     "country": "United States",
     "postalCode": "32931",
     "state": "FL",
     "text": "The Tiny Turtle",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.123941,
    28.01437 ]
   },
   "properties": {


     "address": "115 S Evers St",
     "city": "Plant City",
     "country": "United States",
     "postalCode": "33563",
     "state": "FL",
     "text": "The Tipsy Bookworm",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.671043,
    27.793195 ]
   },
   "properties": {


     "address": "2329 28Th Street North",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33713",
     "state": "FL",
     "text": "The Vortex Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.375458,
    28.535624 ]
   },
   "properties": {


     "address": "211 N Lucerne Circle East",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "The Wellborn Hotel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.738625,
    27.770543 ]
   },
   "properties": {


     "address": "7220 Central Ave",
     "city": "St Petersburg",
     "country": "United States",
     "postalCode": "33707",
     "state": "FL",
     "text": "The Wheelhouse - St Pete",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.611959,
    28.191622 ]
   },
   "properties": {


     "address": "12351 St Rd 54 Unit 5",
     "city": "Odessa",
     "country": "United States",
     "postalCode": "33556",
     "state": "FL",
     "text": "The Wicked Pour",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.954538,
    28.05217 ]
   },
   "properties": {


     "address": "830 N Massachusetts Avesuite 204",
     "city": "Lakeland",
     "country": "United States",
     "postalCode": "33801",
     "state": "FL",
     "text": "The Yard On Mass",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.814724,
    28.558038 ]
   },
   "properties": {


     "address": "1000 Cheney Hwy",
     "city": "Titusville",
     "country": "United States",
     "postalCode": "32780",
     "state": "FL",
     "text": "Third Culture Kitchen",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.369868,
    28.564198 ]
   },
   "properties": {


     "address": "601 Virginia Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Thirsty Topher",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.510132,
    28.671681 ]
   },
   "properties": {


     "address": "48 E 5Th St",
     "city": "Apopka",
     "country": "United States",
     "postalCode": "32703",
     "state": "FL",
     "text": "Three Odd Guys Brewing",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.132725,
    25.789705 ]
   },
   "properties": {


     "address": "1601 Drexel Ave",
     "city": "Miami Beach",
     "country": "United States",
     "postalCode": "33139",
     "state": "FL",
     "text": "Time Out Market (Miami)",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.371219,
    28.513275 ]
   },
   "properties": {


     "address": "419 E Michigan St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32806",
     "state": "FL",
     "text": "Tin & Taco #2 - Michigan",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.379651,
    28.542517 ]
   },
   "properties": {


     "address": "40 W Washington St",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "Tin And Taco - Downtown",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.258503,
    25.759192 ]
   },
   "properties": {


     "address": "1315 Ponce De Leon Blvd",
     "city": "Coral Gables",
     "country": "United States",
     "postalCode": "33134",
     "state": "FL",
     "text": "Tinta Y Cafe - Coral Gables",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.193675,
    25.865638 ]
   },
   "properties": {


     "address": "9840 Ne 2Ave",
     "city": "Miami Shores",
     "country": "United States",
     "postalCode": "33138",
     "state": "FL",
     "text": "Tinta Y Cafe Miami Shores",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.424017,
    29.630083 ]
   },
   "properties": {


     "address": "2440 Sw 76Th Streetsuite 110",
     "city": "Gainesville",
     "country": "United States",
     "postalCode": "32608",
     "state": "FL",
     "text": "Tipple'S Brews Of Gainesville",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.506318,
    27.95826 ]
   },
   "properties": {


     "address": "1720 North Dale Mabry Highway",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33607",
     "state": "FL",
     "text": "Total Wine & More 901 - Tampa",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.093247,
    26.840401 ]
   },
   "properties": {


     "address": "11221 Legacy Avenue",
     "city": "Palm Beach Gardens",
     "country": "United States",
     "postalCode": "33410",
     "state": "FL",
     "text": "Total Wine & More 903 - Palm Beach Garde",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.122952,
    26.363176 ]
   },
   "properties": {


     "address": "5050 Town Center Circlesuite 200",
     "city": "Boca Raton",
     "country": "United States",
     "postalCode": "33432",
     "state": "FL",
     "text": "Total Wine & More 905 - Boca Raton",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.090498,
    26.535966 ]
   },
   "properties": {


     "address": "850 North Congress Ave",
     "city": "Boynton Beach",
     "country": "United States",
     "postalCode": "33426",
     "state": "FL",
     "text": "Total Wine & More 906 - Boynton Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.348494,
    28.552764 ]
   },
   "properties": {


     "address": "2712 E Colonial Dr",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Total Wine & More 909 - Colonial",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.733082,
    28.021172 ]
   },
   "properties": {


     "address": "2528 State Road 580",
     "city": "Clearwater",
     "country": "United States",
     "postalCode": "33761",
     "state": "FL",
     "text": "Total Wine & More 910 - Clearwater",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.755571,
    27.81657 ]
   },
   "properties": {


     "address": "4880 Park Street North",
     "city": "Seminole",
     "country": "United States",
     "postalCode": "33709",
     "state": "FL",
     "text": "Total Wine & More 913 - St Petersburg",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.454014,
    27.389924 ]
   },
   "properties": {


     "address": "8539 Cooper Creek Blvd",
     "city": "University Park",
     "country": "United States",
     "postalCode": "34201",
     "state": "FL",
     "text": "Total Wine & More 914 - Sarasota",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.270326,
    27.235914 ]
   },
   "properties": {


     "address": "2550 Nw Federal Hwy",
     "city": "Stuart",
     "country": "United States",
     "postalCode": "34994",
     "state": "FL",
     "text": "Total Wine & More 916 - Stuart",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.25144,
    26.645659 ]
   },
   "properties": {


     "address": "960 South Hw 7",
     "city": "Village Of Wellington",
     "country": "United States",
     "postalCode": "33414",
     "state": "FL",
     "text": "Total Wine & More 917 - Wellington",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.427769,
    28.496392 ]
   },
   "properties": {


     "address": "4625 Millenia Plaza Way",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32839",
     "state": "FL",
     "text": "Total Wine & More 920 - Millenia",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.727878,
    28.238668 ]
   },
   "properties": {


     "address": "2302 Harnett Dr",
     "city": "Viera",
     "country": "United States",
     "postalCode": "32940",
     "state": "FL",
     "text": "Total Wine & More 921 - Viera",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.080519,
    29.179636 ]
   },
   "properties": {


     "address": "2500 W International Speedway Blvd #800",
     "city": "Daytona Beach",
     "country": "United States",
     "postalCode": "32114",
     "state": "FL",
     "text": "Total Wine & More 923 - Daytona",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.496648,
    27.230754 ]
   },
   "properties": {


     "address": "8280 S Tamiami Trail",
     "city": "Sarasota",
     "country": "United States",
     "postalCode": "34231",
     "state": "FL",
     "text": "Total Wine & More 924 - South Sarasota",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.384888,
    28.66127 ]
   },
   "properties": {


     "address": "160 E Altamonte Dr",
     "city": "Altamonte Springs",
     "country": "United States",
     "postalCode": "32701",
     "state": "FL",
     "text": "Total Wine & More 925 - Altamonte",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.24979,
    26.262834 ]
   },
   "properties": {


     "address": "2564 N University Dr",
     "city": "Coral Springs",
     "country": "United States",
     "postalCode": "33065",
     "state": "FL",
     "text": "Total Wine & More 927 - Coral Springs",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.325677,
    27.921483 ]
   },
   "properties": {


     "address": "11211 Causeway Blvd",
     "city": "Brandon",
     "country": "United States",
     "postalCode": "33511",
     "state": "FL",
     "text": "Total Wine & More 928 - Brandon",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.367442,
    25.789184 ]
   },
   "properties": {


     "address": "1635 Nw 107 Ave",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33172",
     "state": "FL",
     "text": "Total Wine & More 932 - Doral",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.927081,
    28.931841 ]
   },
   "properties": {


     "address": "641 N Highway 27-441",
     "city": "Lady Lake",
     "country": "United States",
     "postalCode": "32159",
     "state": "FL",
     "text": "Total Wine & More 933 - Lady Lake",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.39555,
    28.195538 ]
   },
   "properties": {


     "address": "25535 Sierra Center Blvd",
     "city": "Lutz",
     "country": "United States",
     "postalCode": "33559",
     "state": "FL",
     "text": "Total Wine & More 934 - Wesley Chapel",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -87.209439,
    30.48138 ]
   },
   "properties": {


     "address": "1660 Airport Blvd Unit 145",
     "city": "Pensacola",
     "country": "United States",
     "postalCode": "32504",
     "state": "FL",
     "text": "Total Wine & More 937 - Pensacola",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.62709,
    28.130241 ]
   },
   "properties": {


     "address": "563 Eau Gallie Blvd",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32935",
     "state": "FL",
     "text": "Traditionals Cuts Shaves And Brews",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.367013,
    25.798786 ]
   },
   "properties": {


     "address": "2685 Nw 105 Avenue",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33172",
     "state": "FL",
     "text": "Tripping Animals Brewing - Billback",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.367013,
    25.798786 ]
   },
   "properties": {


     "address": "2685 Nw 105 Avenue",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33172",
     "state": "FL",
     "text": "Tripping Animals Brewing - Billback",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.608063,
    28.306067 ]
   },
   "properties": {


     "address": "1 & 7 S Atlantic Avenue",
     "city": "Cocoa Beach",
     "country": "United States",
     "postalCode": "32931",
     "state": "FL",
     "text": "Tropic'S Cocktail Bar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.347567,
    25.812349 ]
   },
   "properties": {


     "address": "4400 Nw 87 Avenue",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33178",
     "state": "FL",
     "text": "Trump Endeavor 12 Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.153195,
    26.302479 ]
   },
   "properties": {


     "address": "1101 South Powerline Roadsuite 102",
     "city": "Deerfield Beach",
     "country": "United States",
     "postalCode": "33442",
     "state": "FL",
     "text": "Tucker Dukes Lunch Box & Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.27038,
    28.810496 ]
   },
   "properties": {


     "address": "200 S Myrtle Avenue",
     "city": "Sanford",
     "country": "United States",
     "postalCode": "32771",
     "state": "FL",
     "text": "Tuffy'S Bottle Shop & Lounge",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.508881,
    27.990254 ]
   },
   "properties": {


     "address": "4813 N Grady Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33614",
     "state": "FL",
     "text": "Two Shepherds Taproom",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.259696,
    25.834868 ]
   },
   "properties": {


     "address": "1395 E 11Th Ave",
     "city": "Hialeah",
     "country": "United States",
     "postalCode": "33010",
     "state": "FL",
     "text": "Unbranded Brewing Company",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.220479,
    25.765845 ]
   },
   "properties": {


     "address": "1547 Sw 8Th St",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33135",
     "state": "FL",
     "text": "Union Beer Store",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.316842,
    28.790483 ]
   },
   "properties": {


     "address": "300 Upsala Road",
     "city": "Sanford",
     "country": "United States",
     "postalCode": "32771",
     "state": "FL",
     "text": "Upsala Grocery",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.668777,
    27.771292 ]
   },
   "properties": {


     "address": "2601 Central Ave",
     "city": "St. Petersburg",
     "country": "United States",
     "postalCode": "33713",
     "state": "FL",
     "text": "Urban Brew & Bbq",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.533056,
    28.127532 ]
   },
   "properties": {


     "address": "5524 Van Dyke Rd",
     "city": "Lutz",
     "country": "United States",
     "postalCode": "33549",
     "state": "FL",
     "text": "Van Dyke Shell",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.443942,
    27.093069 ]
   },
   "properties": {


     "address": "421 S Tamiami Trail",
     "city": "Venice",
     "country": "United States",
     "postalCode": "34285",
     "state": "FL",
     "text": "Venice Fine Wine And Spirits",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.299113,
    28.509949 ]
   },
   "properties": {


     "address": "3201 Woodgate Blvd",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32822",
     "state": "FL",
     "text": "Ventura Country Club Community",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.469738,
    25.474018 ]
   },
   "properties": {


     "address": "601 Ne 2Nd Road",
     "city": "Homestead",
     "country": "United States",
     "postalCode": "330306177",
     "state": "FL",
     "text": "Veterans Of Foreign Wars",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.724782,
    28.352795 ]
   },
   "properties": {


     "address": "11 Riverside Drivesuite 110",
     "city": "Cocoa",
     "country": "United States",
     "postalCode": "32922",
     "state": "FL",
     "text": "Villa Palma At The Village",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.724441,
    28.355087 ]
   },
   "properties": {


     "address": "4 Harrison St",
     "city": "Cocoa",
     "country": "United States",
     "postalCode": "32922",
     "state": "FL",
     "text": "Village Idiot Pub",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.301221,
    28.426935 ]
   },
   "properties": {


     "address": "9602 Jeff Fuqua Blvdsuite 400",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32827",
     "state": "FL",
     "text": "Vino Volo",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.533646,
    28.353022 ]
   },
   "properties": {


     "address": "14200 Bonnet Creek Resort Ln",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32821",
     "state": "FL",
     "text": "Waldorf Astoria Bonnet Creek",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.673058,
    28.119627 ]
   },
   "properties": {


     "address": "830 N Wickham Rd Suite 10",
     "city": "Melbourne",
     "country": "United States",
     "postalCode": "32935",
     "state": "FL",
     "text": "Wassi'S Meat Market",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.445552,
    25.68399 ]
   },
   "properties": {


     "address": "15698 S W 88 Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33196",
     "state": "FL",
     "text": "West Dade Chevron #1",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.350608,
    28.538856 ]
   },
   "properties": {


     "address": "2425 E South Street",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Whippoorwill Beer House And Package",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.117755,
    26.153537 ]
   },
   "properties": {


     "address": "2000 N Federal Hwy",
     "city": "Ft Lauderdale",
     "country": "United States",
     "postalCode": "",
     "state": "FL",
     "text": "Whole Foods Market #10117",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.092839,
    26.849212 ]
   },
   "properties": {


     "address": "11701 Lake Victoria Garden Avenuesuite 5",
     "city": "Palm Beach Gardens",
     "country": "United States",
     "postalCode": "33410",
     "state": "FL",
     "text": "Whole Foods Market #10188",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.285569,
    25.709481 ]
   },
   "properties": {


     "address": "6701 Red Road",
     "city": "Coral Gables",
     "country": "United States",
     "postalCode": "33143",
     "state": "FL",
     "text": "Whole Foods Market #10190",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.346544,
    26.007661 ]
   },
   "properties": {


     "address": "14956 Pines Boulevard",
     "city": "Pembroke Pines",
     "country": "United States",
     "postalCode": "33027",
     "state": "FL",
     "text": "Whole Foods Market #10193",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.206289,
    26.641288 ]
   },
   "properties": {


     "address": "2635 State Road 7",
     "city": "Wellington",
     "country": "United States",
     "postalCode": "33414",
     "state": "FL",
     "text": "Whole Foods Market #10195",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.323429,
    25.673253 ]
   },
   "properties": {


     "address": "7930 Sw 104Th Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33156",
     "state": "FL",
     "text": "Whole Foods Market #10274",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.141132,
    25.780965 ]
   },
   "properties": {


     "address": "1020 Alton Road",
     "city": "Miami Beach",
     "country": "United States",
     "postalCode": "33139",
     "state": "FL",
     "text": "Whole Foods Market #10285",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.504122,
    28.093061 ]
   },
   "properties": {


     "address": "3802 Northdale Boulevard",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33624",
     "state": "FL",
     "text": "Whole Foods Market #10339",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.099637,
    26.261333 ]
   },
   "properties": {


     "address": "2411 North Federal Hwy",
     "city": "Pompano Beach",
     "country": "United States",
     "postalCode": "33062",
     "state": "FL",
     "text": "Whole Foods Market #10352",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.165293,
    25.887979 ]
   },
   "properties": {


     "address": "12150 Biscayne Boulevard",
     "city": "North Miami",
     "country": "United States",
     "postalCode": "33181",
     "state": "FL",
     "text": "Whole Foods Market #10477",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.089309,
    26.720695 ]
   },
   "properties": {


     "address": "1845 Palm Beach Lakes Boulevardbuilding C",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33401",
     "state": "FL",
     "text": "Whole Foods Market #10529",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.137675,
    26.100749 ]
   },
   "properties": {


     "address": "501 Se. 17Th Street",
     "city": "Ft. Lauderdale",
     "country": "United States",
     "postalCode": "33316",
     "state": "FL",
     "text": "Whole Foods Market #10715",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.285569,
    25.709481 ]
   },
   "properties": {


     "address": "6701 Red Road",
     "city": "Coral Gables",
     "country": "United States",
     "postalCode": "33143",
     "state": "FL",
     "text": "Whole Foods Market #10190",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.137675,
    26.100749 ]
   },
   "properties": {


     "address": "501 Se 17 Street",
     "city": "Fort Lauderdale",
     "country": "United States",
     "postalCode": "33316",
     "state": "FL",
     "text": "Whole Foods Market Ffh Lauderdale",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.504502,
    27.952742 ]
   },
   "properties": {


     "address": "3740 Midtown Drive",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33607",
     "state": "FL",
     "text": "Whole Foods Market Midtown Tampa - 10723",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.092279,
    26.844638 ]
   },
   "properties": {


     "address": "11701 Lake Victoria Gardens Blvd",
     "city": "Palm Beach Gardens",
     "country": "United States",
     "postalCode": "33410",
     "state": "FL",
     "text": "Whole Foods Market Palm Beach Gardens",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.346544,
    26.007661 ]
   },
   "properties": {


     "address": "14956 Pines Blvd",
     "city": "Pembroke Pines",
     "country": "United States",
     "postalCode": "33027",
     "state": "FL",
     "text": "Whole Foods Market Pembroke Pines",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.099637,
    26.261333 ]
   },
   "properties": {


     "address": "2411 N. Federal Hwy",
     "city": "Pompano Beach",
     "country": "United States",
     "postalCode": "33062",
     "state": "FL",
     "text": "Whole Foods Market Pompano",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.206289,
    26.641288 ]
   },
   "properties": {


     "address": "2635 South State Road 441",
     "city": "Wellington",
     "country": "United States",
     "postalCode": "33414",
     "state": "FL",
     "text": "Whole Foods Market Wellington",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.089309,
    26.720695 ]
   },
   "properties": {


     "address": "1845 Palm Beach Lakes Blvd Bldg C",
     "city": "West Palm Beach",
     "country": "United States",
     "postalCode": "33401",
     "state": "FL",
     "text": "Whole Foods Market West Palm Beach",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.763101,
    27.886305 ]
   },
   "properties": {


     "address": "12500 Starkey Rd",
     "city": "Largo",
     "country": "United States",
     "postalCode": "33773",
     "state": "FL",
     "text": "Willard'S Tap House",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.343803,
    28.568257 ]
   },
   "properties": {


     "address": "3201 Corrine Driveooth 6",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32803",
     "state": "FL",
     "text": "Winter Park Biscuit Co",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.263688,
    28.699548 ]
   },
   "properties": {


     "address": "1164 Tree Swallow Dr Ste 1002",
     "city": "Winter Springs",
     "country": "United States",
     "postalCode": "32708",
     "state": "FL",
     "text": "Winter Springs Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.317221,
    27.891694 ]
   },
   "properties": {


     "address": "11127 Winthrop Market Street",
     "city": "Riverview",
     "country": "United States",
     "postalCode": "33578",
     "state": "FL",
     "text": "Winthrop Liquors",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.532814,
    27.959416 ]
   },
   "properties": {


     "address": "5311 Avion Park Drive",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33607",
     "state": "FL",
     "text": "World Of Beer - Avion",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.327871,
    27.921066 ]
   },
   "properties": {


     "address": "2878 Providence Lakes Blvd",
     "city": "Brandon",
     "country": "United States",
     "postalCode": "33511",
     "state": "FL",
     "text": "World Of Beer - Brandon",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.371534,
    28.54264 ]
   },
   "properties": {


     "address": "431 E Central Blvd Ste D",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32801",
     "state": "FL",
     "text": "World Of Beer - Central",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.186499,
    26.283936 ]
   },
   "properties": {


     "address": "4437 Lyons Roadsuite E 101",
     "city": "Coconut Creek",
     "country": "United States",
     "postalCode": "33073",
     "state": "FL",
     "text": "World Of Beer - Coconut Creek",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.336426,
    25.809275 ]
   },
   "properties": {


     "address": "8700-102 Nw 36Th St",
     "city": "Doral",
     "country": "United States",
     "postalCode": "33166",
     "state": "FL",
     "text": "World Of Beer - Doral",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -82.592143,
    28.043287 ]
   },
   "properties": {


     "address": "9526 & 9524 West Linebaugh Ave",
     "city": "Tampa",
     "country": "United States",
     "postalCode": "33626",
     "state": "FL",
     "text": "World Of Beer - Linebaugh",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.281374,
    25.98821 ]
   },
   "properties": {


     "address": "11225-B295 Miramar Parkway",
     "city": "Miramar",
     "country": "United States",
     "postalCode": "33025",
     "state": "FL",
     "text": "World Of Beer - Miramar",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.488894,
    28.398293 ]
   },
   "properties": {


     "address": "7750-130 Palm Parkway",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32836",
     "state": "FL",
     "text": "World Of Beer - Orlando",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.949447,
    28.940296 ]
   },
   "properties": {


     "address": "994 Alverez Ave",
     "city": "Lady Lake",
     "country": "United States",
     "postalCode": "32159",
     "state": "FL",
     "text": "World Of Beer - Spanish Springs",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -81.22106,
    28.598214 ]
   },
   "properties": {


     "address": "3402 Technological Ave Ste 201",
     "city": "Orlando",
     "country": "United States",
     "postalCode": "32817",
     "state": "FL",
     "text": "World Of Beer - Ucf",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.726396,
    28.243072 ]
   },
   "properties": {

     "address": "2290 Town Center Ave Ste 119",
     "city": "Viera",
     "country": "United States",
     "postalCode": "32940",
     "state": "FL",
     "text": "World Of Beer - Viera",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.2044,
    25.800234 ]
   },
   "properties": {


     "address": "565 Nw 24 Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Wynwood Brewing Company Llc",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.200882,
    25.799953 ]
   },
   "properties": {


     "address": "320 Nw 24 Street",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Wynwood Smoke & Lounge",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.200882,
    25.799953 ]
   },
   "properties": {


     "address": "320 Nw 24 St",
     "city": "Miami",
     "country": "United States",
     "postalCode": "33127",
     "state": "FL",
     "text": "Wynwood Smoke Shop",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.161929,
    25.896176 ]
   },
   "properties": {


     "address": "13160 Biscayne Blvd",
     "city": "North Miami",
     "country": "United States",
     "postalCode": "33181",
     "state": "FL",
     "text": "Xs Vapor Lounge",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   },
    {
     "type": "Feature",
     "geometry": {
     "type": "Point",
     "coordinates": [
    -80.201164,
    26.149814 ]
   },
   "properties": {


     "address": "3944 Nw 19Th St",
     "city": "Lauderhill",
     "country": "United States",
     "postalCode": "33311",
     "state": "FL",
     "text": "Yeasty Brews",
     "notice": "Call ahead to ensure they have what you are looking for."
    }
   }

  ]
};

map.on('load', () => {
  /* Add the data to your map as a layer */
  map.addLayer({
    id: 'locations',
    type: 'circle',
    /* Add a GeoJSON source containing place coordinates and information. */
    source: {
      type: 'geojson',
      data: stores
    }
  });

  const geocoder = new MapboxGeocoder({
  accessToken: mapboxgl.accessToken, // Set the access token
  mapboxgl: mapboxgl, // Set the mapbox-gl instance
  marker: true, // Use the geocoder's default marker style
  bbox: [-87.6347449003925, 24.4303400087635, -79.9313803005511, 31.000885] // Set the bounding box coordinates
});

map.addControl(geocoder, 'top-left');
  buildLocationList(stores);

geocoder.on('result', (event) => {
  const searchResult = event.result.geometry;
  const options = { units: 'miles' };
for (const store of stores.features) {
  store.properties.distance = turf.distance(
    searchResult,
    store.geometry,
    options
  );
}
stores.features.sort((a, b) => {
  if (a.properties.distance > b.properties.distance) {
    return 1;
  }
  if (a.properties.distance < b.properties.distance) {
    return -1;
  }
  return 0; // a must be equal to b
});
const listings = document.getElementById('listings');
while (listings.firstChild) {
  listings.removeChild(listings.firstChild);
}
buildLocationList(stores);
const activeListing = document.getElementById(
  `listing-${stores.features[0].properties.id}`
);
activeListing.classList.add('active');
const bbox = getBbox(stores, 0, searchResult);
map.fitBounds(bbox, {
  padding: 100
});

createPopUp(stores.features[0]);
});
});

/* Assign a unique ID to each store */
stores.features.forEach(function (store, i) {
  store.properties.id = i;
});

map.on('click', (event) => {
  /* Determine if a feature in the "locations" layer exists at that point. */
  const features = map.queryRenderedFeatures(event.point, {
    layers: ['locations']
  });

  /* If it does not exist, return */
  if (!features.length) return;

  const clickedPoint = features[0];

  /* Fly to the point */
  flyToStore(clickedPoint);

  /* Close all other popups and display popup for clicked store */
  createPopUp(clickedPoint);

  /* Highlight listing in sidebar (and remove highlight for all other listings) */
  const activeItem = document.getElementsByClassName('active');
  if (activeItem[0]) {
    activeItem[0].classList.remove('active');
  }
  const listing = document.getElementById(
    `listing-${clickedPoint.properties.id}`
  );
  listing.classList.add('active');
});

function buildLocationList(stores) {
  for (const store of stores.features) {
    /* Add a new listing section to the sidebar. */
    const listings = document.getElementById('listings');
    const listing = listings.appendChild(document.createElement('div'));
    /* Assign a unique `id` to the listing. */
    listing.id = `listing-${store.properties.id}`;
    /* Assign the `item` class to each listing for styling. */
    listing.className = 'item';

    /* Add the link to the individual listing created above. */
    const link = listing.appendChild(document.createElement('a'));
    link.href = '#';
    link.className = 'title';
    link.id = `link-${store.properties.id}`;
    link.innerHTML = `${store.properties.address}`;

    /* Add details to the individual listing. */
    const details = listing.appendChild(document.createElement('div'));
    details.innerHTML = `${store.properties.text}`;
    details.innerHTML += ` · ${store.properties.city}`;

    if (store.properties.distance) {
      const roundedDistance = Math.round(store.properties.distance * 100) / 100;
      details.innerHTML += `<div><strong>${roundedDistance} miles away</strong></div>`;
    }
    link.addEventListener('click', function () {
  for (const feature of stores.features) {
    if (this.id === `link-${feature.properties.id}`) {
      flyToStore(feature);
      createPopUp(feature);
    }
  }
  const activeItem = document.getElementsByClassName('active');
  if (activeItem[0]) {
    activeItem[0].classList.remove('active');
  }
  this.parentNode.classList.add('active');
});
  }
}

function flyToStore(currentFeature) {
  map.flyTo({
    center: currentFeature.geometry.coordinates,
    zoom: 15
  });
}

function createPopUp(currentFeature) {
  const popUps = document.getElementsByClassName('mapboxgl-popup');
  /** Check if there is already a popup on the map and if so, remove it */
  if (popUps[0]) popUps[0].remove();

  const popup = new mapboxgl.Popup({ closeOnClick: false })
    .setLngLat(currentFeature.geometry.coordinates)
    .setHTML(`<h3>${currentFeature.properties.text}</h3><h4>${currentFeature.properties.address}</h4><h5>${currentFeature.properties.notice}</h5>`)
    .addTo(map);
}

function getBbox(sortedStores, storeIdentifier, searchResult) {
  const lats = [
    sortedStores.features[storeIdentifier].geometry.coordinates[1],
    searchResult.coordinates[1]
  ];
  const lons = [
    sortedStores.features[storeIdentifier].geometry.coordinates[0],
    searchResult.coordinates[0]
  ];
  const sortedLons = lons.sort((a, b) => {
    if (a > b) {
      return 1;
    }
    if (a.distance < b.distance) {
      return -1;
    }
    return 0;
  });
  const sortedLats = lats.sort((a, b) => {
    if (a > b) {
      return 1;
    }
    if (a.distance < b.distance) {
      return -1;
    }
    return 0;
  });
  return [
    [sortedLons[0], sortedLats[0]],
    [sortedLons[1], sortedLats[1]]
  ];
}
</script>
