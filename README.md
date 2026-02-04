<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="index.css">
    <link rel="icon" type="image/png" href="logotruong.jpg">

    <title>THPTGIOLINH12A5-K48</title>
</head>
<body> 
<div class="welcome-popup">
    Xin chào đây là trang web của 12A5 💙
    - TheThien - 🫡 
</div>

<div class="petal-container">
    <span class="petal"></span>
    <span class="petal"></span>
    <span class="petal"></span>
    <span class="petal"></span>
    <span class="petal"></span>
    <span class="petal"></span>
    <span class="petal"></span>
    <span class="petal"></span>
</div>


<div id="lightbox" onclick="closeImage()">
    <img id="lightboxImg">
</div>

<!-- ===== MUSIC PLAYER ===== -->
<div id="musicPlayer">
    <div id="musicHeader">🎵 Nhạc</div>

    <audio controls>
    <source src="3.mp3"type="audio/mpeg">
    </audio>

</div>
<!-- ===== HEADER ===== -->

<header>
         <img src="logo.jpg" class="logo">  
         <h1> TRƯỜNG TRUNG HỌC PHỔ THÔNG GIO LINH </h1>
         <h3 class="info">📌 KỶ NIỆM CỦA CHÚNG TỚ QUA MỖI NGÀY ĐẾN TRƯỜNG </h3>
         <h3 class="info">  GVCN : 👩‍🏫 NGUYỄN THỊ THANH 💖 </h3>

</header>

<!--====Thanh tùy chọn====-->
<nav>
    <a class="active" onclick="showGroup('home',this)">Trang chủ</a>
    <a onclick="showGroup('about',this)">Giới thiệu</a>
    <a onclick="showGroup('members',this)">Thành viên</a>
    <a onclick="showGroup('services',this)">Kỷ Niệm</a>
    <a onclick="showGroup('contact',this)">Liên hệ 📞 </a>

</nav>

<!-- ===== Trang chủ ===== -->
<div class="content home show">
  <div class="two-col">
    <div class="image-box"><img src="anhlop.jpg"></div>
      <div>
           <h2>Trang chủ 🏫 </h2>
           <p class="welcome">Welcome to website 12A5 </p>
           <p class="welcome" style="color:red; font-size:40px; font-weight:bold; text-align:center;">Tự Tin - Năng Động 🫡🍀 </p>
           <button id="darkToggle" onclick="toggleDark()">🌚</button> 
      </div>
    </div>
</div>

