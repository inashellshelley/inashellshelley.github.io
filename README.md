# quiestarestaurantproject-site.github.io
Restaurant Website CSE326 CA project by Shalini Guha and Radhika Goyal 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Quiesta Italian Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!--head section-->
    <nav id="header">
        <div id="logo">
            <p>QUIESTA</p>
        </div>
        <ul>
            <li><a href="#home" data-after="Home">HOME</a></li>
            <li><a href="#menu" data-after="Menu">MENU</a></li>
            <li><a href="#about" data-after="About">ABOUT US</a></li>
            <li><a href="#booking" data-after="Booking">BOOK</a></li>
            <li><a href="#contact" data-after="Contact">CONTACT US</a></li>
        </ul>
    </nav>
    </section>
    <!--End of head section-->

    <!--home section-->
    <section id="home">
        <div class="home container">
            <div>
                <h1> Quiesta, your Little Italy </h1>
                <a href="#booking" type="button" class="cta">BOOK A TABLE</a>
            </div>
        </div>
    </section>
    <!--End of home section-->

    <!--Menu section-->
    <section id="menu">
        <div class="menu container">
            <div class="menu-top">
                <h1 class="menu-title">MENU</h1>
            </div>
            <div class="menu-down">
                <div class="menu-item1">

                    <h2> Hungry for food </h2>
                    <p>
                        <ul>Lasagna </ul>
                        <ul>Raveioli pasta </ul>
                        <ul>Margherita Pizza </ul>
                        <ul> Spaghetti Classica</ul>
                        <ul> Garlic bread</ul>
                        <ul> Bruschetta</ul>
                    </p>
                </div>
                <div class="menu-item2">

                    <h2> Craving sweet </h2>
                    <p>
                        <ul>Lemon Tart </ul>
                        <ul>Tiramisu </ul>
                        <ul>Canestrelli </ul>
                        <ul> Torta Barozzi</ul>
                        <ul> Affogato</ul>
                        <ul> Zeppole</ul>
                    </p>
                </div>
                <div class="menu-item3">
                    <h2> Something to drink </h2>
                    <p>
                        <ul>Sunshine Lime Ricky</ul>
                        <ul> Mango my tie </ul>
                        <ul> Pina Colada </ul>
                        <ul> Pink Rhubarb Punch</ul>
                        <ul> Scarlet Sipper</ul>
                        <ul> Blackberry Shrub</ul>
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!--End of Menu section-->

    <!--Booking section-->

    <section id="booking">

        <div id="booking-box">
            <form action="">
                <div class="form-group">
                    <label for="name"><strong>Book under the name: </strong> </label>
                    <input type="text" name="name" id="name" placeholder="Enter your name">
                </div>
                <div class="form-group">
                    <label for="email"><strong>Mail you at: </strong> </label>
                    <input type="email" name="name" id="email" placeholder="Enter your email">
                </div>
                <div class="form-group">
                    <label for="phone"><strong>How to reach you? </strong> </label>
                    <input type="number" name="name" id="phone" placeholder="Enter your phone">
                </div>
                <div class="form-group">
                    <label for="number"><strong> A table for: </strong> </label>
                    <input type="number" name="name" id="number" placeholder="Enter number of people">
                </div>
                <div class="form-group">
                    <label for="awareness"><strong>Any special requests or Occasion? </strong>  </label>
                    <textarea name="awareness" id="awareness" cols="20" rows="10"></textarea>
                </div>
                <button class="btn">Submit</button>
            </form>
        </div>
    </section>

    <!--End of Booking section-->

    <!--About Section-->

    <section id="about">
        <div class="about container">

            <div class="right">
                <h1 class="about-title"> About Us </h1>
                <h2> We love food...</h2>
                <p> Metus dictum, at velit primis. Laoreet pellentesque. Adipiscing varius rhoncus a. Nunc nonummy netus. Enim orci commodo quis suspendisse feugiat massa dui eget torquent. Purus id curabitur odio netus. Ullamcorper tortor. Phasellus porttitornullam,
                    quam, phasellus enim pede. Lectus leo pharetra fermentum quis porttitor purus gravida eget parturient pellentesque aptent eleifend, curae; donec odio sem placerat magna curae; felis Ad posuere sodales tellus non quam. Tempor maecenas
                    eros elit. Neque est. Nascetur nibh faucibus nascetur eu hendrerit enim adipiscing odio ornare accumsan nulla facilisi, congue iaculis sagittis porta vulputate varius ad molestie Dignissim rhoncus praesent sit Vulputate taciti vehicula
                    sapien. Metus dictum, at velit primis. Laoreet pellentesque. Adipiscing varius rhoncus a. Nunc nonummy netus. Enim orci commodo quis suspendisse feugiat massa dui eget torquent. Purus id curabitur odio netus. Ullamcorper tortor. Phasellus
                    porttitornullam, quam, phasellus enim pede. Lectus leo pharetra fermentum quis porttitor purus gravida eget parturient pellentesque aptent eleifend, curae; donec odio sem placerat magna curae; felis Ad posuere sodales tellus non quam.
                    Tempor maecenas eros elit. Neque est. Nascetur nibh faucibus nascetur eu hendrerit enim adipiscing odio ornare accumsan nulla facilisi, congue iaculis sagittis porta vulputate varius ad molestie Dignissim rhoncus praesent sit Vulputate
                    taciti vehicula sapien.
                </p>
            </div>
        </div>
    </section>

    <!--End of About Section-->

    <!-- Contact Section -->
    <section id="contact">
        <div class="contact container">
            <div>
                <h1 class="section-title">Contact Us</h1>
            </div>
            <div class="contact-items">
                <div class="contact-item">
                    <div class="contact-info">
                        <h2>Phone</h2>
                        <h3>+91 2233445566</h3>
                        <h3>+91 6677889900</h3>
                    </div>
                </div>
                <div class="contact-item">

                    <div class="contact-info">
                        <h2>Email</h2>
                        <h3>customercomplain@quiesta.com</h3>
                        <h3>customerreview@quiesta.com</h3>
                        <h3>jobs@quiesta.com</h3>
                    </div>
                </div>
                <div class="contact-item">

                    <div class="contact-info">
                        <h2>Address</h2>
                        <h3>Metus dictum, at velit primis. Laoreet pellentesque.Adipiscing varius rhoncus a.</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- End Contact Section -->
    <footer>
        <div class="center">
            Copyright &copy;All rights reserved!
        </div>

    </footer>

</body>

</html>
