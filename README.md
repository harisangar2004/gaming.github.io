<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="GAME_PAGE_C.css">
    <script src="https://kit.fontawesome.com/b30b07921b.js" crossorigin="anonymous"></script>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">

    <title>GAMES_PAGE</title>
    <script>

    </script>
</head>

<body>
    <!-- header section starts -->
    <header>
        <!-- Navbar starts -->
        <nav class="navbar navbar-expand-sm bg-dark" id="navbar">
            <div class="container-fluid" id="container-fluid">
                <a class="navbar-brand" href="#" id="navbar-brand">Logo</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#collapsibleNavbar">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="collapsibleNavbar">
                    <ul class="navbar-nav" id="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">FAQs</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Reviews</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Logout</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- Navbar ends -->

        <!-- Sidebar starts -->
        <div id="sidebar" onclick="toggleMenu()">
            <div class="toggle-btn">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <ul>
                <li>Game 1</li>
                <li>Game 2</li>
                <li>Game 3</li>
            </ul>
        </div>

        <!-- Sidebar ends -->

    </header>
    <!--  1677b48e4baac0fb95f7842e55ae868ea6082cf5 -->
    <div id="container">

        <div id="left-box">
            <div id="li">
                <!-- <i class = "fa-regular fa-circle-xmark" id = "min" style="display: inline-block;"></i> -->
                <div id="lbi" style="display: inline-block;">&ensp;&ensp;GAMES SECTION</div>
            </div>
            <div id="list">
                <br><button id="XOU" onclick="please_work_u()" class="button" style="">XO - 1v1</button>
                <br><br>
                <button id="XOC" onclick="please_work_c()" class="button" style="">XO - UvC</button>
            </div>
        </div>

        <div id="center-box">
            <div id="cbi">&ensp;&ensp;GAME PLAY</div>
        </div>
        <div id="right-box"></div>
    </div>
    <!-- jquery cdn link -->

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.0/jquery.min.js"></script>
    <script type="text/javascript" src="GAME_PAGE_J.js"></script>
</body>

</html>
