<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Meta Pixel Code -->
    <script>
        !function(f,b,e,v,n,t,s) {
            if (f.fbq) return; n = f.fbq = function() {
                n.callMethod ? n.callMethod.apply(n, arguments) : n.queue.push(arguments)
            };
            if (!f._fbq) f._fbq = n; n.push = n; n.loaded = !0; n.version = '2.0';
            n.queue = []; t = b.createElement(e); t.async = !0;
            t.src = v; s = b.getElementsByTagName(e)[0];
            s.parentNode.insertBefore(t, s)
        }(window, document, 'script', 'https://connect.facebook.net/en_US/fbevents.js');
        fbq('init', '2985325631617246'); // Ensure this ID is necessary
        fbq('track', 'PageView');
    </script>
    <noscript>
        <img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=2985325631617246&ev=PageView&noscript=1" />
    </noscript>
    <!-- End Meta Pixel Code -->

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="BK8 - Your ultimate gaming destination.">
    <title>BK8</title>
    <link rel="preload" as="style" onload="this.onload=null; this.rel='stylesheet'" href="./css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" integrity="sha512-jnSuA4Ss2PkkikSOLtYs8BlYIeeIK1h99ty4YfvRPAlzr377vr3CXDb7sb7eEEBYjDtcYj+AjBH3FLv5uSJuXg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <main class="d-lg-flex">
        <section class="position-relative d-lg-inline-block mx-lg-auto">
            <picture>
                <source type="image/webp" srcset="./image/bg.webp">
                <img src="./image/bg.jpg" id="bg" alt="A scenic background for BK8">
            </picture>

            <div class="position-absolute w-100 text-center redirect-btn">
                <a href="./assets/load16.html" id="btn-link">
                    <picture>
                        <source type="image/webp" srcset="./image/tombol/btn.webp">
                        <img src="./image/tombol/btn.png" id="tekan" alt="Click here to proceed" style="cursor: pointer;">
                    </picture>
                </a>
            </div>
        </section>
    </main>

    <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
    <script src="./js/script.js"></script>
    <script>
        document.getElementById("tekan").addEventListener("click", function (event) {
            event.preventDefault(); // Prevent default anchor behavior
            kwaiq.instance('578399536293875793').track("addToCart", {
                value: 0.5,
                currency: "USD",
            });
            window.location.href = this.parentElement.href; // Redirect after tracking
        });
    </script>
</body>

</html>
