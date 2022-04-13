W3 band from F8

Đây là dự án W3 band làm từ fullstack.edu.vn
# Nguồn 
- Themify icons: https://themify.me/themify-icons
- CDN themify icons: https://cdn.jsdelivr.net/gh/lykmapipo/themify-icons@0.1.2/css/themify-icons.css
- W3 band: https://www.w3schools.com/w3css/tryw3css_templates_band.htm

# Source code
## index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The band</title>
    <link rel="stylesheet" href="./assets/css/style.css">
    <link rel="stylesheet" href="./assets/css/responsive.css">
    <link rel="stylesheet" href="./assets/font/themify-icons/themify-icons.css">
</head>
<body>
    <div id="main">
        <div id="header">
            <!-- Begin: Nav -->
            <ul id="nav">
                <li><a href="#">Home</a></li>
                <li><a href="#band">Band</a></li>
                <li><a href="#tour">Tour</a></li>
                <li><a href="#contact">Contact</a></li>
                <li>
                    <a href="#">
                        More
                        <i class="nav-arrow-down ti-angle-down"></i>
                    </a>
                    <ul class="subnav">
                        <li><a href="#">Merchandise</a></li>
                        <li><a href="#">Extras</a></li>
                        <li><a href="#">Media</a></li>
                    </ul>
                </li>
            </ul>
            <!-- End: Nav -->

            <!-- Mobile menu button -->
            <div id="mobile-menu" class="mobile-menu-btn">
                <i class="menu-icon ti-menu"></i>
            </div>

            <!-- Search button -->
            <div class="search-btn">
                <i class="search-icon ti-search"></i>
            </div>
        </div>
    
        <div id="slider">
            <div class="text-content">
                <h2 class="text-heading">New York</h2>
                <div class="text-description">The atmosphere in New York is lorem ipsum.</div>
            </div>
        </div>
    
        <div id="content">
            <!-- About section -->
            <div id="band" class="content-section">
                <h2 class="section-heading">THE BAND</h2>
                <p class="section-sub-heading">We love music</p>
                <p class="about-text">
                    We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </p>
                <div class="row members-list">
                    <div class="col col-third s-col-full mt-32 text-center">
                        <p class="member-name">Name</p>
                        <img src="./assets/img/band/member1.jpg" alt="Name" class="member-img">
                    </div>
                    <div class="col col-third s-col-full mt-32 text-center">
                        <p class="member-name">Name</p>
                        <img src="./assets/img/band/member1.jpg" alt="Name" class="member-img">
                    </div>
                    <div class="col col-third s-col-full mt-32 text-center">
                        <p class="member-name">Name</p>
                        <img src="./assets/img/band/member1.jpg" alt="Name" class="member-img">
                    </div>
                </div>
            </div>

            <!-- Tour section -->
            <div id="tour" class="tour-section">
                <div class="content-section">
                    <h2 class="section-heading text-white">TOUR DATES</h2>
                    <p class="section-sub-heading text-white">Remember to book your tickets!</p>
                    
                    <!-- Tickets -->
                    <ul class="tickets-list">
                        <li>September <span class="sold-out">Sold out</span></li>
                        <li>October <span class="sold-out">Sold out</span></li>
                        <li>November <span class="quantity">3</span></li>
                    </ul>

                    <!-- Places -->
                    <div class="row places-list">
                        <div class="col col-third s-col-full mt-16">
                            <img src="./assets/img/places/place1.jpg" alt="New York" class="place-img">
                            <div class="place-body">
                                <h3 class="place-heading">New York</h3>
                                <p class="place-time">Fri 27 Nov 2016</p>
                                <p class="place-desc">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                                <button class="btn s-full-width js-buy-ticket">Buy Tickets</button>
                            </div>
                        </div>
                        <div class="col col-third s-col-full mt-16">
                            <img src="./assets/img/places/place2.jpg" alt="New York" class="place-img">
                            <div class="place-body">
                                <h3 class="place-heading">Paris</h3>
                                <p class="place-time">Sat 28 Nov 2016</p>
                                <p class="place-desc">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                                <button class="btn s-full-width js-buy-ticket">Buy Tickets</button>
                            </div>
                        </div>
                        <div class="col col-third s-col-full mt-16">
                            <img src="./assets/img/places/place3.jpg" alt="New York" class="place-img">
                            <div class="place-body">
                                <h3 class="place-heading">San Francisco</h3>
                                <p class="place-time">Sun 29 Nov 2016</p>
                                <p class="place-desc">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                                <button class="btn s-full-width js-buy-ticket">Buy Tickets</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Begin: Contact section -->
            <div id="contact" class="content-section">
                <h2 class="section-heading">CONTACT</h2>
                <p class="section-sub-heading">Fan? Drop a note!</p>
                
                <div class="row contact-content">
                    <div class="col col-half s-col-full contact-info">
                        <p><i class="ti-location-pin"></i>Chicago, US</p>
                        <p><i class="ti-mobile"></i>Phone: <a href="tel: +00 151515">+00 151515</a></p>
                        <p><i class="ti-email"></i>Email: <a href="mailto: mail@mail.com">mail@mail.com</a></p>
                    </div>
                    <div class="col col-half s-col-full contact-form">
                        <form action="">
                            <div class="row">
                                <div class="col col-half s-col-full">
                                    <input type="text" name="" placeholder="Name" required id="contact-name" class="form-control">
                                </div>
                                <div class="col col-half s-col-full s-mt-8">
                                    <input type="email" name="" placeholder="Email" required id="contact-email" class="form-control">
                                </div>
                            </div>
                            <div class="row mt-8">
                                <div class="col col-full">
                                    <input type="text" name="" placeholder="Message" required id="contact-message" class="form-control">
                                </div>
                            </div>
                            <input class="contact-submit-btn btn pull-right mt-16 s-full-width" type="submit" value="SEND">
                        </form>
                    </div>
                </div>
            </div>
            <!-- End: Contact section -->

            <div class="map-section">
                <img src="./assets/img/map.jpg" alt="Map">
            </div>
        </div>
    
        <div id="footer">
            <div class="socials-list">
                <a href=""><i class="ti-facebook"></i></a>
                <a href=""><i class="ti-instagram"></i></a>
                <a href=""><i class="ti-youtube"></i></a>
                <a href=""><i class="ti-pinterest"></i></a>
                <a href=""><i class="ti-twitter"></i></a>
                <a href=""><i class="ti-linkedin"></i></a>
            </div>
            <p class="copyright">Powered by <a href="#">w3.css</a></p>
        </div>
    </div>

    <div class="modal js-modal">
        <div class="modal-container js-modal-container">
            <div class="modal-close js-modal-close">
                <i class="ti-close"></i>
            </div>

            <header class="modal-header">
                <i class="modal-heading-icon ti-bag"></i>
                Tickets
            </header>

            <div class="modal-body">
                <label for="ticket-quantity" class="modal-label">
                    <i class="ti-shopping-cart"></i>
                    Tickets, $15 per person
                </label>
                <input id="ticket-quantity" type="text" class="modal-input" placeholder="How many?">

                <label for="ticket-email" class="modal-label">
                    <i class="ti-user"></i>
                    Send to
                </label>
                <input id="ticket-email" type="email" class="modal-input" placeholder="Enter email...">

                <button id="buy-tickets">
                    Pay <i class="ti-check"></i>
                </button>
            </div>

            <footer class="modal-footer">
                <p class="modal-help">Need <a href="#">help?</a></p>
            </footer>
        </div>
    </div>

    <script>
        var header = document.getElementById('header');
        var mobileMenu = document.getElementById('mobile-menu');
        var headerHeight = header.clientHeight;

        // Đóng/mở mobile menu
        mobileMenu.onclick = function() {
            var isClosed = header.clientHeight === headerHeight;
            if (isClosed) {
                header.style.height = 'auto';
            } else {
                header.style.height = null;
            }
        }

        // Tự động đóng khi chọn menu
        var menuItems = document.querySelectorAll('#nav li a[href*="#"]');
        for (var i = 0; i < menuItems.length; i++) {
            var menuItem = menuItems[i];
            
            menuItem.onclick = function(event) {
                var isParentMenu = this.nextElementSibling && this.nextElementSibling.classList.contains('subnav');
                if (!isParentMenu) {
                    header.style.height = null;
                } else {
                    event.preventDefault();
                }
            }
        }
    </script>

    <script>
        const buyBtns = document.querySelectorAll('.js-buy-ticket');
        const modal = document.querySelector('.js-modal');
        const modalContainer = document.querySelector('.js-modal-container')
        const modalClose = document.querySelector('.js-modal-close');

        // Hàm hiển thị modal mua vé (thêm class open vào modal)
        function showBuyTickets() {
            modal.classList.add('open');
        }

        // Hàm ẩn modal mua vé (gỡ bỏ class open của modal)
        function hideBuyTickets() {
            modal.classList.remove('open');
        }

        // Lặp qua từng thẻ button và nghe hành vi click
        for (const buyBtn of buyBtns) {
            buyBtn.addEventListener('click', showBuyTickets);
        }

        // Nghe hành vi click vào button close
        modalClose.addEventListener('click', hideBuyTickets);

        modal.addEventListener('click', hideBuyTickets);

        modalContainer.addEventListener('click', function (event) {
            event.stopPropagation();
        });
    </script>
