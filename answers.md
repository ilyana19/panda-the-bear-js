var profileImage = document.querySelector(".profile-image");
profileImage.src = "https://placebear.com/400/400";

var portfolioImage1 = document.querySelector(".photography");
portfolioImage1.src = "https://placebear.com/325/225";

var title = document.querySelector("h1");
title.innerHTML = "Linda";
title.style.fontFamily = "monospace";

var body = document.querySelector("body");
body.style.backgroundColor = "#eee";
body.style.color = "#333";

var highlights = document.querySelectorAll(".highlight");
highlights.forEach(function(highlight) {
  highlight.style.backgroundColor = "#22d4bd";
});

var roundButtons = document.querySelectorAll(".action-icon-bg");
roundButtons.forEach(function(roundButton) {
  roundButton.style.backgroundColor = "#66b2d8";
});

var formNameField = document.querySelector("#name");
formNameField.placeholder = "Identify Yourself";
formNameField.value = "Your Nemesis";

var formMessageField = document.querySelector("#message");
formMessageField.placeholder = "State Your Business";

var formEmailField = document.querySelector("#email");
formEmailField.value = "koalathebear@gmail.com";

var submitButton = document.querySelector("#submit");
submitButton.value = "En garde!";
submitButton.setAttribute("disabled", true);

var bioInfo = document.querySelectorAll(".bio-info-value");
bioInfo.forEach(function(bioInfo) {
  if (!bioInfo.classList.contains("bio-info-name")) {
    bioInfo.innerHTML = "Hidden";
  }
});