<!-- ===== Giới thiệu ===== -->
<div class="content about">
    <div class="two-col">

        <!-- CỘT TRÁI -->
        <div class="school"> 
            <h2>TRƯỜNG _ TẬP THỂ 12A5_K48 🫂 </h2>
            <p>Tập thể 12A5 – Trường THPT Gio Linh là một phần thanh xuân mà mỗi thành viên khi nghĩ lại đều thấy bồi hồi và tự hào. Ba năm cấp ba không quá dài, nhưng đủ để những con người xa lạ trở thành anh em, bạn bè, một gia đình đúng nghĩa. Ở 12A5 có tiếng cười giòn tan của những giờ ra chơi, có sự nghiêm túc trong những buổi học căng thẳng, có cả những lần mệt mỏi, chán nản nhưng chưa bao giờ bỏ lại nhau phía sau. Tập thể ấy đã cùng nhau trưởng thành qua từng hoạt động, từng buổi sinh hoạt, từng kỷ niệm với thầy cô – đặc biệt là những khoảnh khắc bên cô giáo chủ nhiệm luôn tận tâm và yêu thương học trò. 12A5 không chỉ ghi dấu bằng thành tích hay hình ảnh, mà bằng tình cảm chân thành, sự gắn bó và những ký ức sẽ theo mỗi người suốt cuộc đời. Dù sau này mỗi đứa một con đường, thì 12A5 – THPT Gio Linh vẫn mãi là nơi bắt đầu của tuổi trẻ, của ước mơ và của những năm tháng không thể nào quên. 🍀✨</p>

            <p> Dưới mái trường THPT Gio Linh, chúng ta đã đi qua những năm tháng đẹp nhất của tuổi trẻ. Có mệt mỏi, có áp lực, có cả những lần tưởng chừng muốn bỏ cuộc, nhưng chưa bao giờ chúng ta bước đi một mình. Bạn bè bên cạnh, thầy cô phía sau, tất cả đã tiếp thêm cho ta niềm tin và sức mạnh. Mỗi bài học, mỗi giọt mồ hôi đều là bước đệm cho tương lai. Dù mai này mỗi người một con đường, hãy luôn tự hào vì đã từng cố gắng hết mình dưới mái trường Gio Linh. Thanh xuân ấy sẽ mãi là động lực để ta bước tiếp và vươn xa. 💙🍀 </p>
            <h2>Website:</h2>
            <a href="https://thptgiolinh.quangtri.edu.vn/" 
                 style="color:red; font-size:20px; font-weight:600; text-decoration:none;">
                        TRƯỜNG THPT GIO LINH  👈 🏫 
            </a>
            <br>    
            </br> 
            <div id="countdown-box">
                <h3>⏳ Đếm ngược ngày thi THPT Quốc Gia</h3>
                <div id="countdown"></div>
            </div>
        </div>

        <!-- CỘT PHẢI -->
        <div>

            <div class="shorts-box">
                <h2>🎬 Khoảnh khắc lớp A5 ____ ( Ấn nút để xem 📩 )</h2>

                <div class="shorts-list">
                    <div class="short-item"><video src="1 (1).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (2).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (3).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (4).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (5).mp4" muted></video>
                    </div>
                    <div class="short-item"><video src="1 (6).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (7).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (8).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (9).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (10).mp4" muted></video>
                    </div>
                    <div class="short-item"><video src="1 (11).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (12).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (13).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (14).mp4" muted></video></div>
                    <div class="short-item"><video src="1 (15).mp4" muted></video>
                    </div>
                    <div class="short-item"><video src="3 (1).mp4" muted></video></div>
                    <div class="short-item"><video src="3 (3).mp4" muted></video></div>
                    <div class="short-item"><video src="3 (4).mp4" muted></video></div>
                    <div class="short-item"><video src="3 (5).mp4" muted></video></div>
                    <div class="short-item"><video src="3 (6).mp4" muted></video>
                    </div>
                </div>

                <div class="play-center" onclick="openShort(0)">▶</div>
                <div id="shortModal" onclick="closeShort()">
                <div class="short-box" onclick="event.stopPropagation()">
                    <button class="nav-btn left" onclick="prevShort()">❮</button>

                    <video id="shortPlayer" controls></video>

                    <button class="nav-btn right" onclick="nextShort()">❯</button>
                    <div class="close-btn" onclick="closeShort()">✖</div>
                </div>
            </div>
            </div>
        </div>

    </div>   
</div>

<!-- ===== PHẦN THÀNH VIÊN ===== -->

