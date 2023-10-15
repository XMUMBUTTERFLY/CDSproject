
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XMUM Students Favorite Food</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 40px;
        }
        h1 {
            color: #333333;
        }
        .main-container {
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .img-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 60%;
            margin: 0 1%;
        }
        img.side {
            width: 19%; /* Adjusted width for side images */
            margin: 10px;
        }
        img.middle {
            width: 100%; /* Full width for central images within its container */
            margin: 10px;
        }

        /* Media Query for Mobile Devices */
        @media (max-width: 768px) {
            .main-container {
                flex-direction: column;
            }
            .img-container, img.side {
                width: 100%; /* On mobile devices, images take full width */
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <h1>XMUM STUDENTS FAVORITE FOOD</h1>
    <div class="main-container">
        <img class="side" src="ly3.png" alt="Side Image 1">
        <div class="img-container">
            <img class="middle" src="canteen_preference_charts.png" alt="Preferred Canteens">
            <img class="middle" src="food_stall_preference_charts (1).png" alt="Preferred Food">
            <img class="middle" src="food_preference_charts.png" alt="Preferred Food Stalls">
        </div>
        <img class="side" src="d6.png" alt="Side Image 2">
    </div>
</body>
</html>

