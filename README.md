# <!DOCTYPE html>

<!-- Auther: Shorouk Abdelaziz  https://shorouk.dev -->

<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Socials</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      display: grid;
      font-family: "Poppins", sans-serif;
      place-items: center;
    }

    .wrapper {
      padding-top: 10px;
      display: inline-flex;

    }

    .icon {
      /* Change the icon size here */
      font-size: 2em;
      /* Change the icons colours here*/
      color: #7a7a7a
    }


    .blog:hover {
      color: #ffbd2f;
    }

    .email:hover {
      color: #23c8c8;
    }

    .facebook:hover {
      color: #4267B2;
    }

    .instagram:hover {
      color: rgb(241, 102, 217);
    }

    .linkedin:hover {
      color: #0e76a8;
    }

    .twitter:hover {
      color: #26a7de;
    }

    .reddit:hover {
      color: #ff4500;
    }

    .tiktok:hover {
      color: #ff0050;
    }

    .youtube:hover {
      color: #FF0000;
    }

    .pinterest:hover {
      color: #c8232c;
    }

    .telegram:hover {
      color: #2AABEE;
    }

    .social {
      position: relative;
      margin: 10px;
      cursor: pointer;
    }
  </style>

</head>

<body>

  <body>

    <div class="wrapper">

      <!-- Start email Icon -->
      <div id="email" onclick="navigate(this.id)" class="social">
        <span class="icon email"><i class="fa-solid fa-envelope"></i></span>
      </div>
      <!-- End email Icon -->

      <!-- Start instagram Icon -->
      <div id="instagram" onclick="navigate(this.id)" class="social">
        <span class="icon instagram"><i class="fab fa-instagram"></i></span>
      </div>
      <!-- End instagram Icon -->

      <!-- Start tiktok Icon -->
      <div id="tiktok" onclick="navigate(this.id)" class="social">
        <span class="icon tiktok"><i class="fab fa-tiktok"></i></span>
      </div>
      <!-- End tiktok Icon -->

      <!-- Start pinterest Icon -->
      <div id="pinterest" onclick="navigate(this.id)" class="social">
        <span class="icon pinterest"><i class="fab fa-pinterest"></i></span>
      </div>
      <!-- End pinterest Icon -->



    </div>




    <script>
      function navigate(id) {

        //if you want the URL to open in the same window use '_parent'  instead of '_blank'

        if (id === "blog")
          window.open("https://blog.shorouk.dev", '_blank').focus(); //Add the url to your blog

        else if (id === "email") {
          window.open("mailto:joannetheryn14@gmail.com", '_blank').focus(); //Add your email after "mailto:""
        }

        else if (id === "facebook") {
          window.open("https://facebook.com/", '_blank').focus(); //Add the url to your facebook page or account
        }
        else if (id === "instagram") {
          window.open("https://www.instagram.com/joanne.theryn/", '_blank').focus(); //Add the url to your instagram account
        }
        else if (id === "linkedin") {
          window.open("https://www.linkedin.com/", '_blank').focus(); //Add the url to your pinterest account
        }
        else if (id === "twitter") {
          window.open("https://twitter.com/", '_blank').focus(); //Add the url to your pinterest account
        }
        else if (id === "reddit") {
          window.open("https://www.reddit.com/", '_blank').focus(); //Add the url to your reddit account
        }
        else if (id === "tiktok") {
          window.open("https://www.tiktok.com/@lilbouquets", '_blank').focus(); //Add the url to your tiktok account
        }
        else if (id === "youtube") {
          window.open("https://www.youtube.com/", '_blank').focus(); //Add the url to your youtube account
        }
        else if (id === "pinterest") {
          window.open("https://www.pinterest.com/emeluu14/", '_blank').focus(); //Add the url to your pinterest account
        }
        else if (id === "telegram") {
          window.open("https://web.telegram.org/", '_blank').focus(); //Add the url to your telegram account
        }
      }

    </script>



  </body>

</html>