</body>
</html>
```
## style.css
```css
/* Reset CSS */
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    font-family: Arial, Helvetica, sans-serif;
}

/* 
1. Từ ngoài vào trong
2. Từ trên xuống dưới
3. Tổng quan đến chi tiết
*/

/* 
1. Vị trí
2. Kích thước (width, height)
3. Màu sắc
4. Kiểu dáng (kiểu chữ, hình tròn, vuông, ...)
*/

/* Common */
.clear {
    clear: both;
}

.text-white {
    color: #fff !important;
}

.text-center {
    text-align: center !important;
}

.pull-right {
    float: right !important;
}

.btn {
    color: #fff;
    background-color: #000;
    text-decoration: none;
    padding: 11px 16px;
    display: inline-block;
    margin-top: 15px;
    border: none;
    text-align: center;
    appearance: none;
    -webkit-appearance: none;
}

.btn:hover {
    cursor: pointer;
    color: #000;
    background-color: #ccc;
}

.row {
    margin-left: -8px;
    margin-right: -8px;
}

.row::after {
    content: "";
    display: block;
    clear: both;
}

.col {
    float: left;
    padding-left: 8px;
    padding-right: 8px;
}

.col-full {
    width: 100%;
}

.col-half {
    width: 50%;
}

.col-third {
    width: 33.33333%;
}

