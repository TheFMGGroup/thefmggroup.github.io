<html>
<head>
<link rel="stylesheet" href="stylesheet.css">
<title>A testing area- Wow!</title>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <title>Dark Mode Toggle</title>
    <meta charset="utf-8">
    <meta name="description" content="Dark Mode Toggle Example">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="keywords" content="Dark Mode Toggle Example">
	<meta name="author" content="Henry Egloff">
	
    <style>

    	
		/* Light Mode Button
		--------------------------- */ 

		.light-mode-button {
			background:0;
		    border: 0;
		    box-sizing: border-box;
		    cursor: pointer;
		    width: 30px;
		    height: 16px;
		    position: relative;
		    border: 1px solid rgba(255,255,255,0);

		    /* Fixed position for this demo */
		    position: fixed;
		    top:16px;
		    right:16px;
		}

		.light-mode-button:focus {
			outline:none; /* Not ideal for accessibility */
		}

		.light-mode-button span:nth-child(1) {
			position: absolute;
			top:0;
		    left:0;
		    width: 30px;
		    height:16px;
		    background-color: #d6d7db;
		    border-radius: 9px;
		    box-shadow: inset 1px 1px 3px 0 rgb(0 0 0 / 40%);
		    transition: .3s;
		}

		.light-mode-button span:nth-child(2) {
			position: absolute;
			top:3px;
		    left:3px;
		    width: 10px;
		    height: 10px;
		    background-color: #fff;
		    border-radius: 50%;
		    box-shadow: 1px 1px 2px 0 rgb(0 0 0 / 40%);
		    transition: .3s;
		}


		/* Light & Dark Mode Styles
		--------------------------- */ 

		body {
			background-color: #f6f6f6;
            transition: background-color .3s;
        }

		body[light-mode=dark] {
            background-color: #141516;
            color: #ced4e2;
        }

        body[light-mode="dark"] .light-mode-button span:nth-child(1){
            background-color: #ced4e2;
            color: #141516;
        }

        body[light-mode=dark] .light-mode-button span:nth-child(2) {
		    left: 17px;
		    background-color: #141516;
		}


    </style>
</head>

<body light-mode="light">

    <script>
        var app = document.getElementsByTagName("BODY")[0];
        if (localStorage.lightMode == "dark") {
            app.setAttribute("light-mode", "dark");
        }
    </script>


	<button class="light-mode-button" aria-label="Toggle Light Mode" onclick="toggle_light_mode()">
    	<span></span>
    	<span></span>
    </button> 


    <script>
		
        function toggle_light_mode() {
            var app = document.getElementsByTagName("BODY")[0];
            if (localStorage.lightMode == "dark") {
                localStorage.lightMode = "light";
                app.setAttribute("light-mode", "light");
            } else {
                localStorage.lightMode = "dark";
                app.setAttribute("light-mode", "dark");
            }       
        }

		window.addEventListener("storage", function () {
			if (localStorage.lightMode == "dark") {
				app.setAttribute("light-mode", "dark");
			} else {
				app.setAttribute("light-mode", "light");
			}
		}, false);
		
    </script>

  <body light-mode="light">

    <script>
        var app = document.getElementsByTagName("BODY")[0];
        if (localStorage.lightMode == "dark") {
            app.setAttribute("light-mode", "dark");
        }
    </script>


	<button class="light-mode-button" aria-label="Toggle Light Mode" onclick="toggle_light_mode()">
    	<span></span>
    	<span></span>
    </button> 


    <script>
		
        function toggle_light_mode() {
            var app = document.getElementsByTagName("BODY")[0];
            if (localStorage.lightMode == "dark") {
                localStorage.lightMode = "light";
                app.setAttribute("light-mode", "light");
            } else {
                localStorage.lightMode = "dark";
                app.setAttribute("light-mode", "dark");
            }       
        }

		window.addEventListener("storage", function () {
			if (localStorage.lightMode == "dark") {
				app.setAttribute("light-mode", "dark");
			} else {
				app.setAttribute("light-mode", "light");
			}
		}, false);
		
    </script>


<div class="topnav">
  <a class="active" href="#home">Home</a>
  <a href="https://thefmggroup.github.io/wikiarchive">Wikipedia Archives</a>
  <a href="contact">Contact</a>
  <a href="about">About</a>
</div> 
    
<p>A website for stuff 2021-2021</p>

<h1>Any FMG Group News</h1>
 
<img src="https://generated.inspirobot.me/a/bRelEYmaJ7.jpg" alt="Inspiration" class="center" style="width:500px;height:600px;">

<h1>Stuff</h1>

<p>
In this website I will be doing tests please ignore anything labeled test.
.A part from that this is a normal wesite coded in HTML.
</p>
<p><h2><a href="https://www.speedtest.net">Speedtest.net</a></h2></p>
<img class="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flogos-download.com%2Fwp-content%2Fuploads%2F2016%2F09%2FGitHub_logo.png&f=1&nofb=1">
    
<p>This website may be alone of not being updated for days, weeks or even months but I never leave a project unfinished </p>
    
<p>Eventually we will tranfer to HTML6 when that comes out in about 6 months</p>        
    
    
<p>ON THIS WEBSTIE YOU WILL SEE SOME ISSUES AND WHAT NOT BUT NOTHING TO MUCH IT IS ONLY A BIG TEST.</p>



<p>You will also see the source code and documents for things think of this sometimes as a long winded google effort, just badly made</p>
 
<h1><a href="/wikiarchive">Wikipedia Archives</a></h1>
    
<h1> Staff </h1>
<h2><a href="/dakrustyboi">dakrustyboi- technical jargon, bug fixing, writing?</a></h2>
<h2><a href="https://www.youtube.com/channel/UC1NEDcS-XrFCURxCAwValZw">Deddit- writing, maintainance, technical jargon</a></h2>

</body>
</html>
