 news
 <template>
<div>
 <div class="all-title-box">
		<div class="container text-center">
			<h1>News<span class="m_1"></span></h1>
		</div>
	</div>

    <div id="overviews" class="section lb">
        <div class="container">
            <div class="section-title row text-center">
                <div class="col-md-8 offset-md-2">
                    
                
                </div>
            </div>
        
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="message-box">
                       

                        <h2><strong>Tree planting 'has mind-blowing potential' to tackle climate crisis</strong></h2>
                        <h4>Research shows a trillion trees could be planted to capture huge amount of carbon dioxide</h4>
                        <p>Planting billions of trees across the world is one of the biggest and cheapest ways of taking CO2 out of the atmosphere to tackle the climate crisis, according to scientists, who have made the first calculation of how many more trees could be planted without encroaching on crop land or urban areas.As trees grow, they absorb and store the carbon dioxide emissions that are driving global heating. New research estimates that a worldwide planting programme could remove two-thirds of all the emissions from human activities that remain in the atmosphere today, a figure the scientists describe as “mind-blowing”... </p>
                         <a href="#" class="hover-btn-new"><span>Read More</span></a>

                       
                    </div><!-- end messagebox -->
                </div><!-- end col -->
               
                
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="post-media wow fadeIn">
                        <img src="../assets/pic2.png" alt="" class="img-fluid img-rounded">
                    </div><!-- end media -->
                </div><!-- end col -->
            </div>
            <div class="section-title row text-center">
                <div class="col-md-8 offset-md-2">
                </div>
            </div>
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="post-media wow fadeIn">
                        <img src="../assets/pic1.png" alt="" class="img-fluid img-rounded">
                    </div><!-- end media -->
                </div><!-- end col -->
                
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="message-box">
                        <h2><strong>Ethiopia plants 350m trees in a day to help tackle climate crisis</strong></h2>
                        <h4>National ‘green legacy’ initiative aims to reduce environmental degradation</h4>
                        <p>About 350m trees have been planted in a single day in Ethiopia, according to a government minister.The planting is part of a national “green legacy” initiative to grow 4bn trees in the country this summer by encouraging every citizen to plant at least 40 seedlings. Public offices have reportedly been shut down in order for civil servants to take part.The project aims to tackle the effects of deforestation and climate change in the drought-prone country. According to the UN, Ethiopia’s forest coverage was just 4% in the 2000s, down from 35% a century earlier.</p>

                        <p> Ethiopia’s minister of innovation and technology, Dr Getahun Mekuria, tweeted estimates of the number of trees planted throughout the ... </p>
                        <a href="#" class="hover-btn-new"><span>Read More</span></a>

                        
                    </div><!-- end messagebox -->

          
                </div><!-- end col -->
<div class="section-title row text-center">
                <div class="col-md-8 offset-md-2">
                </div>
            </div>
                <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="message-box">
                       

                        <h2><strong>Global tree cover has increased 7% since 1982, finds biggest ever study</strong></h2>
                        <h4>Forests chopped down in tropics outweighed by more trees in regions which were previously too cold</h4>
                        <p>Amid growing urbanisation, deforestation and agricultural expansion, it’s long been thought the number of trees across the planet is being reduced. However, that belief is probably wrong, according to new figures.The biggest ever analysis of global land change has discovered there are more trees across the earth today than there were 36 years ago. “This overall net gain is the result of a net loss in the tropics being outweighed by a net gain in the extratropics,” the report states.... </p>
                         <a href="#" class="hover-btn-new"><span>Read More</span></a>

                       
                    </div><!-- end messagebox -->
                </div><!-- end col -->
                
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="post-media wow fadeIn">
                        <img src="../assets/pic02.png" alt="" class="img-fluid img-rounded">
                    </div><!-- end media -->
                </div><!-- end col -->
                <div class="section-title row text-center">
                <div class="col-md-8 offset-md-2">
                    
                
                </div>
            </div>
            </div>
                
            </div><!-- end row -->

        </div><!-- end container -->
    </div><!-- end section -->
    </div>
    
