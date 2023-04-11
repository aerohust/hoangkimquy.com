---
layout: post
title: "Wedding Invitation"
categories: thought
img: wedding-invitation-quyhk-cover.jpg
---
This is a testing

{% include img/full-normal.html src="/img/post/thought/wedding/AP-Wedding.jpg" des="Ảnh cưới demo." %}

# Wedding Countdown Timer

<script>
// Set the date of your wedding in UTC+7 timezone
var countDownDate = new Date("2023-04-23T16:00:00+07:00").getTime();

// Update the countdown every 1 second
var x = setInterval(function() {

  // Get the current date and time in UTC+7 timezone
  var now = new Date().getTime() + (7 * 60 * 60 * 1000);

  // Calculate the time remaining until your wedding
  var distance = countDownDate - now;

  // Calculate the days, hours, minutes, and seconds remaining
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the countdown on the page
  document.getElementById("countdown").innerHTML = days + " days, " + hours + " hours, "
  + minutes + " minutes, " + seconds + " seconds";

  // If the countdown is over, display a message
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("countdown").innerHTML = "Congratulations! It's your wedding day!";
  }
}, 1000);
</script>

<div id="countdown"></div>

