- Create a layout according to the design shown below.

![Backgrounds and gradient Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/adding-media/ex-1.png)

- Video link: https://www.youtube.com/watch?v=AqcjdkPMPJA#action=share

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/style.css">
    <script src="https://kit.fontawesome.com/ef43d9bbc3.js" crossorigin="anonymous"></script>
    <title>Document</title>
</head>
<body>
    <section class="part1">
        <div class="container">
        <header class="flex">
            <div class="left flex">
                <h2>Hydro</h2>
                <ul class="left1 flex">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Our Work</a></li>
                    <li><a href="#">ContactUs</a></li>
                </ul>
            </div>
            <div class="right flex">
                <ul class="right1 flex">
                    <li><a href="#"><i class="fab fa-facebook-square"></i></a></li>
                    <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                    <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                </ul>
                <button class="bt1">
                    <a href="#">Sign in/Join</a>
                </button>
            </div>
        </header>
        <section class="subpart1 flex">
            <article>
            <h1>We make beautiful</h1>
            <h1>websites for all people</h1>
            <div class="subpart1-1 flex">
                <button class="bt1 bt2">
                <a href="#">Start a project</a>
                </button>
                <div class="subpart1-1-1">
                <p>CALL US(+66)010-020-0340</p>
                <p>For any enquiry</p>
                </div>
            </div>
            </article>
            <figure>
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/AqcjdkPMPJA" 
                    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay;
                     clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

            </figure>
        </section>
        </div>
    </section>
    <section class="part2 container flex">
        <div class="part2-1">
        <h3>Let Us Introduce</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
             Ut enim ad minim veniam, quis nostrud exercitation ullamLorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
              incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamcoco</p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
             Ut enim ad minim veniam, quis nostrud exercitation ullamco
        </p>
        </div>
        <div class="part2-2">
            <div class="skill skill1">
            <div class="number1 flex">
            <p>Web Design</p>
            <p>85%</p>
            </div>
            <hr>
            </div>
            <div class="skill skill2">
            <div class="number1 flex">
            <p>Photography</p>
            <p>90%</p>
            </div>
            <hr>
            </div>
            <div class="skill skill3">
            <div class="number1 flex">
            <p>Content Marketing</p>
            <p>75%</p>
            </div>
            <hr>
            </div>
            <div class="skill skill4">
            <div class="number1 flex">
            <p>CMS Admin</p>
            <p>70%</p>
            </div>
            <hr>
            </div>
        </div>
        <div class="part2-3">
            <img src="assets/about-image.jpg">
        </div>
    </section>
    <section class="part3">
        <h3>Our Blog</h3>
        <div class="container">
            <div class="part3-1 flex">
                <div class="part3-2 flex">
                    <img src="assets/blog-image1.jpg">
                    <article>
                        <i class="far fa-clock">December22,2017</i>
                        <h4>How to find out beautiful Workplace</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <button class="bt1 bt3">
                            Read Article
                        </button>
                    </article>
                </div>
                <div class="part3-2 flex">
                    <img src="assets/blog-image2.jpg">
                    <article>
                        <i class="far fa-clock">December22,2017</i>
                        <h4>How to find out beautiful Workplace</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <button class="bt1 bt3">
                            Read Article
                        </button>
                    </article>
                </div>
            </div>
            <div class="part3-1 flex">
                <div class="part3-2 flex">
                    <img src="assets/blog-image3.jpg">
                    <article>
                        <i class="far fa-clock">December22,2017</i>
                        <h4>How to find out beautiful Workplace</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <button class="bt1 bt3">
                            Read Article
                        </button>
                    </article>
                </div>
                <div class="part3-2 flex">
                    <img src="assets/blog-image4.jpg">
                    <article>
                        <i class="far fa-clock">December22,2017</i>
                        <h4>How to find out beautiful Workplace</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <button class="bt1 bt3">
                            Read Article
                        </button>
                    </article>
                </div>
            </div>
        </div>     
    </section>
    <section class="part4 container">
        <h3>Our Work</h3>
        <div class="part4-1 flex">
            <img src="assets/work-image1.jpg">
            <img src="assets/work-image2.jpg">
            <img src="assets/work-image3.jpg">
            <img src="assets/work-image4.jpg">
        </div>
    </section> 
    <section class="part5">
        <div class="container">
            <h3>Contact Us</h3>
            <div class="part5-1 flex">
                <div class="form">
                    <div class="line1 flex">
                        <div class="name">
                        <h5>Your Name</h5>
                        </div>
                        <div class="name">
                        <h5>Your email</h5>
                        </div>
                    </div>
                    <div class="line1 flex">
                        <div class="name">
                        <h5>Your Phone</h5>
                        </div>
                        <div class="name">
                        <div class="budget flex">
                        <h5>Budgets</h5>
                        <i class="fas fa-sort"></i>
                        </div>
                        </div>
                    </div>
                    <div class="requirements">
                        <h5>Your requirements</h5>
                    </div>
                    <button class="bt1 bt4">
                         Send Message
                    </button>
                </div>
                <div class="map">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14691.947479210707!2d72.51771388798873!3d22.987510309532034!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x395e853112433981%3A0x7060b93a88f5a8cd!2sJuhapura%2C%20Ahmedabad%2C%20Gujarat!5e0!3m2!1sen!2sin!4v1634807731457!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <div class="footer-1 flex">
            <div class="footer-1-1">
                <h3>Hydro Company</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
                   ut labore et dolore magna aliqua
                </p>
            </div>
            <div class="footer-1-2">
                <h3>Company</h3>
                <ul>
                    <li>About Us</li>
                    <li>Join our Team</li>
                    <li>Read Blog</li>
                    <li>Press</li>
                </ul>
            </div>
            <div class="footer-1-2">
                <h3>Services</h3>
                <ul>
                    <li>Pricing</li>
                    <li>Documentation</li>
                    <li>Support</li>
                </ul>
            </div>
            <div class="footer-1-2">
                <h3>Contact Us</h3>
                <p>123 Grnad Something</p>
                <p>New York</p>
            </div>


            </div>
            <hr>
            <div class="footer-2 flex">
                <div class="copyright">
                    <p>Copyright AltCampus Company</p>
                </div>
                <div class="call-us flex">
                    <p>Call us</p>
                    <p>(+66)1326765</p>
                    <ul class="icon-f flex">
                        <li><a href="#"><i class="fab fa-facebook-square"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                    </ul>                        
                    </div>
                </div>

            </div>
        </div>
    </footer>
</body>
</html>