<div class="content members">
   <div class="three-col">

        <div class="member" data-img=" .jpg" onclick="toggleMember(this)">
               <h3>PHAN LỆ QUYÊN </h3>
            <div class="info">
               <p>LỚP TRƯỞNG</p>
               <p>Ngày sinh: </p>
               <p>Sở thích:  </p>
               <p>Ước mơ:</p>
               <p> </p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
                <h3>NGUYỄN THỊ THÙY LINH</h3> 
            <div class="info"> 
                <p>BÍ THƯ </p> <p>Ngày sinh: 08/04/2008</p> 
                <p>Sở thích: sở thích đơn giản thôi, việc gì làm mà thấy thoải mái thì là sở thích :></p> 
                <p>Ước mơ:</p>
                <p>Đậu nv1 và sau này sẽ mở 1 tiệm bánh .</p>
            </div> 
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3>ĐOÀN THẾ THIỆN 👑 </h3>
            <div class="info">
               <p>PHÓ BÍ THƯ 🎖️ </p>
               <p>Ngày sinh: 03/02/2008</p>
               <p>Sở thích: Chơi cầu lông , chơi game , đánh được đàn piano. 🏸</p>
               <p>Ước mơ:</p>
               <p>Đậu được trường sĩ quan thông tin , có quân hàm TÁ  trước tuổi 50 ổn định công việc và tiền bạc 💰 </p>
            </div>
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3>LÊ NGỌC LINH </h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh:29/12/2008</p> 
               <p>Sở thích: múa, nhảy, hát, đàn violin, nghe nhạc </p>
               <p>Ước mơ:</p>
               <p>Đậu NV1 trường Đại học Kinh Tế Đà Nẵng </p>
            </div>
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3>NGUYỄN PHƯƠNG ANH</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: 30/04/2008</p>
               <p>Sở thích: Xem phim, nghe nhạc, đánh bóng chuyền, chơi game</p>
               <p>Ước mơ:</p>
               <p>Đậu B2 qua Đức 🇩🇪 và có nhìu tiền 🤑. </p>
            </div>
        </div>  
        <div class="member" onclick="toggleMember(this)">
               <h3>HOÀNG BẢO NAM</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: Chơi thể thao, nghe nhạc, ngủ</p>
               <p>Ước mơ:</p>
               <p>Thành công, ...</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>HOÀNG LÊ THIỆN NHÂN</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: khám phá khắp Việt Nam</p>
               <p>Ước mơ:</p>
               <p>  </p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>DƯƠNG NỮ NHẬT NY</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p> ...</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>TRẦN THỊ BÌNH </h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p>...</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>NGUYỄN HÀ ĐỨC PHÚC</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: 14/7/2008 </p>
               <p>Sở thích: đi du lịch, chụp ảnh và thể thao </p>
               <p>Ước mơ:</p>
               <p>trở thành sĩ quan trong quân đội nhân dân Việt Nam Cấp Bậc Đại Tá..</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>TẠ QUANG HIỆP </h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: 26/05/2008</p>
               <p>Sở thích: Đá Bóng, chơi game, thích tự do </p>
               <p>Ước mơ:</p>
               <p>.đứng trên tất cả😄,...</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>HOÀNG THỊ THANH HƯƠNG</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh : 18/01/2008 </p>
               <p>Sở thích: Bóng chuyền, chơi thể thao, thích trò chuyện lượn lờ với bạn bè, thích nơi yên tĩnh</p>
               <p>Ước mơ:</p>
               <p>Đỗ nv1, xây nhà lầu xe hơi, cưới chồng đại gia .</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>ĐOÀN VĂN QUYẾT</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh:12/10/2008  </p>
               <p>Sở thích: Thể thao , nghe nhạc ,... </p>
               <p>Ước mơ: Bộ Đội Biên Phòng... </p>
               <p></p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>NGUYỄN THỊ THANH TRÚC</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh:08/02/2008 </p>
               <p>Sở thích: động vật , nghe nhạc, ngủ…</p>
               <p>Ước mơ:</p>
               <p>lo đc cho ba mẹ  , thành công ...</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p>...</p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p>...</p>
            </div>
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p>...</p>
            </div>
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p>...</p>
            </div>
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: </p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p>...</p>
            </div>
        </div>
        <div class="member" onclick="toggleMember(this)">
               <h3></h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: /2008</p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p></p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: /2008</p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p></p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: /2008</p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p></p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: /2008</p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p></p>
            </div>
        </div> 
        <div class="member" onclick="toggleMember(this)">
               <h3>...</h3>
            <div class="info">
               <p>ĐOÀN VIÊN</p>
               <p>Ngày sinh: /2008</p>
               <p>Sở thích: </p>
               <p>Ước mơ:</p>
               <p></p>
            </div>
        </div> 
    </div>
