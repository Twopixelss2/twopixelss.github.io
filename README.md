<!DOCTYPE html>
<html>

<head>
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
    <title>Jaco Vibezz Counter!</title>
</head>
<style>
    body,
    html {
        height: 100%;
        margin: 0;
    }

    .bgimg {
        background-image: url('https://images.pexels.com/photos/2707756/pexels-photo-2707756.jpeg?cs=srgb&dl=pexels-aleksandar-pasaric-2707756.jpg&fm=jpg');
        height: 100%;
        background-position: center;
        background-size: cover;
        position: relative;
        color: white;
        font-family: sans-serif;
        font-size: 25px;
    }

    .topleft {
        position: absolute;
        font-family: sans-serif;
        top: 0;
        left: 16px;
    }

    .bottomleft {
        font-family: sans-serif;
        position: absolute;
        bottom: 0;
        left: 16px;
    }

    .middle {
        position: absolute;
        font-family: sans-serif;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
        text-shadow: 5px 5px 5px black;
    }

    hr {
        margin: auto;
        width: 40%;
    }
</style>

<body>

    <div class="bgimg">
        <div class="topleft">
            <b>
                <p>Jaco Vibezz🌊</p>
            </b>
        </div>
        <div class="middle" style="text-shadow: 2px 2px 2px black;">
            <b>
                <h1>JACO VIBEZZ COUNTER</h1>
            </b>
            <h4>till Summer🌊 / ATH touchdown!🛬</h4>
            <hr>
            <p id="demo" style="font-size:30px"></p>
        </div>
        <div class="bottomleft">
            <i>
                <p>by Jaco Airlines</p>
            </i>
        </div>
    </div>

    <script>
        // Set the date we're counting down to
        var countDownDate = new Date("Jun 15, 2023 23:59:59").getTime();

        // Update the count down every 1 second
        var countdownfunction = setInterval(function () {

            // Get todays date and time
            var now = new Date().getTime();

            // Find the distance between now an the count down date
            var distance = countDownDate - now;

            // Time calculations for days, hours, minutes and seconds
            var days = Math.floor(distance / (1000 * 60 * 60 * 24));
            var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            var seconds = Math.floor((distance % (1000 * 60)) / 1000);

            // Output the result in an element with id="demo"
            document.getElementById("demo").innerHTML = days + "d " + hours + "h "
                + minutes + "m " + seconds + "s ";

            // If the count down is over, write some text 
            if (distance < 0) {
                clearInterval(countdownfunction);
                document.getElementById("demo").innerHTML = "EXPIRED";
            }
        }, 1000);
    </script>

</body>

</html>
