---
layout: post
title: "Wedding Invitation"
categories: thought
img: wedding-invitation-quyhk-cover.jpg
---
This is a testing

{% include img/full-normal.html src="/img/post/thought/wedding/AP-Wedding.jpg" des="Ảnh cưới demo." %}

## Thời gian đếm ngược

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
  document.getElementById("countdown").innerHTML = days + " ngày, " + hours + " giờ, "
  + minutes + " phút, " + seconds + " giây";

  // If the countdown is over, display a message
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("countdown").innerHTML = "Cảm ơn các bạn đã đến tham dự lễ cưới của chúng mình!";
  }
}, 1000);
</script>

<div id="countdown" style="text-align: center; color: red;"></div>



## Địa điểm đón khách



<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3724.2949454335794!2d105.85184932853097!3d21.020881341232016!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3135abedb5e4a929%3A0x6fcb00cf4e2c426f!2sSun%20Red%20River%20Building!5e0!3m2!1sen!2sus!4v1681192017295!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

