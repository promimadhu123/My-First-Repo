<!DOCTYPE html>
font-family: 'Inter', sans-serif;
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Stats Section</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f7f9fc;
      display: flex;
      justify-content: center;
      padding: 20px;
    }

    .stats-section {
      background-color: #e8eafb;
      text-align: center;
      padding: 40px 20px;
      border-radius: 20px;
      max-width: 1000px;
      width: 100%;
    }

    .stats-section h2 {
      font-size: 1.75rem;
      color: #1c1c1c;
      font-weight: 700;
      margin-bottom: 40px;
    }

    .stats-container {
      display: flex;
      justify-content: space-around;
      align-items: center;
      gap: 40px;
      flex-wrap: wrap;
    }

    .stat-item {
      flex: 1 1 150px;
      min-width: 120px;
      margin-bottom: 20px;
    }

    .stat-item h3 {
      font-size: 2.5rem;
      font-weight: 700;
      color: #5D5FEF;
      margin-bottom: 8px;
    }

    .stat-item p {
      font-size: 1rem;
      color: #6b7280;
      margin: 0;
    }

    @media (max-width: 768px) {
      .stats-section {
        padding: 30px 15px;
      }
      .stats-section h2 {
        font-size: 1.5rem;
        margin-bottom: 30px;
      }
      .stats-container {
        gap: 20px;
      }
      .stat-item h3 {
        font-size: 2rem;
      }
    }

    @media (max-width: 480px) {
      .stats-section {
        padding: 20px 10px;
      }
      .stats-section h2 {
        font-size: 1.25rem;
        margin-bottom: 20px;
      }
      .stat-item h3 {
        font-size: 1.75rem;
      }
    }
  </style>
</head>
<body>
  <section class="stats-section">
    <h2>Joined Thousands of Productive Users</h2>
    <div class="stats-container">
      <div class="stat-item">
        <h3>50K</h3>
        <p>Active Users</p>
      </div>
      <div class="stat-item">
        <h3>2M+</h3>
        <p>Focus Sessions</p>
      </div>
      <div class="stat-item">
        <h3>95%</h3>
        <p>Satisfaction Rate</p>
      </div>
    </div>
  </section>
</body>
</html>
