# AnggaFirmansyah.github.io

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Smart Farming</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background: #f5f6f8;
    }
    .sensor-card {
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.08);
      text-align: center;
      padding: 15px;
    }
    .sensor-value {
      font-size: 1.4rem;
      font-weight: 600;
      margin-top: 6px;
    }
  </style>
</head>
<body>
  <div class="container py-4">
    <h3 class="mb-4">Smart Farming</h3>
    <div class="row g-3">

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-primary bg-white">
          <div>KELEMBABAN (RH)</div>
          <div class="sensor-value text-primary">54 %</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-success bg-white">
          <div>TDS</div>
          <div class="sensor-value text-success">400 ppm</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-info bg-white">
          <div>KEKERUHAN (TURBID)</div>
          <div class="sensor-value text-info">18 NTU</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-warning bg-white">
          <div>TEMPERATUR AIR (WTEMP)</div>
          <div class="sensor-value text-warning">25 °C</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-primary bg-white">
          <div>OKSIGEN TERLARUT</div>
          <div class="sensor-value text-primary">10 ppm</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-success bg-white">
          <div>INTENSITAS CAHAYA</div>
          <div class="sensor-value text-success">100 Lux</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-info bg-white">
          <div>TEMPERATUR UDARA (AMTEMP)</div>
          <div class="sensor-value text-info">34 °C</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-warning bg-white">
          <div>EC</div>
          <div class="sensor-value text-warning">2</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-danger bg-white">
          <div>ALIRAN AIR (WFLOW)</div>
          <div class="sensor-value text-danger">34</div>
        </div>
      </div>

      <div class="col-md-3 col-sm-6">
        <div class="sensor-card border-danger bg-white">
          <div>pH</div>
          <div class="sensor-value text-danger">7.1</div>
        </div>
      </div>

    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
