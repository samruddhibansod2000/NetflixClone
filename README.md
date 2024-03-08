# NetflixClone
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>netflix</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;

        }

        body {
            background-color: black;
            color: white;
        }

        main section #body {
            width: 100%;
            height: 100vh;
            background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url(./divimg1.jpg);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        main section div nav img {
            height: 40px;
            width: 150px;
            margin: 20px 20px 0 20px;
        }

        main section div nav select.btn {
            height: 30px;
            width: 100px;
            margin-left: 900px;
            text-decoration: none;
            color: white;
            font-size: 20px;
            background-color: black;
            border-radius: 10px;
        }

        main section div nav #btn2 {
            background-color: red;
            border-color: black;
            height: 30px;
            width: 100px;
            font-size: 15px;
        }

        #hed1 {
            text-align: center;
            font-size: 40px;
            margin: 190px auto 20px;
            color: white;
        }

        #hed2 {
            text-align: center;
            font-size: 20px;
            color: white;
            margin-top: 20px;
        }

        p {
            text-align: center;
            margin-top: 20px;
            font-size: 20px;
        }

        .sign {
            text-align: center;
        }

        #inp1 {
            height: 50px;
            width: 300px;
            padding: 10px;
            margin: 20px;
            color: white;
            background-color: black;
            border-color: gray;
            border-radius: 4px;
        }

        .headbtn {
            background-color: red;
            height: 50px;
            width: 100px;
            color: white;
            border-radius: 4px;
        }

        .headbtn:hover {
            background-color: rgba(255, 0, 0, 0.7);

        }

        .container {
            width: 100%;
            font-size: 30px;
            align-items: center;
            display: flex;
            padding: 50px;
            margin: 200px 10px;

        }

        h3 {
            font-size: 50px;
            text-align: center;
            margin: 50px auto;
        }

        .child {
            height: 70px;
            width: 900px;
            border: 1px solid;
            border-color: rgb(59, 58, 58) transparent;
            background-color: rgb(59, 58, 58);
            margin: 10px auto;
            color: white;

        }

        .child:hover {
            background-color: rgba(136, 134, 134, 0.7);
        }

        h4 {
            font-size: 13px;
            flex-wrap: wrap;
            background-color: rgb(59, 58, 58);
        }

        summary {
            line-height: 70px;
        }


        .link {
            margin: 30px;
            /* font-size: 20px;*/
        }

        #title {
            font-size: 18px;
            font-weight: 400;
            margin-bottom: 30px;

        }

        .link .tag {
            margin-bottom: 20px;
        }

        a {
            color: white;
            margin-bottom: 10px;
            display: block;
            font-size: 20px;
            text-decoration: none;
        }

        td {
            padding: 30px;
        }

        #linkbtn {
            background-color: black;
            color: white;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <main>
        <section>
            <div id="body">
                <nav>
                    <img src="./netflix.logo.png" alt="no image">
                    <select name="" id="" class="btn">
                        <option value="">English</option>
                        <option value="">Hindi</option>
                    </select>
                    <button type="button" onclick="alert('Sign In')" id="btn2" class="btn">Sign In</button>
                    <header>
                        <h1 class="header" id="hed1"><b>Unlimited movies, TV shows and more</b></h1>
                        <h5 class="header" id="hed2">Watch anywhere. Cancel anytime.</h5>
                        <p>Ready to watch? Enter your email to create or restart your membership.</p>
                        <form action="" class="sign">
                            <input id="inp1" placeholder="Email Address" type="text ">
                            <button class="headbtn" type="submit"><b>Get Started</b></button>
                        </form>
                    </header>
                </nav>
            </div>

            <div id="container2" class="container">
                <div>
                    <h2>Enjoy on your TV</h2>
                    <h5>Watch on smart TVs, PlayStation, Xbox,Chromecast,Apple TV, Blu-ray players and more.</h5>
                </div>
                <div class="img">
                    <img id="tv" src="./tv.png" alt="">
                </div>

            </div>

            <hr>

            <div id="container3" class="container">
                <div class="img">
                    <img class="img" id="imgcont3" src="./container3.jpg" alt="">
                </div>
                <div>
                    <h2>Download your shows to watch offline</h2>
                    <h5>Save your favourites easily and always have something to watch.</h5>
                </div>
            </div>

            <hr>

            <div id="container4" class="container">
                <div>
                    <h2>Watch everywhere</h2>
                    <h5>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</h5>
                </div>
                <div>
                    <img class="img" id="watchtv" src="./watchtv.png" alt="">
                </div>
            </div>

            <hr>

            <div id="container3" class="container">
                <div class="img">
                    <img class="img" id="imgcont3" src="./children.png" alt="">
                </div>
                <div>
                    <h2>Create profiles for kids</h2>
                    <h5>Send children on adventures with their favourite characters in a space made just for them—free
                        with your membership.</h5>
                </div>
            </div>

            <hr>

            <div id="container3" class="details">
                <h3>Frequently Asked Questions</h3>
                <div class="box">
                    <div class="child" id="child1">
                        <details>
                            <summary>What is Netflix?</summary>
                            <h4>Netflix is a streaming service that offers a wide variety of award-winning TV shows,
                                movies, anime, documentaries and more – on thousands of internet-connected devices.
                                You can watch as much as you want, whenever you want, without a single ad – all for one
                                low monthly price. There's always something new to discover, and new TV shows and movies
                                are added every week!</h4>
                        </details>
                    </div>
                    <br>
                    <div class="child" id="child2">
                        <details>
                            <summary>How much does Netflix cost?</summary>
                            <h4>Watch Netflix on your smartphone, tablet, Smart TV, laptop, or streaming device, all for
                                one fixed monthly fee. Plans range from ₹ 149 to ₹ 649 a month. No extra costs, no
                                contracts.</h4>
                        </details>
                    </div>
                    <br>
                    <div class="child" id="child3">
                        <details>
                            <summary>Where can I Watch?</summary>
                            <h4>Watch anywhere, anytime. Sign in with your Netflix account to watch instantly on the web
                                at netflix.com from your personal computer or on any internet-connected device that
                                offers the Netflix app, including smart TVs, smartphones, tablets, streaming media
                                players and game consoles.
                                You can also download your favourite shows with the iOS, Android, or Windows 10 app. Use
                                downloads to watch while you're on the go and without an internet connection. Take
                                Netflix with you anywhere.</h4>
                        </details>
                    </div>
                    <br>
                    <div class="child" id="child4">
                        <details>
                            <summary>How do I cancel?</summary>
                            <h4>Netflix is flexible. There are no annoying contracts and no commitments. You can easily
                                cancel your account online in two clicks. There are no cancellation fees – start or stop
                                your account anytime.</h4>
                        </details>
                    </div>
                    <br>
                    <div class="child" id="child5">
                        <details>
                            <summary>What can I Watch on Netflix?</summary>
                            <h4>Netflix has an extensive library of feature films, documentaries, TV shows, anime,
                                award-winning Netflix originals, and more. Watch as much as you want, anytime you want.
                            </h4>
                        </details>
                    </div>
                    <br>
                    <div class="child" id="child6">
                        <details>
                            <summary>Is Netflix good for kids?</summary>
                            <h4>The Netflix Kids experience is included in your membership to give parents control while
                                kids enjoy family-friendly TV shows and films in their own space.
                                Kids profiles come with PIN-protected parental controls that let you restrict the
                                maturity rating of content kids can watch and block specific titles you don’t want kids
                                to see.</h4>
                        </details>
                    </div>

                </div>
                <p>Ready to watch? Enter your email to create or restart your membership.</p>
                <form action="" class="sign">
                    <input id="inp1" placeholder="Email Address" type="text ">
                    <button class="headbtn" type="submit"><b>Get Started</b></button>
                </form>

            </div>

            <hr>

            <div id="container4" class="link">
                <a href="" id="title">Questions? Call 000-800-919-1694 </a>
                <table>
                    <tr>
                        <td>
                            <div class="tag">
                                <a href="">FAQ</a>
                                <a href="">Investor Relation</a>
                                <a href="">Privacy</a>
                                <a href="">Speed Test</a>
                            </div>
                            <select name="" id="linkbtn" class="btn">
                                <option value="">English</option>
                                <option value="">Hindi</option>
                            </select>
                            <h6 class="net_ind">Netflix India</h6>
                        </td>

                        <td>
                            <div class="tag">
                                <a href="">Help Centre</a>
                                <a href="">Jobs</a>
                                <a href="">Cookie Preferences</a>
                                <a href="">Legal Notices</a>
                            </div>
                        </td>
                        <td>
                            <div class="tag">
                                <a href="">Account</a>
                                <a href="">Ways to Watch</a>
                                <a href="">Corporate Information</a>
                                <a href="">Only on Netflix</a>
                            </div>
                        </td>
                        <td>
                            <div class="tag">
                                <a href="">Media Centre</a>
                                <a href="">Terms of Use</a>
                                <a href="">Contact Us</a>
                            </div>
                        </td>
                    </tr>
                </table>

            </div>




        </section>
    </main>
</body>

</html>
