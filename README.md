![pxfuel](https://github.com/ichsanfifa99/ultah-bebee/assets/157405120/3bbb03ed-833f-48cd-b353-ce22984ee31f)# ultah-bebee
pengingat
<!DOCTYPE html>
<html>
<style>
body, html {
  height: 100%;
  margin: 0;
}
.bgimg {
  background-image: url('pxfuel.jpg');
  height: 100%;
  background-position: center;
  background-size: cover;
  position: relative;
  color: white;
  font-family: "Courier New", Courier, monospace;
  font-size: 25px;
}
.topleft {
  position: absolute;
  top: 0;
  left: 16px;
}
.bottomleft {
  position: absolute;
  bottom: 0;
  left: 16px;
}
.middle {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}
hr {
  margin: auto;
  width: 40%;
}
</style>
<body>
<div class="bgimg">
  <div class="topleft">
    <p>Birthday Bebeee sayangkuuu 💕</p>
  </div>
  <div class="middle">
    <h1>COMING SOON</h1>
    <hr>
<p id="demo"></p>
  </div>
  <div class="bottomleft">
    <p>I love You Bebee</p>
  </div>
</div>
 <figure>
    <figcaption>Listen me</figcaption>
    <audio
        controls
        src="ultah.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>
</div>
<!-- Display the countdown timer in an element -->
<script>
// Set the date we're counting down to
var countDownDate = new Date("Marc 12, 2024 00:00:00").getTime();
// Update the count down every 1 second
var x = setInterval(function() {
  // Get today's date and time
  var now = new Date().getTime();
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";
  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>
</body>
</html>
