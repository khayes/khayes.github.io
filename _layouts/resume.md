<!--
Hello there!

This website uses Jekyll and is hosted on GitHub pages as it only needs a simple hosting platform.
Other than the image icons I have hand created all the markup and styles for this website.
I like to ensure my work is not just visually clean, but that the source is well thought through and is simple and semantic as possible.

If you are interested in viewing the source for this site you can find it on my GitHub account at https://github.com/khayes
If you have any questions or suggestions please reach out to me at kieran@khayes.ie
-->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>{% if page.title %} {{ page.title }} - {% endif %}Kieran Hayes</title>
    <meta http-equiv="Content-Security-Policy" content="block-all-mixed-content; default-src 'none'; img-src 'self'; style-src 'self';">
    <link rel="stylesheet" href="/assets/css/style.css" />
  </head>
  <body>
    <main id="resume">{{ content }}</main>
  </body>
</html>