</template>

<style>
body{
    font-family: 'Quicksand', sans-serif;
}
.all-title-box{
	background: url(../assets/slider-02.jpg)no-repeat;
	-webkit-background-size: cover;
	-moz-background-size: cover;
	-o-background-size: cover;
	background-size: cover;
	background-position: center;
	min-height: 300px;
}

.all-title-box h1{
	color: #fff;
	font-weight: 600;
	text-transform: capitalize;
	padding-top: 11%;
	font-size: 48px;
	line-height: 0px;
}
.message-box a{
    position: relative;
    padding: 13px 40px;
    font-size: 18px;
    display: inline-block;
}
.message-box a,
.message-box a.hover-btn-new::after {
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}

.message-box a.hover-btn-new::before,
.message-box a.hover-btn-new::after {
  background: #405d27;
  content: '';
  position: absolute;
  z-index: 1;
}

.message-box a.hover-btn-new:hover span {
  color: #333333;
}
.message-box a.hover-btn-new::before {
  height: 100%;
  left: 0;
  top: 0;
  width: 100%;
}
.message-box a.hover-btn-new::after {
  background: #333333 !important;
  height: 100%;
  left: 0;
  top: 0;
  width: 100%;
}
.message-box a.hover-btn-new span{
    position: relative;
    z-index: 2;
    color: #fff;
}
.message-box a.hover-btn-new:hover:after {
  height: 0;
  left: 50%;
  top: 50%;
  width: 0;
}

.message-box h4 {
    text-transform: uppercase;
    padding: 0;
    margin: 0 0 5px;
    font-weight: 600;
    letter-spacing: 0.5px;
    font-size: 15px;
    color: #999;
}

.message-box h2 {
    font-size: 38px;
    font-weight: 400;
    padding: 0 0 10px;
    margin: 0;
    line-height: 62px;
    margin-top: 0;
    text-transform: none;
}

.message-box p {
    margin-bottom: 20px;
}

.message-box .lead {
    padding-top: 10px;
    font-size: 19px;
    font-style: italic;
    color: #999;
    padding-bottom: 0;
}

.post-media {
    position: relative;
}

.post-media img {
    width: 100%;
}

.playbutton {
    position: absolute;
    color: #ffffff !important;
    top: 40%;
    font-size: 60px;
    z-index: 12;
    left: 0;
    right: 0;
    text-align: center;
    margin: -20px auto;
}

.hoverbutton {
    background-color: rgba(255, 255, 255, 0.8);
    position: absolute;
    color: #1f1f1f !important;
    top: 48%;
    font-size: 21px;
    z-index: 12;
    left: 0;
    opacity: 0;
    right: 0;
    width: 50px;
    height: 50px;
    line-height: 50px;
    text-align: center;
    margin: -20px auto;
}

.service-widget:hover .hoverbutton {
    opacity: 1;
}

hr.hr1 {
    position: relative;
    margin: 60px 0;
    border: 1px dashed #f2f3f5;
}

hr.hr2 {
    position: relative;
    margin: 17px 0;
    border: 1px dashed #f2f3f5;
}

hr.hr3 {
    position: relative;
    margin: 25px 0 30px 0;
    border: 1px dashed #f2f3f5;
}

hr.invis {
    border-color: transparent;
}

hr.invis1 {
    margin: 10px 0;
    border-color: transparent;
}

.section.parallax hr.hr1 {
    border-color: rgba(255, 255, 255, 0.1);
}

.sep1 {
    display: block;
    position: absolute;
    content: '';
    width: 40px;
    height: 40px;
    bottom: -20px;
    left: 50%;
    margin-left: -14px;
    background-color: #1f1f1f;
    -ms-transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
    z-index: 1;
}

.sep2 {
    display: block;
    position: absolute;
    content: '';
    width: 40px;
    height: 40px;
    top: -20px;
    left: 50%;
    margin-left: -14px;
    background-color: #1f1f1f;
    -ms-transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
    z-index: 1;
}


</style>