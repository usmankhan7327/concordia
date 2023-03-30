<template>
    <header id="header" data-transparent="true" data-fullwidth="true" class="dark submenu-light">
        <div class="header-inner">
            <div class="container">
                <!--Logo-->
                <div id="logo">
                    <a href="#">
                        <span class="logo-default"><img src="/images/logo.png" height="90px" width="128"></span>
                        <span class="logo-dark"><img src="/images/logo.png" height="90px" width="128"></span>
                    </a>
                </div>
                <!--End: Logo-->
                <!-- Search -->
                <div id="search"><a id="btn-search-close" class="btn-search-close" aria-label="Close search form"><i class="icon-x"></i></a>
                    <form class="search-form" action="search-results-page.html" method="get">
                        <input class="form-control" name="q" type="text" placeholder="Type & Search..." />
                        <span class="text-muted">Start typing & press "Enter" or "ESC" to close</span>
                    </form>
                </div>
                <!-- end: search -->
                <!--Header Extras-->
                <div class="header-extras">
                    <ul>
                        <li>
                            <a id="btn-search" href="#"> <i class="icon-search"></i></a>
                        </li>
                        <li>
                            <div class="p-dropdown">
                                <a href="#"><i class="icon-globe"></i><span>EN</span></a>
                                <ul class="p-dropdown-content">
                                    <li><a href="#">French</a></li>
                                    <li><a href="#">Spanish</a></li>
                                    <li><a href="#">English</a></li>
                                </ul>
                            </div>
                        </li>
                    </ul>
                </div>
                <!--end: Header Extras-->
                <!--Navigation Resposnive Trigger-->
                <div id="mainMenu-trigger">
                    <a class="lines-button x"><span class="lines"></span></a>
                </div>
                <!--end: Navigation Resposnive Trigger-->
                <!--Navigation-->
                <div id="mainMenu">
                    <div class="container">
                        <nav>
                            <ul>
                                <li><a href="#">Home</a></li>
                                <li class=""><a href="#welcome">About</a>
                                </li>
                                <li class=""><a href="#feature">Features</a>
<!--                                    <ul class="dropdown-menu">-->
<!--                                        <li class="dropdown-submenu"><a href="#">Sliders</a>-->
<!--                                            <ul class="dropdown-menu">-->
<!--                                                <li><a href="slider-revolution-slider.html">Revolution Slider</a></li>-->
<!--                                                <li><a href="slider-inspiro-slider.html">Inspiro Slider</a></li>-->
<!--                                                <li><a href="slider-static-media-image.html">Fullscreen Image</a></li>-->
<!--                                                <li><a href="slider-static-media-parallax.html">Fullscreen Parallax</a></li>-->
<!--                                                <li><a href="slider-static-media-text-rotator.html">Fullscreen Text Rotator</a></li>-->
<!--                                                <li><a href="slider-static-media-video.html">Fullscreen HTML5 Video</a></li>-->
<!--                                            </ul>-->
<!--                                        </li>-->
<!--                                        <li><a href="widgets.html">Widgets</a></li>-->
<!--                                        <li><a href="page-loaders.html">Page Loaders<span class="badge bg-danger">NEW</span></a></li>-->
<!--                                        <li class="dropdown-submenu"><a href="#">Modal Auto Open<span class="badge bg-danger">NEW</span></a>-->
<!--                                            <ul class="dropdown-menu">-->
<!--                                                <li><a href="modal-auto-open-subscription.html">Subscription</a></li>-->
<!--                                                <li><a href="modal-auto-open-shop.html">Shop Promotion</a></li>-->
<!--                                                <li><a href="modal-auto-open-login.html">Login Form</a></li>-->
<!--                                                <li><a href="modal-auto-open-audio.html">Audio Player</a></li>-->
<!--                                                <li><a href="modal-auto-open-video.html">HTML5 Video</a></li>-->
<!--                                                <li><a href="modal-auto-open-youtube.html">YouTube Video</a></li>-->
<!--                                                <li><a href="modal-auto-open-vimeo.html">Vimeo Video</a></li>-->
<!--                                                <li><a href="modal-auto-open-iframe.html">Iframe</a></li>-->
<!--                                                <li><a href="modal-auto-open.html">Sample Text</a></li>-->
<!--                                            </ul>-->
<!--                                        </li>-->
<!--                                        <li class="dropdown-submenu"><a href="#">Cookie Notify<span class="badge bg-danger">NEW</span></a>-->
<!--                                            <ul class="dropdown-menu">-->
<!--                                                <li><a href="cookie-notify.html">Top position</a></li>-->
<!--                                                <li><a href="cookie-notify-bottom.html">Bottom position</a></li>-->
<!--                                            </ul>-->
<!--                                        </li>-->
<!--                                        <li><a href="shape-dividers.html">Shape Dividers<span class="badge bg-danger">NEW</span></a></li>-->
<!--                                        <li class="dropdown-submenu"><a href="#">Menu Labels</a>-->
<!--                                            <ul class="dropdown-menu">-->
<!--                                                <li><a href="#">Label (new)<span class="badge bg-danger">NEW</span></a></li>-->
<!--                                                <li><a href="#">Label (hot)<span class="badge bg-danger">HOT</span></a></li>-->
<!--                                                <li><a href="#">Label (popular)<span class="badge bg-success">POPULAR</span></a></li>-->
<!--                                                <li><a href="#">Label (sale)<span class="badge bg-warning">SALE</span></a></li>-->
<!--                                                <li><a href="#">Label (info)<span class="badge bg-info">INFO</span></a></li>-->
<!--                                            </ul>-->
<!--                                        </li>-->
<!--                                    </ul>-->
                                </li>
                                <li class=""><a href="#services">Services</a>
                                </li>
                                <li class=""><a href="#clients">Clients</a>
                                </li>
                                <li class=""><a href="#teams">Teams</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div>
                <!--end: Navigation-->
            </div>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>

</style>