.mt-8 {
    margin-top: 8px !important;
}

.mt-16 {
    margin-top: 16px !important;
}

.mt-32 {
    margin-top: 32px !important;
}

/* Main */
#main {

}

#header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    height: 46px;
    background-color: #000;
    z-index: 1;
}

#nav {
    display: inline-block;
}

#nav, .subnav {
    list-style-type: none;
}

#nav > li {
    display: inline-block;
}

#nav li {
    position: relative;
}

#nav > li > a {
    color: #fff;
    text-transform: uppercase;
}

#nav li a {
    text-decoration: none;
    line-height: 46px;
    padding: 0 24px;
    display: block;
}

#nav li:hover .subnav {
    display: block;
}

#nav > li:hover > a,
#nav .subnav li:hover a {
    color: #000;
    background-color: #ccc;
}

#nav .subnav {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    min-width: 160px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

#nav .subnav a {
    color: #000;
    padding: 0 12px;
    line-height: 38px;
}

#nav .nav-arrow-down {
    font-size: 14px;
}

#header .mobile-menu-btn {
    position: absolute;
    top: 0;
    right: 0;
    display: none;
}

#header .mobile-menu-btn,
#header .search-btn {
    float: right;
    padding: 0 21px;
}

#header .search-btn:hover {
    cursor: pointer;
    background-color: #f44336;
}

#header .mobile-menu-btn:hover {
    background-color: #ccc;
}

#header .mobile-menu-btn:hover .menu-icon {
    color: #000;
}

#header .menu-icon,
#header .search-icon {
    color: #fff;
    font-size: 20px;
    line-height: 46px;
}

#slider {
    position: relative;
    margin-top: 46px;
    padding-top: 50%;
    background: url('/assets/img/slider/slider1.jpg') top center / cover no-repeat;
}

#slider .text-content {
    position: relative;
    bottom: 47px;
    color: #fff;
    width: 100%;
    text-align: center;
}

#slider .text-heading {
    font-weight: 500;
    font-size: 24px;
}

#slider .text-description {
    font-size: 15px;
    margin-top: 25px;
    text-shadow: 0 0 1px #000;
}


#content {

}

#content .content-section {
    width: 800px;
    max-width: 100%;
    padding: 64px 0 112px;
    margin-left: auto;
    margin-right: auto;
    padding-left: 16px;
    padding-right: 16px;
}

#content .section-heading {
    font-size: 30px;
    font-weight: 500;
    text-align: center;
    letter-spacing: 4px;
}

#content .section-sub-heading {
    font-size: 15px;
    text-align: center;
    margin-top: 25px;
    font-style: italic;
    opacity: 0.6;
}

#content .about-text {
    margin-top: 25px;
    font-size: 15px;
    text-align: justify;
    line-height: 1.4;
}

#content .members-list {
    margin-top: 32px;
}

#content .member-name {
    font-size: 15px;
}

#content .member-img {
    width: 154px;
    margin-top: 15px;
    border-radius: 4px;
}

/* Tour section */
.tour-section {
    background-color: #000;
}

.tickets-list {
    margin-top: 40px;
    list-style: none;
    background-color: #fff;
}

.tickets-list li {
    color: #757575;
    font-size: 15px;
    padding: 11px 16px;
    border-bottom: 1px solid #ddd;
}

.tickets-list .sold-out {
    background-color: #f44336;
    color: #fff;
    padding: 3px 4px;
    margin-left: 16px;
}

.tickets-list .quantity {
    float: right;
    width: 24px;
    height: 24px;
    background: #000;
    color: #fff;
    border-radius: 50%;
    text-align: center;
    line-height: 24px;
    margin-top: -3px;
}

