 news
 <template>
<div>
 <div class="all-title-box">
		<div class="container text-center">
			<h1>Events<span class="m_1"></span></h1>
		</div>
	</div>

    <div id="overviews" class="section lb">
        <div class="container">
            <div class="section-title row text-center">
                <div class="col-md-8 offset-md-2">
                   <h3>UPCOMING PLANTING EVENTS</h3>
                    <p class="lead">We have lots more work to do, but for now we will have to wait until the weather is ideal for tree planting!</p> 
                
                </div>
            </div>
        
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="message-box">
                       

                        <h2><strong>PLANTING FOR BRIGHTER FUTURE</strong></h2>
                        <p>Thank you to everyone who participated in planting events with us this past season! We have lots more work to do, but for now we will have to wait until the weather is ideal for tree planting. </p>
                         <a href="#" class="hover-btn-new"><span>Read More</span></a>

                       
                    </div><!-- end messagebox -->
                </div><!-- end col -->
               
                
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="post-media wow fadeIn">
                        <img src="../assets/event1.png" alt="" class="img-fluid img-rounded">
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
                        <img src="../assets/events2.png" alt="" class="img-fluid img-rounded">
                    </div><!-- end media -->
                </div><!-- end col -->
                
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="message-box">
                        <h2><strong>LETS PLANT TREES.</strong></h2>
                        <p>Thank you to everyone who came out to a planting in 2020! We had another stellar year with over 4,200 new trees and shrubs planted all across the Forest City. We look forward to getting started again this spring.</p>
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
                       

                        <h2><strong>PLANTING TREES GROWS COMMUNITIES!</strong></h2>
                        <p>Get to know your community, meet new people, enjoy the outdoors, and help make the World healthier and greener by volunteering to plant trees. No experience, training or volunteer registration is required to attend a tree planting event. </p>
                         <a href="#" class="hover-btn-new"><span>Read More</span></a>

                       
                    </div><!-- end messagebox -->
                </div><!-- end col -->
                
                <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12">
                    <div class="post-media wow fadeIn">
                        <img src="../assets/events3.png" alt="" class="img-fluid img-rounded">
                    </div><!-- end media -->
                    <div class="section-title row text-center">
                <div class="col-md-8 offset-md-2">
                    
                
                </div>
            </div>
                </div><!-- end col -->
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
	background: url(../assets/slider-03.jpg)no-repeat;
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