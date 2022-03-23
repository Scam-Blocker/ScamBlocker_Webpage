# 🐟 Scamblocker 🐟
## ***App is still under development!***
https://linktr.ee/ScamBlocker

KISS scams goodbye! To be released for Android & iOS.

Overview:
1. What is Scamblocker? 🐟
2. Design & Philosophy 🤔
3. Be in the loop! 😎

## 1. What is Scamblocker? 🐟
Scamblocker is ,unsurprisingly, a scam blocking application. The algorithm behind our app will be tailored for the context of Singapore, though usage in other countries should be reasonably viable.

![Demo gif](https://media1.giphy.com/media/aNolEvCgjtE9RqghYq/giphy.gif)

## 2. Design & Philosophy 🤔
We aim to create an app that is capable of filtering out scam messages effectively. Scams are a huge issue in Singapore, with a recent Straits Times article titled "Over 300 victims lose $760,000 to phishing scams related to delivery firms". The app will utilise both blacklisting and machine learning technology to identify and isolate scam messages. Through such, we hope to reduce the alarming damage done by scams.

The interface of Scamblocker will be bare and minimal, following the KISS principle.
- The KISS principle refers to "Keep it Simple, Stupid".
- We believe that extreme simplicity will allow users of all ages to use Scamblocker in a manner as intended, without any confusion.

While Google's messaging app has in-built anti-scam features, we hope scamblocker keeps "big tech" company's hands away from your private data (or, at least further away). 

## 3. Be in the loop! 😎
Join our newsletter by entering your email below, we promise to never spam!

<form method="post" id="sheetdb-form"
  action="https://sheetdb.io/api/v1/z2ds7stbrwanb">
    Your email: <input name="data[email]">
    <button type="submit">Submit</button>
</form>

<script>
  var form = document.getElementById('sheetdb-form');
  form.addEventListener("submit", e => {
    e.preventDefault();
    fetch(form.action, {
        method : "POST",
        body: new FormData(document.getElementById("sheetdb-form")),
    }).then(
        response => response.json()
    ).then((html) => {
      // you can put any JS code here
      alert('Success. Thank you for your support!')
    });
  });
</script>


Do contact our team at [scam.blocker@outlook.com](mailto:scam.blocker@outlook.com) to simply find out more or even help with our project!
