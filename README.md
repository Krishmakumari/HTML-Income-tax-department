# HTML-Income-tax-department
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.1/css/fontawesome.min.css"
        crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <title>Income tax Department</title>
</head>

<body>
    <div class="top-bar">
        <div class="logo">
            <img src="logo itd.jpg" alt="logo">
        </div>
        <nav>
            <div class="toggle">
                <a href="#">
                    <ion-icon name="menu-outline"></ion-icon>
                </a>
            </div>
            <ul class="menu">
                <li><a class="active" href="#">HOME</a><br></li>
                <li><a href="#">ABOUT US</a><br></li>
                <li><a href="#">TAX PAYER SERVICES</a><br></li>
                <li><a href="#">FORMS DOWNLOAD</a><br></li>
                <li><a href="#">PUBLICITY CAMPAIGN</a><br></li>
                <li><a href="#">FEED BACK</a><br></li>
            </ul>
        </nav>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>

        <script>
            $(function () {
                $(".toggle").on("click", function () {
                    if ($(".menu").hasClass("active")) {
                        $(".menu").removeClass("active");
                        $(this).find("a").html("<ion-icon name='menu-outline'>");
                    } else {
                        $(".menu").addClass("active");
                        $(this).find("a").html("<ion-icon name='close-outline'>");
                    }
                })
            })
        </script>

    </div>

    <br><br><br>
    </header>
    <div id="content">
        <h4>

        </h4>

        <br><br><br>
    </div>


    <div>
        <h3>Our Committed Taxpayers<h3><br>
                To express gratitude towards committed taxpayers, the Income Tax Department has started a
                uniqueappreciation initiative.

                It recognizes taxpayer'5s commitment by awarding certificates of appreciation to them. The four
                categories of these certificates are: Platinum, Gold, Silver, and Bronze.
    </div>
    <br>
    <div>
        <table border="2px">


            <tr>

                <th>6148 Platinum</th>
                <th>2Lakh+Silver</th>
                <th>15827 Gold</th>
                <th>32Lakh+Bronze</th>
            </tr>
            <tr>
                <th>Certificate Winners</th>
                <th>Certificate Winners</th>
                <th>Certificate Winners</th>
                <th>Certificate Winners</th>
            </tr>

        </table>
    </div>
    <br><br><br><br><br>
    <div class="shadowbox">
        <div id="items">
            <h2>SERVICES</h2><br>
        </div>
        <table>
            <thead>
                <tr>
                    <th>
                        <h3 class="upper">TAX INFORMATION AND SERVICES</h3><br>
                    </th>
                    <th>
                        <h3 class="upper">TAX LAWS AND RULES</h3><br>
                    </th>
                    <th>
                        <h3 class="upper">INTERNATIONAL TAXATION</h3><br>
                    </th>
                </tr>
            </thead>


            <tbody>
                <tr>
                    <td>
                        <a href="">Tax
                            Tools</a><br><br>
                        <br>

                        <a href="">Tax
                            Tutorials</a><br><br>
                        <br>
                        <a href="">Tax
                            Charts and Tables</a><br><br>
                        <br>
                        <a href="">Tax Offices</a><br>
                    </td>


                    <td>
                        <a href="">Acts</a><br><br>
                        <br>
                        <a href="">Rules</a><br><br>
                        <br>
                        <a href="">Circulars</a><br><br>
                        <br>
                        <a href="">Notifications</a><br>
                    </td>

                    <td>
                        <a href="">Tax treaties</a><br><br>
                        <br>
                        <a href="">withholding tax</a><br><br>
                        <br>
                        <a href="">Provision-Non Resident</a><br><br>
                        <br>
                        <a href="">Exchange of Information</a><br>
                    </td>
                </tr>
            </tbody>
        </table>
    </div><br><br><br>
    <div class="container">
        <div class="tax">
            <h3>How We Can Help You</h3><br><br>
            <table>

                <a href="#">Sign into Your Account</a><br><br><br>
                <a href="#">Get Your Tax Record</a><br><br><br>
                <a href="#">Apply for an Employer ID Number (EIN)</a><br><br><br>
                <a href="#">Get Your Refund Status</a><br><br><br>
                <a href="#">Check Your Amended Return Status
                </a><br><br><br>
                <a href="#">Get Answers to Your Tax Questions</a><br><br><br>
                <a href="#">Tax Professionals: Renew Your PTIN
                </a><br><br><br>
            </table>
        </div>

        <div class="tax">
            <table>
                <thead>
                    <tr>
                        <h3>Resolve an issue</h3>
                    </tr> <br><br>
                </thead>
                <tbody>
                    <a href="#">RESOLVE AN ISSUE</a><br><br><br>
                    <a href="#">IRS Notices and Letters</a><br><br><br>
                    <a href="#">Identity Theft</a><br><br><br>
                    <a href="#">Phishing</a><br><br><br>
                    <a href="#">Tax Fraud</a><br><br><br>
                    <a href="#">Criminal Investigation</a><br><br><br>
                    <a href="#">Whistleblower Office</a><br><br><br>
                </tbody>
            </table>
        </div>
    </div>
    <br>
    <br>


    <div class="heading">
        <h2 class="heading">Check out this demonstration</h2><br>
        <main class="main">

            <section class="left section">
                <p>In order to understand how to make tax payment using E-pay tax functionality, refer to this video.
                </p>
            </section>
            <section class="right section">

                <iframe width="750" height="515" src="https://www.youtube.com/embed/jtuoi7FQiIc"
                    title="YouTube video player" frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    controls></iframe> <br>
            </section>
        </main>
    </div><br><br>
    <div class="section-container">
        <div class="column">
            <h2>Pay Your Tax</h2>
            <br>
            <h5>FROM</h5><br>
            <input type="date" placeholder="FROM"><br><br>
            <h5>TO</h5><br>
            <input type="date" placeholder="TO"><br><br><br>
            <h5>Mode Of Payement</h5><br>
            <form action="form.php">
                <label for="sectionida">
                    <input type="radio" value="UPI" name="payement" id="sectionida">UPI
                </label>
                <label for="sectionidb">
                    <input type="radio" value="CARD" name="payement" id="sectionidb">CARD
                </label>
                <label for="sectionidc">
                    <input type="radio" value="NET BANKING" name="payement" id="sectionidc">NET BANKING
                </label>
            </form>
            <br><br><br>
            <input type="submit">
        </div>

        <div class="content-container">
            <p>The Income Tax Department (also referred to as IT Department or ITD) is a government agency undertaking
                direct tax
                collection of the government of India. It functions under the Department of Revenue of the Ministry of
                Finance. The
                Income Tax Department is headed by the apex body Central Board of Direct Taxes (CBDT). The main
                responsibility of
                the Income Tax Department is to enforce various direct tax laws, most important among these being the
                Income-tax
                Act, 1961, to collect revenue for the government of India. It also enforces other economic laws such as
                the
                Benami
                Transactions (Prohibition) Act, 1988, and the Black Money Act, 2015.
            </p>
        </div>
    </div>
    <br>
    <br>
    <div class="contactUs">
        <div class="title">
            <h2>Get in touch</h2>
        </div>
        <div class="box">
            <div class="contact form">
                <h3> Send your query</h3>
                <form>
                    <div class="formbox">
                        <div class="row50">
                            <div class="inputbox">
                                <span>First Name</span>
                                <input type="text" placeholder=" first name">
                            </div>
                            <div class="inputbox">
                                <span>Last name</span>
                                <input type="text" placeholder="last name">
                            </div>
                        </div>

                        <div class="row50">
                            <div class="inputbox">
                                <span>E-mail</span>
                                <input type="text" placeholder="abc@gmail.com">
                            </div>
                            <div class="inputbox">
                                <span>Mobile</span>
                                <input type="text" placeholder="**********">
                            </div>
                        </div>
                        <div class="row100">
                            <div class="inputbox">
                                <span>Message</span>
                                <textarea placeholder="write your message here...."></textarea>
                            </div>
                        </div>
                        <div class="row100">
                            <div class="inputbox">
                                <input type="submit" value="Send">
                            </div>
                        </div>
                </form>
            </div>
        </div>
        <div class="contact info">
            <h3>Contact info</h3>
            <div class="infobox">
                <div>
                    <span>
                        <ion-icon name="location"></ion-icon>
                    </span>
                    <p>38-BLOCK LPU,PHAGWARA-PUNJAB</p>
                </div>
                <div>
                    <span>
                        <ion-icon name="mail"></ion-icon>
                    </span>
                    <a href="mailto:shivamraj.0110@gmail.com">shivamraj.0110@gmail.com</a>
                </div>
                <div>
                    <span>
                        <ion-icon name="call"></ion-icon>
                    </span>
                    <a href="mailto:+951-753-246"> 951-753-246</a>
                </div>
                <ul class="sci">
                    <li><a href="#">
                            <ion-icon name="logo-facebook"></ion-icon>
                        </a></li>
                    <li><a href="#">
                            <ion-icon name="logo-twitter"></ion-icon>
                        </a></li>
                    <li><a href="#">
                            <ion-icon name="logo-linkedin"></ion-icon>
                        </a></li>
                    <li><a href="#">
                            <ion-icon name="logo-instagram"></ion-icon>
                        </a></li>
                </ul>
                <div class="contact map">
                    <iframe
                        src="https://maps.google.com/maps?width=600&amp;height=400&amp;hl=en&amp;q=lpu&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
                        style="border:0"></iframe>
                </div>
            </div>
        </div>
        <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
        <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>





</body>

</html>
