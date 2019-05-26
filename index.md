<style>
    body {
        font-family: Arial;
    }
    /* Style the tab */
    
    .tab {
        overflow: hidden;
        border: 1px solid #ccc;
        background-color: #f1f1f1;
    }
    /* Style the buttons inside the tab */
    
    .tab button {
        background-color: inherit;
        float: left;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 14px 16px;
        transition: 0.3s;
        font-size: 17px;
    }
    /* Change background color of buttons on hover */
    
    .tab button:hover {
        background-color: #ddd;
    }
    /* Create an active/current tablink class */
    
    .tab button.active {
        background-color: #ccc;
    }
    /* Style the tab content */
    
    .tabcontent {
        display: none;
        padding: 6px 12px;
        border: 1px solid #ccc;
        border-top: none;
    }
    
    html {
        height: 100%;
    }
    
    body {
        background-image: url("https://travelblog.expedia.com.tw/wp-content/uploads/2017/05/%E5%8F%B0%E6%B1%9F%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92%E5%9B%9B%E8%8D%89%E7%B4%85%E6%A8%B9%E6%9E%97%E7%B6%A0%E8%89%B2%E9%9A%A7%E9%81%93.jpg");
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: center;
        background-size: cover;
    }
    
    .smaller-image {
        width: 300px;
    }
    
    .bigger-image {
        width: 400px;
    }
    
    .smallest-image {
        width: 50px;
    }
    
    .image-position {
        width: 10px:
    }
    
    body {
        background-color: #CCFF99;
    }
    
    td {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    
    th {
        font-family: "微軟正黑體";
        font-size: 18px;
        font-weight: 900;
    }
    
    body {
        background-color: #CCFF99
    }
    
    .blackborder {
        border: 2px black solid;
    }
    
    p {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    
    h1 {
        font-family: "微軟正黑體";
        font-weight: bold;
    }
    
    h2 {
        font-family: "微軟正黑體";
        font-weight: bold;
    }
    
    td {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    
    .button {
        background-color: #a0fdff;
        border: 2px solid black;
        color: #0645ad;
        padding: 8px 24px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button:hover {
        background-color: #A1D0FF;
    }
    
    #flip {
        background-color: #a0fdff;
        border: 2px solid black;
        color: black;
        padding: 8px 42px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button-bar {
        position: fixed;
        top: 5%;
        right: 5%;
    }
    
    * {
        box-sizing: border-box
    }
    
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }
    
    .mySlides {
        display: none
    }
    
    img {
        vertical-align: middle;
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    /* Next & previous buttons */
    
    .prev,
    .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,
    .dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    /* On smaller screens, decrease text size */
    
    @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }
</style>

<html>

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script>
        $(document).ready(function() {
            $('#top').click(function() {
                $('html, body').animate({
                    scrollTop: 0
                }, 1000);
            });
            $('#bottom').click(function() {
                $('html, body').animate({
                    scrollTop: $(document).height() - $(window).height()
                }, 1000);
            });
            $('#a').click(function() {
                $('html, body').animate({
                    scrollTop: $("#A").offset().top
                }, 1000);
            });
            $('#b').click(function() {
                $('html, body').animate({
                    scrollTop: $("#B").offset().top
                }, 1000);
            });
            $('#c').click(function() {
                $('html, body').animate({
                    scrollTop: $("#C").offset().top
                }, 1000);
            });
            $('#d').click(function() {
                $('html, body').animate({
                    scrollTop: $("#D").offset().top
                }, 1000);
            });
            $('#e').click(function() {
                $('html, body').animate({
                    scrollTop: $("#E").offset().top
                }, 1000);
            });
            $('#f').click(function() {
                $('html, body').animate({
                    scrollTop: $("#F").offset().top
                }, 1000);
            });
            $("#flip").click(function() {
                $(".button").slideToggle("slow");
            });
        });
    </script>

</head>

<body>
    <div id="google_translate_element"></div>

    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({
                pageLanguage: 'zh-tw',
                layout: google.translate.TranslateElement.InlineLayout.SIMPLE
            }, 'google_translate_element');
        }
    </script>

    <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
    <div style="font-family:微軟正黑體">
        <h1 style="color: black; font-weight: bold;font-size:40px"><center>台江國家公園</center></h1>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="A">基本資訊</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;">
            <img style="width:300px;height:300px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/86/Yanshuei_River_marine_outfall.JPG/375px-Yanshuei_River_marine_outfall.JPG" align="right"> 台江國家公園是臺灣第8座國家公園，也是臺灣唯一濕地型國家公園。位於河海匯流之地，薈萃了「自然生態」、「人文歷史」與「漁鹽產業」等三大資源特色。廣大的河口、潟湖、魚塭及紅樹林等豐美的濕地環境，孕育了豐饒的生態資源，秋冬時節，也是候鳥過境、度冬的良好棲所；內海滄桑之變與開臺歷史，見證了台江地區深厚的文化底蘊；而阡陌縱橫的魚塭與鹽田，交織出人類與自然環境的和諧互動。台江國家公園宛若是一間間的戶外大教室，也是一所可以親近自然學習的濕地學校。 為透過環境教育服務，引領社會大眾及學校師生深度感受豐富的濕地生命，喚醒濕地保育意識與行動，台管處創設「台江濕地學校」，作為環境教育服務品牌。以多元且寓教於樂的課程，體驗台江獨特的資源特色，落實環境教育與永續發展之理念。 台江國家公園於2012年11月取得環保署環境教育設施場所認證，2013年「台江濕地學校」學習中心開放受理預約。2015年榮獲第三屆「國家環境教育獎」機關組優等獎，同年通過環保署評鑑並獲表揚為「優異環境教育設施場所場」，2017年取得國內第一個環境教育服務類「濕地標章」之肯定。
        </div>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="B">國家公園標誌意涵</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;font-size:18px;font-family:微軟正黑體">

            <p><img style="width:100px;height:100px" src="http://np.cpami.gov.tw/filesys/image/01_chinese/04_news/8logo.jpg" align="left"> 以河口、黑面琵鷺加上台灣船、鲲鯓（沙洲）為設計元素，表現陸域資源特色及台江先民勇渡黑 水溝（台灣海峽）墾拓顯著歷史，象徵台江國家公園的使命與目標。色彩上以「綠色」表現自然 生態生生不息，「藍色」寓意海洋生態資源豐沛之意象，整體造形既傳達台灣歷史足跡。
            </p>

        </div>

        <script>
            function openCity(evt, cityName) {
                var i, tabcontent, tablinks;
                tabcontent = document.getElementsByClassName("tabcontent");
                for (i = 0; i < tabcontent.length; i++) {
                    tabcontent[i].style.display = "none";
                }
                tablinks = document.getElementsByClassName("tablinks");
                for (i = 0; i < tablinks.length; i++) {
                    tablinks[i].className = tablinks[i].className.replace(" active", "");
                }
                document.getElementById(cityName).style.display = "block";
                evt.currentTarget.className += " active";
            }

            // Get the element with id="defaultOpen" and click on it
            document.getElementById("defaultOpen").click();
        </script>

        <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="C">公園特色介紹</h1>
        <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
            <div class="tab">
                <button class="tablinks" onclick="openCity(event, '濕地')" id="defaultOpen">濕地</button>
                <button class="tablinks" onclick="openCity(event, '河口沙洲潟湖生態')">河口沙洲潟湖生態</button>
                <button class="tablinks" onclick="openCity(event, '紅樹林濕地生態')">紅樹林濕地生態 </button>
                <button class="tablinks" onclick="openCity(event, '沙洲')">沙洲</button>
                <button class="tablinks" onclick="openCity(event, '古蹟與史蹟')">古蹟與史蹟</button>
            </div>
            <div id="濕地" class="tabcontent">
                <p>
                    <gg style="font-weight:900">2007年中華民國內政部營建署評選75處國家級、國際級濕地，其中4處位於台江國家公園內。</gg>
                    <br>
                    <br>
                    <gg style="font-weight:900">曾文溪口濕地：</gg>國際級，瀕臨絕種的黑面琵鷺每年有三分之二在此渡冬。
                    <br>
                    <gg style="font-weight:900">四草濕地：</gg>國際級，範圍內有多處魚塭、鹽田、渠道及紅樹林，為高蹺鴴等水鳥繁殖與保護區。
                    <br>
                    <gg style="font-weight:900">七股鹽田濕地：</gg>國家級，冬季吸引雁鴨，亦為黑面琵鷺棲息地。
                    <br>
                    <gg style="font-weight:900">鹽水溪口濕地：</gg>國家級，有藻類、紅樹林等。
                    <br>
                </p>
            </div>
            <div id="河口沙洲潟湖生態" class="tabcontent">
                <p>
                    <gg style="font-weight:900">海灘：</gg>因為波浪或沿岸流等搬運沙礫堆積在海濱，就形成了海灘。可分為沙灘、礫灘。
                    <br>
                    <gg style="font-weight:900">沙洲：</gg>海中的沙礫，因波浪和海流的作用，在濱海地區形成的堤狀沙礫堆積地形，通稱沙洲或障沙島。沙洲完全不與海岸相連者，即為濱外沙洲或離岸沙洲。沙洲為地理學上的名詞，當地人則稱之為「汕」，如：新浮崙汕、頂頭額汕。
                    <br>
                    <gg style="font-weight:900">沙嘴：</gg>沙洲的一端與陸地連接，另一端伸向海洋，稱為沙嘴，又稱為「汕尾」。
                    <br>
                    <gg style="font-weight:900">潟湖：</gg>濱外沙洲與陸地之間所圍的水域。
                    <br>
                    <gg style="font-weight:900">海埔地：</gg>即海埔新生地，係指在海岸地區經自然沈積或施工築堤涸出之土地，廣義而言，泛指臨海地區淺灘處表露的新生土地。
                    <br>
                </p>
            </div>
            <div id="紅樹林濕地生態" class="tabcontent">
                <p>
                    <gg style="font-weight:900">曾文溪北岸的紅樹林，以七股溪與三股溪會合口有近10公頃海茄苳純林的「海寮紅樹林保護區」最具代表性，不但林相優美，也是上千小白鷺、夜鷺及黃頭鷺的群聚營巢所在。 曾文溪北岸以南有三處可欣賞紅樹林濕地</gg>
                    <br>
                    <br>
                    <gg style="font-weight:900">1.</gg>在竹筏港潮溝及蔡姑娘廟附近水道，組成樹種為海茄苳及欖李。
                    <br>
                    <gg style="font-weight:900">2.</gg>在四草地區大眾廟後面及東側水道的紅海欖（五梨跤）具茂密支持根及樹冠層，廟旁水道的海茄苳根據年輪調查應有超過數十年的歷史，形成獨特風格的「綠色隧道」。廟的前潮池及周邊水道有生長良好的欖李，六月開滿白花有如六月雪，另有少數人工復育的水筆仔，在此處小小範圍內可同時看到四種紅樹林植物。
                    <br>
                    <gg style="font-weight:900">3.</gg>在四草湖區域（鹽水溪、嘉南大圳、運鹽古運河，與竹筏港溪交會處）有原生較大面積的海茄苳、欖李與紅海欖（五梨跤）的混合林。
                </p>
            </div>
            <div id="沙洲" class="tabcontent">
                <p>
                    <h3>曾文溪口離岸沙洲  臺南城西濱海沙洲  新浮崙汕</h3>
                    <h3>青山港汕         網仔寮  頂頭額汕</h3>
                </p>
            </div>
            <div id="古蹟與史蹟" class="tabcontent">
                <p>
                    <h3>四草砲台(國定二級古蹟)      鹿耳門港</h3>
                    <h3>安順鹽場運鹽碼頭(市定古蹟)  竹筏港</h3>
                </p>
            </div>
            
            <div class="slideshow-container">

                <div class="mySlides fade">
                    <div class="numbertext">1 / 5</div>
                    <img style="width:100%;height:400px" src="https://www.tjnp.gov.tw/ckfinder/userfiles/images/Newspaper/2013/20131231-11.jpg">
                    <div class="text"> 四草綠色隧道</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">2 / 5</div>
                    <img style="width:100%;height:400px" src="http://np.cpami.gov.tw/filesys/image/01_chinese/12_equarterly/200912/200912_p052_18.jpg">
                    <div class="text"> 招潮蟹</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">3 / 5</div>
                    <img style="width:100%;height:400px" src="https://npgis.cpami.gov.tw/public/data/jpg/B0058p001.jpg">
                    <div class="text"> 夜鷺</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">4 / 5</div>
                    <img style="width:100%;height:400px" src="https://www.tjnp.gov.tw/uploads/%E4%B8%AD%E7%99%BD%E9%B7%BA.jpg">
                    <div class="text"> 中白鷺</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">5 / 5</div>
                    <img style="width:100%;height:400px" src="http://i.epochtimes.com/assets/uploads/2010/03/1003210754572008.jpg">
                    <div class="text"> 黑面琵鷺</div>
                </div>

                <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
                <a class="next" onclick="plusSlides(1)">&#10095;</a>

            </div>
            <br>

            <div style="text-align:center">
                <span class="dot" onclick="currentSlide(1)"></span>
                <span class="dot" onclick="currentSlide(2)"></span>
                <span class="dot" onclick="currentSlide(3)"></span>
                <span class="dot" onclick="currentSlide(4)"></span>
                <span class="dot" onclick="currentSlide(5)"></span>
            </div>
            <script>
                var slideIndex = 1;
                showSlides(slideIndex);

                function plusSlides(n) {
                    showSlides(slideIndex += n);
                }

                function currentSlide(n) {
                    showSlides(slideIndex = n);
                }

                function showSlides(n) {
                    var i;
                    var slides = document.getElementsByClassName("mySlides");
                    var dots = document.getElementsByClassName("dot");
                    if (n > slides.length) {
                        slideIndex = 1
                    }
                    if (n < 1) {
                        slideIndex = slides.length
                    }
                    for (i = 0; i < slides.length; i++) {
                        slides[i].style.display = "none";
                    }
                    for (i = 0; i < dots.length; i++) {
                        dots[i].className = dots[i].className.replace(" active", "");
                    }
                    slides[slideIndex - 1].style.display = "block";
                    dots[slideIndex - 1].className += " active";
                }
            </script>
            <p></p>
        </div>
    </div>

    <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="D">交通資訊</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <h3>♦ 搭乘高鐵：請至高鐵臺南站下車</h3>

        <h3>1. 轉乘高鐵接駁車高鐵臺南站－臺南市政府線：</h3>

        <h3>&nbsp;&nbsp;&nbsp;&nbsp;(1)至興南客運台南站下車，轉乘臺灣好行99台江線至四草大橋西站下車。</h3>

        <h3>&nbsp;&nbsp;&nbsp;&nbsp;(2)至臺南市政府站下車，轉搭計程車至台江國家公園管理處。</h3>

        <h3>2. 轉乘臺鐵沙崙線至臺南火車站，轉乘臺灣好行99台江線至四草大橋西站下車。</h3>

        <h3>♦  搭乘臺鐵：請至臺南站下車</h3>

        <h3>1. 轉乘臺灣好行99台江線至四草大橋西站下車。</h3>

        <h3>2. 轉乘計程車至台江國家公園管理處。</h3>
    </div>

    <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="E">住宿資訊</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">

                <thead>
                    <tr>
                        <th width="31%">酒店/旅館 </th>
                        <th width="48%">地址</th>
                        <th width="18%">電話</th>
                    </tr>
                </thead>

                <tbody>

                    <tr>
                        <td>台南大員皇冠假日酒店</td>
                        <td>台灣台南安平區州平路289號</td>
                        <td>06-3911899</td>
                    </tr>

                    <tr>
                        <td>臺邦商旅</td>
                        <td>台灣台南安平區永華二街199號</td>
                        <td>06-2931888</td>
                    </tr>

                    <tr>
                        <td>沐府海旅</td>
                        <td>台灣台南安平區安億路288號</td>
                        <td> 06-2939998</td>
                    </tr>

                    <tr>
                        <td>歐薇汽車旅館(台南館)</td>
                        <td>台灣台南育平路181號</td>
                        <td>06-2993000</td>
                    </tr>

                    <tr>
                        <td>康橋商旅(臺南民生館)</td>
                        <td>台灣台南中西區民生路二段299號</td>
                        <td>06-2245566</td>
                    </tr>

                </tbody>
            </table>
        </p>
    </div>

    <h1 style="color: black; font-weight: bold;font-size:0.8cm" id="F">美食資訊</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">

                <thead>
                    <tr>
                        <th width="31%">店名</th>
                        <th width="48%">地址</th>
                        <th width="18%">電話</th>
                    </tr>
                </thead>

                <tbody>

                    <tr>
                        <td>同記安平豆花</td>
                        <td>安平區安北路433號</td>
                        <td>0963915385</td>
                    </tr>

                    <tr>
                        <td>椰庭</td>
                        <td>四草大道261號四草里</td>
                        <td>0962840988</td>
                    </tr>

                    <tr>
                        <td>元素</td>
                        <td>州平路289號1樓</td>
                        <td>0963911899</td>
                    </tr>

                    <tr>
                        <td>文章牛肉湯</td>
                        <td>安平區安平路590號</td>
                        <td>0962284626</td>
                    </tr>

                    <tr>
                        <td>義豐冬瓜茶</td>
                        <td>安平區安平路768號</td>
                        <td>0962219197</td>
                    </tr>

                </tbody>
            </table>
        </p>
    </div>

    <h1 style="color: black; font-weight: bold;font-size:0.8cm">參考資料</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <a href="https://www.tripadvisor.com.tw/RestaurantsNear-g13792454-d5513252-Taijian_National_Park-Annan_Tainan.html"><h3>貓途鷹(美食)</h3></a>
        <a href="https://www.tripadvisor.com.tw/HotelsNear-g13792454-d5513252-Taijian_National_Park-Annan_Tainan.html"><h3>貓途鷹(住宿)</h3></a>
        <a href="https://zh.wikipedia.org/wiki/%E5%8F%B0%E6%B1%9F%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92"><h3>維基百科</h3></a>
        <a href="http://np.cpami.gov.tw/youth/index.php?option=com_content&view=article&id=4206&Itemid=6"><h3>台灣國家公園(公園標誌意涵)</h3></a>
        <a href="https://www.tjnp.gov.tw//chtNature/Environment/ShiDiXueXiao2.htm"><h3>台江國家公園(台江濕地學校)</h3></a>
    </div>
    </div>

</body>

<div class="button-bar">
    <a id="flip">選單</a>
    <a class="button" id="a" href="#">基本資訊</a>
    <a class="button" id="b" href="#">標示意涵</a>
    <a class="button" id="c" href="#">特色介紹</a>
    <a class="button" id="d" href="#">交通資訊</a>
    <a class="button" id="e" href="#">住宿資訊</a>
    <a class="button" id="f" href="#">美食資訊</a>
    <a class="button" id="top" href="#">網頁頂端</a>
    <a class="button" id="bottom" href="#">網頁底部</a>
    <a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
</div>

</html>
