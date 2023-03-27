<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thực Phẩm Chay Vegan</title>

    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="style.css">

</head>
<body>
    
<!-- header section starts  -->

<header>

    <div id="menu-bar" class="fas fa-bars"></div>

    <a href="#" class="logo"><span>Vegan</span> Organic</a>

    <nav class="navbar">
        <a href="#home">Trang Chủ</a>
        <a href="#gioithieu">Giới thiệu</a>
        <a href="#sanpham">Sản phẩm</a>
        <a href="#tintuc">Tin tức</a>
        <a href="#lienhe">Liên Hệ</a>
        <a href="#rlienhe">Hệ thống phân phối</a>
        
    </nav>

    <div class="icons">
        <i class="fas fa-search" id="search-btn"></i>
        <i class="fas fa-user" id="login-btn"></i>
    </div>

    <form action="" class="search-bar-container">
        <input type="search" id="search-bar" placeholder="search here...">
        <label for="search-bar" class="fas fa-search"></label>
    </form>

</header>

<!-- header section ends -->

<!-- login form container  -->

<div class="login-form-container">

    <i class="fas fa-times" id="form-close"></i>

    <form action="">
        <h3>Account</h3>
        <input type="email" class="box" placeholder="SĐT/ Email">
        <input type="password" class="box" placeholder="Mật Khẩu">
        <input type="submit" value="Đăng Nhập" class="btn">
        <input type="checkbox" id="remember">
        <label for="remember">Lưu mật khẩu</label>
        <p>Quên mật khẩu? <a href="#">Ấn vào đây</a></p>
        <p>Bạn chưa có tài khoản? <a href="#">Tạo mới ngay</a></p>
    </form>

</div>

<!-- home section starts  -->

<section class="home" id="home">

    <div class="content">
        <h3>Ăn chay không phải là sự hy sinh mà đó là niềm vui của cuộc sống </h3>
        <p>Tinh khiết - Bình an - Tinh tuệ</p>
        <a href="#sanpham" class="btn">Khám phá thếm</a>
    </div>

    <div class="controls">
        <span class="vid-btn active" data-src="images/Waterfall - 6998.mp4"></span>
        <span class="vid-btn" data-src="images/Mountain - 70464.mp4"></span>
        <span class="vid-btn" data-src="images/Ocean - 54081.mp4"></span>
        <span class="vid-btn" data-src="images/Palm Trees - 41897.mp4"></span>
    </div>

    <div class="video-container">
        <video src="images/Mountain - 70464.mp4" id="video-slider" loop autoplay muted></video>
    </div>

</section>

<!-- home section ends -->
<section class="home" id="gioithieu">

    <div class="content">
        <h3>Chào mừng quý khách đến với Thực Phầm Chay Vegan.</h3>
        <p style="color: aquamarine;">Với sứ mệnh phục vụ khách hàng, Thực Phẩm chay Vegan đã cố gắng hoàn thiện bản thân để cung cấp đến khách hàng những sản phẩm chất lượng, thơm ngon và dinh dưỡng.</p>
    </div>

    <div class="video-container">
        <video src="images/video.mp4" id="video-slider" loop autoplay muted></video>
    </div>

</section>




<!-- book section ends -->

<!-- packages section starts  -->

<section class="packages" id="sanpham">

    <h1 class="heading">
        <span>S</span>
        <span>Ả</span>
        <span>N</span>
        <span class="space"></span>
        <span>P</span>
        <span>H</span>
        <span>Ẩ</span>
        <span>M</span>
       
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/thucphamchaykho.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Thực phẩm chay khô </h3>
                
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">  <span></span> </div>
                <a href="thucphamchaykho.html" class="btn">xem hàng</a>
            </div>
        </div>

        <div class="box">
            <img src="images/raucuorganic.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i>Thực phẩm rau - Củ thiên nhiên </h3>
                
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> <span></span> </div>
                <a href="thucphamraucuthiennhien.html" class="btn">xem hàng</a>
            </div>
        </div>

        <div class="box">
            <img src="images/raucusay.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i>Thực phẩm Hoa quả Sấy khô </h3>
                <p>cho nội dung vào</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> <span></span> </div>
                <a href="thucphamhoaquasaykho.html" class="btn">xem hàng</a>
            </div>
        </div>

        <div class="box">
            <img src="images/donglanh.png" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i>Thực phẩm Chay Đông Lạnh </h3>
                <p>cho nội dung vào</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> <span></span> </div>
                <a href="thucphamchaydonglanh.html" class="btn">xem hàng</a>
            </div>
        </div>

        <div class="box">
            <img src="images/raucuorganic.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i>Thực phẩm ăn kiêng </h3>
                <p>cho nội dung vào</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> <span></span> </div>
                <a href="thucphamankien.html" class="btn">xem hàng</a>
            </div>
        </div>

        <div class="box">
            <img src="images/raucusay.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i>Thực phẩm Nhập khẩu </h3>
                <p>cho nội dung vào</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> <span></span> </div>
                <a href="thucphamnhapkhau.html" class="btn">xem hàng</a>
            </div>
        </div>

    </div>