/* Places */
.places-list {
    margin-top: 16px;
}

.place-img {
    width: 100%;
    display: block;
}

.place-img:hover {
    opacity: 0.6;
}

.place-body {
    padding: 16px;
    font-size: 15px;
    background-color: #fff;
}

.place-heading {
    font-size: 15px;
    font-weight: 600;
}

.place-time {
    margin-top: 15px;
    color: #757575;     
}

.place-desc {
    margin-top: 15px;
    line-height: 1.4;
}

/* Contact from */
.contact-content {
    margin-top: 48px;
}

.contact-info {
    font-size: 18px;
    line-height: 1.5;
}

.contact-info i[class*="ti-"] {
    width: 30px;
    display: inline-block;
}

.contact-info a {
    color: #101aef;
    opacity: 0.8;
}

.contact-info a:hover {
    opacity: 1;
}

.contact-form {
    font-size: 15px;
}

.contact-form .form-control {
    padding: 10px;
    border: 1px solid #ccc;
    width: 100%;
}

/* Map section */
.map-section img {
    width: 100%;
}

/* Footer section */
#footer {
    padding: 64px 16px;
    text-align: center;
}

#footer .socials-list {
    font-size: 24px;
}

#footer .socials-list a {
    color: rgba(0, 0, 0, 0.6);
    text-decoration: none;
}

#footer .copyright a:hover,
#footer .socials-list a:hover {
    color: rgba(0, 0, 0, 0.4);
}

#footer .copyright {
    margin-top: 15px;
    color: rgba(0, 0, 0, 0.6);
}

#footer .copyright a {
    color: rgba(0, 0, 0, 0.6);
}

.modal {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(0, 0, 0, 0.4);
    align-items: center;
    justify-content: center;
    display: none;
}

.modal.open {
    display: flex;
}

.modal-container {
    background: #fff;
    width: 900px;
    max-width: calc(100% - 32px);
    min-height: 200px;
    position: relative;
    animation: modalFadeIn ease .5s;
}

.modal-header {
    background: #009688;
    height: 130px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 30px;
    color: #fff;
}

.modal-heading-icon {
    margin-right: 16px;
}

.modal-close:hover {
    opacity: 1;
}

.modal-close {
    position: absolute;
    right: 0;
    top: 0;
    color: #fff;
    padding: 12px;
    cursor: pointer;
    opacity: 0.8;
}

.modal-body {
    padding: 16px;
}

.modal-label {
    display: block;
    font-size: 15px;
    margin-bottom: 12px;
}

.modal-input {
    border: 1px solid #ccc;
    width: 100%;
    padding: 10px;
    font-size: 15px;
    margin-bottom: 24px;
}

#buy-tickets {
    background: #009688;
    border: none;
    color: #fff;
    width: 100%;
    font-size: 15px;
    text-transform: uppercase;
    padding: 18px;
    cursor: pointer;
}

#buy-tickets:hover {
    opacity: 0.9;
}

.modal-footer {
    padding: 16px;
    text-align: right;
}

.modal-footer a {
    color: #2196f3;
}

@keyframes modalFadeIn {
    from {
        opacity: 0;
        transform: translateY(-140px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```
## responsive.css
```css
/* PC */
@media (min-width: 64em) {

}

/* Tablet & mobile */
@media (max-width: 63.9375em) {
    .btn {
        padding: 15px 16px;
    }

    #nav .subnav a {
        padding: 5px 12px;
    }

    .contact-form .form-control {
        padding: 15px;
        font-size: 16px;
    }

    .contact-info {
        line-height: 2;
    }

    .contact-submit-btn {
        font-size: 17px;
    }

    .socials-list {
        font-size: 48px;
    }

    #footer .socials-list a {
        margin: 0 8px;
    }

    #footer .copyright a {
        padding: 12px 0;
        display: inline-block;
    }
}

/* Tablet */
@media (min-width: 46.25em) and (max-width: 63.9375em) {

}

/* Mobile */
@media (max-width: 46.1875em) {
    .s-full-width,
    .s-col-full {
        width: 100% !important;
    }

    .s-mt-8 {
        margin-top: 8px !important;
    }

    #header {
        overflow: hidden;
    }

    #header .mobile-menu-btn {
        display: block;
    }

    #header .search-btn {
        display: none;
    }

    #nav {
        display: block;
    }

    #nav li a {
        padding: 1px 24px;
    }
    
    #nav > li {
        display: block;
    }

    #nav > li:first-child {
        display: inline-block;
    }

    #nav .subnav {
        position: initial;
        background: #333;
    }

    #nav .subnav a {
        color: #fff;
        padding: 5px 41px;
    }

    #content .member-img {
        width: 60%;
    }

    .contact-form {
        margin-top: 32px;
    }
}
```