</div>             
       
 
<!-- ===== CÁC HOẠT ĐỘNG ===== -->
<div class="content services">

   <div class="three-col">
    <h2>Lớp 10</h2>

    <div class="album">
        <div class="photo" onclick="openImage(this)">
            <img src="2.jpg">
            <h4>Ngày đầu vào lớp</h4>
            <p>Bỡ ngỡ, ngại ngùng nhưng đầy háo hức.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="7.jpg">
            <h4>Sinh hoạt tập thể</h4>
            <p>Những buổi sinh hoạt đầu tiên cùng nhau.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="1.jpg">
            <h4>Hoạt động ngoại khóa</h4>
            <p>Kỷ niệm vui không thể quên.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="2 (1).jpg">
            <h4>12A5 – nơi thanh xuân bắt đầu</h4>
            <p>là nơi thanh xuân của chúng ta bắt đầu và cũng là nơi ký ức đẹp nhất được cất giữ.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="2 (2).jpg">
            <h4>Ba năm học cùng nhau là ba năm không thể nào quên.</h4>
            <p>Mỗi tiếng cười trong lớp 12A5 đều là một mảnh ghép của tuổi trẻ.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="2 (3).jpg">
            <h4>Dù sau này mỗi người một hướng, ký ức 12A5 vẫn ở trong tim.</h4>
            <p>12A5 không chỉ là một lớp học, mà là một gia đình.</p>
        </div>
    </div> 
    </div>
</div>


<div class="content services">
   <div class="three-col">
    <h2>Lớp 11 </h2>

    <div class="album">
        <div class="photo" onclick="openImage(this)">
            <img src="2 (4).jpg">
            <h4>Chúng ta đã từng mệt mỏi, nhưng chưa bao giờ bỏ cuộ</h4>
            <p>Mỗi bài kiểm tra là một bước tiến của bản thân.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="2 (5).jpg">
            <h4>Sinh hoạt tập thể</h4>
            <p>Những buổi sinh hoạt đầu tiên cùng nhau.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="2 (6).jpg">
            <h4>Áp lực thi cử không thể đánh bại tinh thần 12A5.</h4>
            <p>Gian nan hôm nay là nền móng cho thành công ngày mai.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="2 (7).jpg">
            <h4>Hãy mang theo tinh thần 12A5 đi thật xa trên con đường phía trước.</h4>
            <p>Dù tương lai có thế nào, đừng quên bạn từng cố gắng đến đâu</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="2 (8).jpg">
            <h4>Thanh xuân chỉ đến một lần, hãy sống cho xứng đáng.</h4>
            <p>Hôm nay là học sinh, ngày mai là ước mơ trở thành hiện thực.</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="6.jpg">
            <h4>Ba năm học chung một mái trường</h4>
            <p>Chúng ta có thể không hoàn hảo, nhưng nhất định không tầm thường.</p>
        </div>
    </div> 
    </div>
</div>

