# NetflixhomepageUI
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
   <link rel="stylesheet" href="">
</head>
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: black;
    color: #ffffff;

}

.navigation {
    font-size: 20px;
    /* display: flex; */
    /* text-align: right; */
    /* list-style: none; */
    padding: 7.8px 13px;
    background-color: red;
    border-radius: 5px;
    color: white;
    bottom: 0;
    /* margin: 24px; */
}


/* button {
    list-style: none;
    padding: 20px 23px;
} */

section {
    height: 344px;
    justify-content: center;
    margin: 3px 23px;
    display: flex;
    flex-direction: column;
    align-items: center;
    /* border: 2px solid red; */
}

h1 {
    font-size: 4rem;
}

/* header {
   
} */

header::before {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    background: url(https://assets.nflxext.com/ffe/siteui/vlv3/9db4a880-3034-4e98-bdea-5d983e86bf52/b5953637-091d-4e02-9754-2bfadc8a8f7c/IN-en-20230925-popsignuptwoweeks-perspective_alpha_website_large.jpg) no-repeat center;
    /* this will make our text come up of the image */
    top: 0;
    left: 0;
    opacity: 0.5;
}

h2 {
    font-size: 34px;
}

.container {
    height: 34px;
    width: 533px;
    /* justify-content: center; */
    /* margin: 30px 20px; */
    display: flex;
    /* align-self: center; */
  padding-left: 400px;
}

#button {
    background-color: red;
    width: 500px;
    height: 39px;
    border-radius: 8px;
    border: red;
}

#language {
    background-color: transparent;
    color: white;
    padding: 10px 13px;
    border-radius: 4px;
}

.p1 {
    margin: 34px;
    text-align: right;

}

.netflix {

    /* z-index: 1; */
    background-color: transparent;
    width: 50%;
}

img {
    height: 77px;
    margin: 30px;
    display: block;

}

#div1 {
    width: 50%;
    margin-left: 700px;
    margin-top: -100px;
}

#email {
    border-radius: 8px;
    width: 1300px;
    height: 35px;
    margin-right: 0.7px;
    background-color: transparent;
    color: white;

}
</style>

<body>
    <header>
        <div class="p1">
            <div class="netflix">
                <img src="https://cdn.usbrandcolors.com/images/logos/netflix-logo.svg" alt="error">
            </div>

            <!-- drop down -->
            <div id="div1">
                <label for="language"></label>
                <select name="language" id="language">
                    <option value="english">English</option>
                    <option value="Hindi">Hindi</option>
                </select>
                <button class="navigation">Sign In</button>
            </div>
        </div>


    </header>

    <section>
        <h1 data-uia="nmhp-card-hero-text-title" class="default-ltr-cache-jpuyb8 e9eyrqp8">Enjoy big movies, hit series
            and more from ₹&nbsp;149.</h1>
        <h2 data-uia="nmhp-card-hero-text-subtitle" class="default-ltr-cache-10i4ild e9eyrqp7">Join today. Cancel
            anytime.</h2>
        <h2>Ready to watch? Enter your email to create or restart your membership.</h2>
    </section>

    <div class="container">
        <label for="email" id="email"><b></b></label>
        <input type="text" placeholder="Email address" id="email">
        <button type="button" id="button"> Get Started ></button>
        <div>


</body>

</html>
