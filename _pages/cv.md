---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<script>

/* I created a function which would check if the frame src the same to which is your url. else it would change the frame src automatically */
function ckframe() {

// define framesrc = the frame src
var framesrc = document.getElementById('frame').src;

// define the url
var urlsrc = "https://rmarcinkevics.github.io/files/CV_RMarcinkevics_short.pdf";

// here is where it checks.
if (framesrc != urlsrc) {
framesrc = urlsrc;
}
}

// make an interval every second to make sure that the src is correct.
setInterval("ckframe()",500);
</script>

<iframe src="https://docs.google.com/viewer?url=https://rmarcinkevics.github.io/files/CV_RMarcinkevics_short.pdf&embedded=true" style="width:100%; height:650px;" frameborder="0"><p>Your web browser doesn't have a PDF plugin.
  Instead you can <a href="https://rmarcinkevics.github.io/files/CV_RMarcinkevics_short.pdf" style="color: black; text-decoration: underline;text-decoration-style: dotted;">click here</a> to
  download the PDF file.</p></iframe>