<div class="content services">
   <div class="three-col">
    <h2>Lớp 12 </h2>

    <div class="album">
        <div class="photo" onclick="openImage(this)">
            <img src="32.jpg">
            <h4>12A5 – nơi chúng ta đã lớn lên cùng nhau</h4>
            <p>Trong tiếng cười, nước mắt và những ngày không quên</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="8.jpg">
            <h4>Có những buổi học rất bình thường</h4>
            <p>Nhưng sau này nhớ lại lại thấy nghẹn lòng</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="3 (7).jpg">
            <h4>Ba năm ngồi chung một lớp</h4>
            <p>Đủ để thành ký ức theo suốt một đời</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (8).jpg">
            <h4>Chúng ta từng mệt mỏi, từng áp lực</h4>
            <p>Nhưng chưa bao giờ cô đơn trong 12A5</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="3 (9).jpg">
            <h4>Ngày chia tay không ai nói thành lời</h4>
            <p>Chỉ lặng im mà thương nhau nhiều hơn</p>
        </div>

        <div class="photo" onclick="openImage(this)">
            <img src="3 (10).jpg">
            <h4>Mai này mỗi người một con đường</h4>
            <p>Nhưng ký ức 12A5 sẽ mãi ở lại</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (11).jpg">
            <h4>12A5 không chỉ là một lớp học, mà là một thanh xuân rực rỡ được ghi lại trong từng tấm ảnh</h4>
            <p>Nơi có mồ hôi sân thể thao, tiếng cười hành lang và những cái ôm chiến thắng.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (12).jpg">
            <h4>Mai này mỗi người một con đường</h4>
            <p>Nhưng ký ức 12A5 sẽ mãi ở lại</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (13).jpg">
            <h4>Có những ngày chúng ta khoác áo thể thao, không vì huy chương mà vì tinh thần đồng đội</h4>
            <p>12A5 đã cùng nhau cố gắng bằng tất cả sự trẻ trung và nhiệt huyết.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (14).jpg">
            <h4>Những tấm huy chương trên ngực không sáng bằng nụ cười của cả lớp.</h4>
            <p>Vì phía sau đó là tình bạn và sự cố gắng không ai bỏ lại ai.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (15).jpg">
            <h4>12A5 – nơi mỗi khoảnh khắc đều đáng nhớ, từ sân đấu đến lớp học quen thuộc.</h4>
            <p>Tất cả gom lại thành một thanh xuân không thể quay lại lần nữa.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (16).jpg">
            <h4>Chúng ta đã lớn lên cùng nhau qua từng buổi tập, từng lần thi đấu và từng ngày đến lớp.</h4>
            <p>Mỗi tấm ảnh là một mảnh ghép của tuổi 17 rực rỡ.</p>
        </div>
        <div class="photo" onclick="openImage(this)">
            <img src="3 (17).jpg">
            <h4>Có thể sau này mỗi người một con đường, nhưng ký ức về 12A5 sẽ luôn ở đó.</h4>
            <p>Như một nơi để nhớ, để thương và để tự hào.</p>
        </div>
    </div> 
    </div>
</div>


<!-- ===== Liên hệ ===== -->
<div class="content contact ">
    <div class="two-col contact-box">
        
        <!-- Ảnh lớp -->
        <div class="image-lop">
            <img src="2.png" alt="Ảnh tập thể lớp">
        </div>

        <!-- Thông tin liên hệ -->
        <div class="contact-info">
            <h2>📞 Liên hệ</h2>

            <p>📧 <strong>Email:</strong> 
                <a href="mailto:thethien322008@gmail.com">
                    thethien322008@gmail.com
                </a>
            </p>

            <p>☎️ <strong>SĐT:</strong> 
                <a href="tel:0948273730">0948 273 730</a>
            </p>

            <p>📍 <strong>Địa chỉ:</strong> Lớp 12A5 – THPT Gio Linh </p>

            <h3>Kết nối với chúng tôi </h3>
            <ul class="social-links">
                <li>
                    <a href="https://www.facebook.com/the.thien.344741" target="_blank">
                        🌐 Facebook
                    </a>
                </li>
                <li>
                    <a href="https://www.tiktok.com/@a5_withluv?_r=1&_t=ZS-93TK4OHSj4u" target="_blank">
                        🎵 TikTok
                    </a>
                </li>
                <li>
                    <a href="https://www.instagram.com/12a5_glhighschool/" target="_blank">
                        📸 Instagram
                    </a>
                </li>
            </ul>
        </div>

    </div>
</div>

<div id="comment-list" class="comment-box">
    <h4>12A5 là trang thanh xuân rực rỡ, nơi tình bạn ở lại mãi với thời gian. 💚</h4>
</div>

<footer class="footer">
    <p>🌸 Kỷ niệm của chúng tôi – Tập thể lớp <b>12A5</b> 🌸</p>
</footer>

 <script src="index.js"></script>
</body>
</html>