</section>

<!-- packages section ends -->

<!-- services section starts  -->

<section class="services" id="tintuc">

    <h1 class="heading">
        <span>T</span>
        <span>I</span>
        <span>N</span>
        <span class="space"></span>
        <span>T</span>
        <span>Ứ</span>
        <span>C</span>
       
    </h1>  

    

    <div class="box-container">

        <div class="box">
            <i class="fas fa-utensils"></i>
            <h3>Món ngon chay mỗi ngày</h3>
            <p>nhập thông tin</p>
        </div>
        <div class="box">
            <i class="fas fa-globe-asia"></i>
            <h3>Cẩm nang ăn chay khoa học</h3>
            <p>nhập thông tin</p>
        </div>
        <div class="box">
            <i class="fas fa-bullhorn"></i>
            <h3>Công thức món chay</h3>
            <p>nhập thông tin</p>
        </div>
        <div class="box">
            <i class="fas fa-globe-asia"></i>
            <h3>Món chay đãi tiệc</h3>
            <p>nhập thông tin</p>
        </div>
  
    </div>

</section>

<!-- services section ends -->

<!-- gallery section starts  -->

<section class="gallery" id="lienhe">
    
    <h1 class="heading">
        <span>L</span>
        <span>I</span>
        <span>Ê</span>
        <span>N</span>
        <span class="space"></span>
        <span>H</span>
        <span>Ệ</span>
    </h1>
    <span style="font-size: 32px">Mọi thắc mắc xin liên hệ hỗ trợ qua <a href="zalo.me/0944312002">ZALO</a> </h1></span>
    <br>
    <span style="font-size: 32px">Email: Veganvn@gmail.com</span>
</section>

<!-- review section ends -->

<!-- contact section starts  -->

<section class="services" id="contact">
    
    <h1 class="heading">
        <span>G</span>
        <span>I</span>
        <span>Ớ</span>
        <span>I</span>
        <span class="space"></span>
        <span>T</span>
        <span>H</span>  
        <span>I</span>
        <span>Ệ</span>
        <span>U</span>
    </h1> 
    <div class="box-container">
        <div class="box">
            <i class="fas fa-globe-asia"></i>
    <H3 >Đến với thực phẩm chay Vegan, chúng tôi cung cấp cho quý khách những thực phẩm chay uy tính và chất lượng từ nhiều thương hiệu nổi tiếng như: thực phẩm chay Âu Lạc, thực phẩm chay Sài Gòn food, thực phẩm chay Đại Bình Dương,...</H3>
    <br>
    <h3> Liên hệ với chúng tôi qua số điện thoại Zalo: 0944312002</h3>
    </div>
    </div>
</section>

<!-- footer section  -->

<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>Về chúng tôi</h3>
            <p>Cam kết những gì tốt nhất cho khách hàng</p>
        </div>
        <div class="box">
            <h3>Chi nhánh</h3>
            <a href="#">Hà Nội</a>
            <a href="#">Thành phố Hồ Chí Minh</a>
            <a href="#">Đà Nẵng</a>
            <a href="#">Đắk Lắk</a>
            <a href="#">Cần Thơ</a>
            <a href="#">Phú Quốc</a>
        </div>
        <div class="box">
            <h3>Liên Hệ</h3>
            <a href="chat.zalo.me" ">ZALO</a>
            <p>Email: Veganvn@gmail.com </p>
        </div>
        <div class="box">
            <h3>Theo dõi chúng tôi</h3>
            <a href="#">facebook</a>
            <a href="#">instagram</a>
            <a href="#">twitter</a>
            <a href="#">linkedin</a>
        </div>
        <div class="box">
            <h3>Trang liên kết </h3>
            <a href="https://aulac-vegan.com/danh-muc-san-pham/hang-lanh/">Thực phẩm chay Âu Lạc</a>
            <a href="#https://soyna.vn/sua-thuc-vat-chay/">Sữa thực vật chay Soyna</a>
        </div>
        <div class="box">
            <h3>Mua Hàng Nhanh </h3>
            <a href="thucphamchaykho.html">Thực phẩm chay khô</a>
			<a href="thucphamraucuthiennhien.html" >Thực Phẩm Rau - Củ Thiên Nhiên</a>
			<a href="thucphamhoaquasaykho.html">Thực Phẩm Hoa Quả Sấy Khô</a>
			<a href="thucphamchaydonglanh.html">Thực Phẩm Chay Đông Lạnh</a>
            <a href="thucphamankien.html">Thực Phẩm Ăn Kiêng</a>
            <a href="thucphamnhapkhau.html">Thực Phẩm Nhập Khẩu</a>
        </div>

    </div>

    <h1 class="credit"> Thiết kế bởi <span> Vegan Organic </span> | Đã đăng kí bản quyền! </h1>

</section>
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

<!-- custom js file link  -->
<script src="script.js"></script>

</body>
</html>
