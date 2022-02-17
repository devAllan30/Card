Card Clone
DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card</title>
    <style>
        body{
            background-color: rgb(36, 36, 36);
            font-family: Arial, Helvetica, sans-serif;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100%;
            margin: 0%;
        }
        .container{
            background-color: #820ad1;
            padding: 1em;
            border-radius: 10px;
            width: 15em;
            height: 25em;
            box-shadow: 5px 8px 8px #000;
        }
        img[alt=mastercard]{
            width: 30%;
          
        }
        img[alt=chip]{
            transform: rotate(90deg);
        }
        .footer img{
            width: 35%;
        }
        .content{
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .header{
            height: 70%;

        }
        .box-img{
            display: flex;
            align-items: flex-start;

        }
        .footer{
            height: 30%;
            
        }
        .footer p{
            margin-left: 1em;
        }
        
    </style>
</head>
<body>
    <h1>Allan Flores</h1>
    <br>
    <div class="container">
        <div class="content">
                <div class="header">
                    <div class="box-img">
                        <img src="https://img.icons8.com/color/48/000000/mastercard-logo.png"/>
                        <img src="https://img.icons8.com/color/48/000000/sim-card-chip.png" alt="chip"/>
                    </div>
                    
                </div>
                <div class="footer">
                    <p>Allan Flores</p>
                    <img src="nubank_logo.png"alt="nubank">
                </div>
        </div>
    </div>
</body>        

