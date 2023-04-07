
Gráfico em Barra

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chart JS</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

</head>
<body>



    <div>
  <canvas id="myChart"></canvas>
</div>




</body>
<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['Janeiro', 'Fevereiro', 'Março', 'Abril', 'Maio', 'Junho'],
      datasets: [{
        label: 'Umidade Média', 
        backgroundColor: 'rgb(54,162,235)',
        data: [90, 89, 93, 87, 88, 82],
        borderWidth: 1
      },
      {
        label: 'Temperatura', 
        backgroundColor: 'rgb(255,99,132)',
        data: [22, 24, 27, 23, 20, 18],
        borderWidth: 1
      }
    ]
    },
    
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>
 
</html>


                                                                   GRÁFICO EM LINHA
                                                                   
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chart JS</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

</head>
<body>



    <div>
  <canvas id="myChart"></canvas>
</div>




</body>
<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'line',
    data: {
      labels: ['Janeiro', 'Fevereiro', 'Março', 'Abril', 'Maio', 'Junho'],
      datasets: [{
        label: 'Umidade Média', 
        backgroundColor: 'rgb(54,162,235)',
        borderColor: 'rgb(54,162,235)',
        data: [80, 82, 80, 85, 80, 83],
        borderWidth: 5
      },
      {
        label: 'Temperatura', 
        backgroundColor: 'rgb(255,99,132)',
        borderColor: 'rgb(255,99,132)',
        data: [30, 29, 28, 25, 22, 23],
        borderWidth: 5
      }
    ]
    },
    
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>
 
</html>

                                                                  
