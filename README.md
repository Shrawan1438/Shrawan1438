<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IP Address Tracker</title>
    <link
        href="https://fonts.googleapis.com/css?family=Rubik:300,regular,500,600,700,800,900,300italic,italic,500italic,600italic,700italic,800italic,900italic"
        rel="stylesheet" />
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
    integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY=" crossorigin="" />
  <link rel="stylesheet" href="style.css">
  <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"
    integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=" crossorigin=""></script>
    <script src="script.js" defer></script>

</head>
<body>
    <main>
        <header>
            <h1>IP Address Tracker</h1>
            <div class="search-ip">
                <input class="input" type="text" placeholder="Search for any IP address or domain">
                <div class="arrow"> <img src="images/icon-arrow.svg" alt=""> </div>
            </div>
            <div class="data-container">
                <div class="data">
                    <div class="info-title"> IP Address</div>
                    <div class="info">xysshgsdxh</div>
                </div>
                <div class="data shrink-level">
                    <div class="info-title"> Location</div>
                    <div class="info">cdhcdhddc</div>
                </div>
                <div class="data">
                    <div class="info-title">Timezone</div>
                    <div class="info">dsdscdc</div>
                </div>
                <div class="data">
                    <div class="info-title"> ISP</div>
                    <div class="info">dfddcds</div>
                </div>
            </div>
        </header>
        <div id="map"></div>
    </main>
</html>
