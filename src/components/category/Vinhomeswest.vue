<template>
  	<div>
  	<div class="row mt-2 screen-home-vip">
		<div class="mb-2 col-12">
			<b-carousel
					id="carousel-fade"
					style="text-shadow: 0px 0px 2px #000"
					:interval="4000"
			>
				<b-carousel-slide id="slide-1" caption="" :img-src="require('../../assets/images/slide-1.jpg')"  @click.native="clickRegister()"/>
			</b-carousel>
		</div>
  		<div class="col-lg-9 col-sm-12 content-page-padding">
			<div class="content-page-detail">
				<p class="text1">VINHOMES SMART CITY - TÂY MỖ ĐẠI MỖ</p>
				<p class="text1">ĐẠI ĐÔ THỊ THÔNG MINH ĐẲNG CẤP QUỐC TẾ ĐẦU TIÊN Ở VIỆT NAM</p>
				<div class="image-block-vin"><img class="image-vinhomeswest mb-2" :src="require('../../assets/images/01tongquan.jpg')"/></div>
				<p class="text1">CHÍNH THỨC MỞ BÁN VINHOMES TÂY MỖ ĐẠI MỖ</p>
				<div class="text-pr"> 
					<ul>
						<p style="text-align: justify;"><strong><span style="color: #d4ca66;">🎁 Tòa căn hộ mở bán:</span></strong>H3, H5, H8 (Tiểu khu The Hero)</p>
						<p style="text-align: justify;"><strong><span style="color: #d4ca66;"> 🎁 Thông tin căn hộ được mở bán:</span></strong></p>
						<p>♦  Căn hộ Studio: Diện tích 28.2 - 36.4 m2, giá bán từ 930 Triệu - 1.1 tỷ</p>
						<p>♦  Căn hộ 1 phòng ngủ: Diện tích 42.8 - 48.1 m2, giá bán từ 1.2 - 1.5 tỷ</p>
						<p>♦  Căn hộ 2 phòng ngủ: Diện tích 53.7 - 65.4 m2, giá bán từ 1.6 - 2.2 tỷ</p>
						<p>♦ Căn hộ 3 phòng ngủ: Diện tích 74.1 - 76.2 m2, giá bán từ 2.3 - 2.9 tỷ</p>

						<p style="text-align: justify;"><strong><span style="color: #d4ca66;"> 🎁 Chính sách hỗ trợ vây vốn:</span></strong>Khách hàng tham gia mua căn hộ Vinhomes Smart City Tây Mỗ Đại Mỗ sẽ được tham gia chương trình hỗ trợ vay vốn từ ngân hàng Techcombank lên tới tối đa 70% giá trị căn hộ trong vòng tối đa 35 năm kèm các ưu đãi đặc biệt như sau:</p>
						<p>♦  LS 0% từ thời điểm mua cho đến ngày 31/10/2020</p>
						<p>♦  Ân hạn nợ gốc trong vòng 24 tháng</p>
						<p>♦  Miễn phạt lãi trả nợ trước hạn trong thời gian ưu đãi lãi suất hoặc sau 5 năm kể từ thời điểm vay.</p>
						<p>Lưu ý: Khách hàng chọn thanh toán theo tiến độ, không vay vốn sẽ được chiết khấu 2% giá trị căn hộ.</p>

						<p style="text-align: justify;"><strong><span style="color: #d4ca66;"> 🎁 Chính sách dành cho khách hàng thanh toán sớm:</span></strong>Khách hàng thanh toán 100% giá trị căn hộ bằng vốn tự có sẽ được chiết khấu 9% giá trị căn hộ.</p>

						<p style="text-align: justify;"><strong><span style="color: #d4ca66;"> 🎁Chính sách bão lãnh ngân hàng:</span></strong>Khách hàng không nhận bảo lãnh ngân hàng sẽ dược chiết khấu 1.5% giá trị căn hộ.</p>
					</ul>
				</div>

				<form class="form-mail" action="https://jumprock.co/mail/nguyenphu2476" method="post">
					<div class="form-group form-mail-custom">
						<label style="font-weight: bold; font-size: 24px; color: #ffffff">Nhận trọn bộ tài liệu Bảng giá - Chính sách bán hàng</label>
						<div class="form-group row">
							<div class="input-group col-lg-3 col-sm-12 mb-3">
								<div class="input-group-prepend">
									<span class="input-group-text"><font-awesome-icon :icon="['fas', 'user']" :style="{color: '#424F7E'}" class="icon alt"/></span>
								</div>
								<input type="text" name="name" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Họ và tên*">
							</div>
							<div class="input-group col-lg-3 col-sm-12 mb-3">
								<div class="input-group-prepend">
									<span class="input-group-text"><font-awesome-icon :icon="['fas', 'phone']" :style="{color: '#424F7E'}" class="icon alt"/></span>
								</div>
								<input type="text" name="phone" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Số điện thoại*">
							</div>
							<div class="input-group col-lg-3 col-sm-12 mb-3">
								<div class="input-group-prepend">
									<span class="input-group-text"><font-awesome-icon :icon="['fas', 'envelope']" :style="{color: '#424F7E'}" class="icon alt"/></span>
								</div>
								<input type="email" name="email" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Email*">
							</div>
							<div class="col-lg-3 col-sm-12 mb-3">
								<button type="submit" class="btn btn-register-now">TẢI XUỐNG NGAY</button>
								<input type="hidden" name="after" value="https://vinhomestaymo.com.vn/category/notification">
							</div>
						</div>
					</div>
				</form>

			</div>


			<div class="content-page-overview mt-3">
				<p class="text-overview" style="text-align: center">TỔNG QUAN VINHOMES SMART CITY</p>
				<div class="image-line-overview"></div>
				<p></p>
				<div class="oveview-li">
					<p>Dự án Vinhomes Đại Mỗ – Tây Mỗ có tên gọi là Vinhomes Smart City “Đại Đô Thị Chuẩn Thông Minh Đẳng Cấp Quốc Tế”, hiện là cái tên tạo nên “cơn sốt” trên thị trường bất động sản miền Bắc khi nhận được sự quan tâm của đông đảo khách hàng và giới đầu tư.</p>
					<ul>

<li><p style="text-align: justify;"><strong>Tên chính thức:</strong>Vinhomes Smart City</a> (Tên gọi cũ là Vincity Sportia)</p>
</li>
<li><p style="text-align: justify;"><strong>Chủ đầu tư:</strong> Vingroup</p>
</li>
<li><p><strong>Đơn vị quản lý &amp; vận hành:</strong>Vinhomes</a></p>
</li>
<li><p style="text-align: justify;"><strong>Đơn vị thi công:</strong> Coteccons</p>
</li>
<li><p style="text-align: justify;"><strong>Tổng diện tích đất dự án:</strong> Khoảng 280 ha</p>
</li>
<li><p style="text-align: justify;"><strong>Mật độ xây dựng:</strong> 14.7%</p>
</li>
<li><p style="text-align: justify;"><strong>Quy mô phát triển:</strong> Bao gồm khoảng 58 tòa tháp chung cư</p>
</li>
<li><p style="text-align: justify;"><strong>Loại hình phát triển:</strong> Căn hộ Studio, 1, 2, 3 phòng ngủ</p>
</li>
<li><p style="text-align: justify;"><strong>Thời điểm khởi công:</strong> Năm 2018</p>
</li>
<li><p style="text-align: justify;"><strong>Thời điểm bàn giao:</strong> Tháng 8/2020</p></li>

					</ul>
				</div>
						<b-card no-body>
								<b-card-img bottom :src="require('../../assets/images/02tongquan.jpg')" />
								<b-card-footer style="text-align: center;">Phối cảnh tổng thể Vinhomes Smart City</b-card-footer>
					</b-card>

				<p></p>
				<p style="font-weight: bold;">VỊ TRÍ DỰ ÁN</p>
				<p>Vinhomes Smart City tọa lạc trên địa phận 2 phường Tây Mỗ &amp; Đại Mỗ, quận Nam Từ Liêm, Hà Nội. Với lợi thế ôm trọn cả 3 cung đường Đại lộ Thăng Long, Quốc lộ 70 &amp; đường Lê Trọng Tấn kéo dài, Vinhomes Tây Mỗ Đại Mỗ sở hữu hệ thống giao thông hoàn chỉnh bậc nhất khu vực phía Tây Hà Nội, vừa dễ dàng kết nối khu vực trung tâm thành phố, vừa thuận tiện trong việc di chuyển đến các tỉnh thành Hòa Bình, Phú Thọ...</p>
				<p>Dự án Vinhomes Smart City Kết nối với các vị trí sau rất thuận tiên cho việc di chuyển:</p>
				<ul>
				<li><p style="text-align: justify;"></p>500m đến Thiên Đường Bảo Sơn</li>
				<li><p style="text-align: justify;"></p>1.5 km đến khu đô thị Vinhomes Thăng Long</li>
				<li><p style="text-align: justify;"></p>3 km đến Keangnam</li>
				<li><p style="text-align: justify;"></p>3.5 km đến sân vận động Mỹ Đình</li>
				<li><p style="text-align: justify;"></p>4 km đến trung tâm hội nghị quốc gia</li>
				<li><p style="text-align: justify;"></p>4 km Khách sạn 5* JW Marriott</li>
				<li><p style="text-align: justify;"></p>4 km Khách sạn 5* Grand Plaza</li>

				</ul>

					<b-card no-body>
								<b-card-img bottom :src="require('../../assets/images/vitri.jpg')" />
								<b-card-footer style="text-align: center;">Vị trí Vinhomes Smart City</b-card-footer>
					</b-card>

			</div>


<div class="page-smart-vinhome mt-3">
				<p></p>
				<p class="text-page-smart">CUỘC SỐNG TIỆN NGHI VÀ ĐẲNG CẤP TẠI VINHOMES SMART CITY</p>
				<div class="image-line-smart mb-3"></div>
				<p><strong>Vinhomes Smart City</strong> là Đại đô thị thông minh đẳng cấp quốc tế đầu tiên tại Việt Nam kiến tạo một hệ sinh thái thông minh toàn diện nhằm mang đến cuộc sống năng động, hiện đại và thời thượng</p>
				<p>Hệ sinh thái thông minh dựa trên 4 trục cốt lõi, gồm:</p>
				<ul>
					<li><p style="text-align: justify;"></p><strong>Smart Security</strong> (an ninh thông minh): Camera trí tuệ nhân tạo đa lớp thông minh, An ninh thang máy, Hệ thống cảnh báo ô nhiễm môi trường, PCCC thông minh, Giao thông thông minh.</li>
					<li><p style="text-align: justify;"></p><strong>Smart Management</strong> (vận hành thông minh): Trung tâm điều hành 24/7 ứng dụng các CN tiên tiến nhất (AI, IoT, Internet vạn vật); Đậu xe thông minh, Hạ tầng thông minh, HT Intercom.</li>
					<li><p style="text-align: justify;"></p><strong>Smart Community</strong> (cộng đồng thông minh): Quản trị thông minh qua app cư dân, thương mại thông minh, Smart KID Pay.</li>
					<li><p style="text-align: justify;"></p><strong>Smart Home</strong> (căn hộ thông minh – tùy thuộc dòng sản phẩm của Vinhomes): Điều khiển tự động, tính năng điều khiển thông minh qua smartphone/ giọng nói, vòng tay thông minh (dành cho trẻ em và người già).</li>
				</ul>


				<div class="row">
					<div class="col-lg-6 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhom-stay-1" :src="require('../../assets/images/06security.jpg')"/>
					</div>
					<div class="col-lg-6 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhom-stay-1" :src="require('../../assets/images/06management.jpg')"/>
					</div>
					<div class="col-lg-6 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhom-stay-1" :src="require('../../assets/images/06community.jpg')"/>
					</div>
					<div class="col-lg-6 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhom-stay-1" :src="require('../../assets/images/06home.jpg')"/>
					</div>

				</div>


				<div class="row">
					<div class="col-lg-6 col-sm-12 div-smart-padding-mobile">
						<p></p>
						<p>TIỆN ÍCH</p>
						<p>Lần đầu tiên tại dự án Vinhomes Smart City Tây Mỗ Đại Mỗ, ông lớn Vingroup đã cho ra mắt hệ thống công viên thể thao ngoài trời lớn nhất Việt Nam bao gồm: Hơn 1000 máy tập thể thao ngoài trời và 200 máy tập nằm rải rác tại các phân khu. Hơn 200 sân thể thao các loại bao gồm: sân tennis, sân bóng rổ, sân cầu lông, sân bóng chuyền hơi, sân bóng đá mini… nhằm phục vụ tối ưu nhu cầu chơi thể thao, nâng cao sức khỏe của cư dân tại dự án. 8 bể bơi trong nhà và ngoài trời…</p>
						<div class="text-pr">
							<ul>
								<li>Công viên GYM lớn nhất Việt Nam 1000 máy tập Gym</li>
								<li>70 khu vui chơi, 200 sân tập thể thao, 9 bể bơi…</li>
								<li>Công viên, vườn hoa, 3 công viên BBQ, hồ cảnh quan, tiểu cảnh, sông hồ…</li>
								<li>Dịch vụ y tế, phòng khám, bệnh viện Vinmec.</li>
								<li>Trường học liên cấp Vinschool, trường công lập cấp 1,2,3 Tây Mỗ, Đại Mỗ…</li>
							</ul>
						</div>
					</div>
					<div class="col-lg-6 col-sm-12 div-smart-padding-mobile">
						<p></p>
						<p>CÔNG VIÊN THỂ THAO</p>
						<p>Tổ hợp Công viên Thể thao có diện tích lớn nhất từ trước tới nay hình thành một khu vui chơi, giải trí, rèn luyện sức khỏe tích hợp cho các cư dân VinCity Sportia. Hệ thống tiện ích trong Công viên Thể thao bao gồm:</p>
						<div class="text-pr">
							<ul>
								<li>Công viên Gym</li>
								<li>Công viên Dưỡng sinh</li>
								<li>Công viên Patin</li>
								<li>Công viên Xe đạp địa hình</li>
								<li>Công viên Aerobic</li>
								<li>Công viên Khiêu vũ</li>
								<li>Hệ thống sân tập thể thao</li>
								<li>Khu Chèo thuyền Kayak</li>
								<li>Công viên Dã ngoại</li>
							</ul>
						</div>
					</div>
				</div>
				<div class="row">
					<div class="col-lg-6 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhom-stay-1" :src="require('../../assets/images/tienich01.jpg')"/>
					</div>
					<div class="col-lg-6 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhom-stay-1" :src="require('../../assets/images/tienich02.jpg')"/>
					</div>
				</div>
				<div class="row">
					<div class="col-lg-4 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhomeswest-1" :src="require('../../assets/images/tienich03.jpg')"/>
					</div>
					<div class="col-lg-4 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhomeswest-1" :src="require('../../assets/images/tienich04.jpg')"/>
					</div>
					<div class="col-lg-4 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhomeswest-1" :src="require('../../assets/images/tienich05.jpg')"/>
					</div>
				</div>
				<div class="row">
					<div class="col-lg-4 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhomeswest-1" :src="require('../../assets/images/tienich06.jpg')"/>
					</div>
					<div class="col-lg-4 col-sm-12 div-image-transition mb-1">
						<img class="image-vinhomeswest-1" :src="require('../../assets/images/tienich07.jpg')"/>
					</div>
					<div class="col-lg-4 col-sm-12 div-image-transition">
						<img class="image-vinhomeswest-1" :src="require('../../assets/images/tienich08.jpg')"/>
					</div>
				</div>
			</div>





			<div class="content-page-design">
				<p></p>
				<p class="text-page-design">MẶT BẰNG VÀ THIẾT KẾ CĂN HỘ</p>
				<div class="image-line-design mb-3"></div>
				<p>Đại đô thị Vinhomes Smart City được phát triển thành 5 tiểu khu chính: The Dream, The Power, The Sun, The Hero, The Victory. Trong đó, The Hero sẽ là tiểu khu được cho ra mắt đầu tiên tại dự án.</p>



					<b-card no-body>
								<b-card-img bottom :src="require('../../assets/images/04matbangtongthe.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng tổng thể dự án</b-card-footer>
					</b-card>
					<p></p>
					<b-card no-body>
								<b-card-img bottom :src="require('../../assets/images/05matbangthehero.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng phân khu The Hero</b-card-footer>
					</b-card>

				<p></p>	
				<p class="text-page-design">MẶT BẰNG CHI TIẾT</p>
				<div>
					<b-card no-body>
						<b-tabs card nav-class="justify-content-center">
							<b-tab no-body title="Toà H01">
								<b-card-img bottom :src="require('../../assets/images/h01.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng Toà H01</b-card-footer>
							</b-tab>

							<b-tab no-body title="Toà H02">
								<b-card-img bottom :src="require('../../assets/images/h02.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng Toà H02</b-card-footer>
							</b-tab>

							<b-tab no-body title="Toà H03">
								<b-card-img bottom :src="require('../../assets/images/h03.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng Toà H03</b-card-footer>
							</b-tab>

							<b-tab no-body title="Toà H05">
								<b-card-img bottom :src="require('../../assets/images/h05.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng Toà H05</b-card-footer>
							</b-tab>

							<b-tab no-body title="Toà H06">
								<b-card-img bottom :src="require('../../assets/images/h06.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng Toà H06</b-card-footer>
							</b-tab>

							<b-tab no-body title="Toà H08">
								<b-card-img bottom :src="require('../../assets/images/h08.jpg')" />
								<b-card-footer style="text-align: center;">Mặt bằng Toà H08</b-card-footer>
							</b-tab>

						</b-tabs>
					</b-card>
				</div>

				<p></p>
				<p class="text-page-design">CÁC LOẠI THIẾT KẾ CĂN HỘ</p>

				<div>
					<b-card no-body>
						<b-tabs card nav-class="justify-content-center">

							<b-tab no-body title="Căn Studio">
								<b-card-img bottom :src="require('../../assets/images/canstudio.jpg')" />
								<b-card-footer style="text-align: center;">Căn hộ Studio </b-card-footer>
							</b-tab>

							<b-tab no-body title="Căn 1PN">
								<b-card-img bottom :src="require('../../assets/images/can1pn.jpg')" />
								<b-card-footer style="text-align: center;">Căn hộ 1 phòng ngủ</b-card-footer>
							</b-tab>

							<b-tab no-body title="Căn 2PN">
								<b-card-img bottom :src="require('../../assets/images/can2pn.jpg')" />
								<b-card-footer style="text-align: center;">Căn hộ 2 phòng ngủ</b-card-footer>
							</b-tab>

							<b-tab no-body title="Căn 2PN+1">
								<b-card-img bottom :src="require('../../assets/images/can2pn1.jpg')" />
								<b-card-footer style="text-align: center;">Căn hộ 2 phòng ngủ + 1 đa năng</b-card-footer>
							</b-tab>

							<b-tab no-body title="Căn 3PN">
								<b-card-img bottom :src="require('../../assets/images/can3pn.jpg')" />
								<b-card-footer style="text-align: center;">Căn hộ 3 phòng ngủ</b-card-footer>
							</b-tab>

						</b-tabs>
					</b-card>
				</div>
			</div>


			
			<div class="screen-page-pay mt-3">
				<p class="text-page-pay">GIÁ BÁN VÀ CHÍNH SÁCH BÁN HÀNG</p>
				<div class="image-line-pay"></div>
				<div class="row">
					<div class="col-lg-12 col-sm-12 div-padding-tablets" style="text-align: left;">
						<p>
						<li>Chỉ Cần 10% Giá Trị Căn Hộ (GTCH) Ký Ngay Hợp Đồng Mua Bán. Trong Vòng 9 Tháng Đóng Đủ 30%.</li>
						<li>Hỗ Trợ Trả Góp Trong Vòng 35 năm, Số dư nợ lên đến 70% GTCH. Hỗ trợ lãi suất 0% cho 70% GTCH kể từ thời điểm ký hợp đồng mua bán đến 31/10/2020.</li>
						<li>Khách hàng không nhận bảo lãnh Ngân Hàng: Chiết khấu 1.5% vào giá trước VAT và kinh phí bảo trì.</li>
						<li>Chiết khấu lên tới 9% với thanh toán sớm 100% (với KH là người VN).</li>
						<li>Với Khách hàng đóng tiền theo tiến độ được chiết khấu 2% giá bán trước VAT và kinh phí bảo trì.</li>
						</p>

						<b-card no-body>
								<b-card-img bottom :src="require('../../assets/images/csbh.jpg')" />
								<b-card-footer style="text-align: center;">Chính sách bán hàng</b-card-footer>
					</b-card>

					<p></p>

					</div>
					<form class="form-mail form-register-custom" action="https://jumprock.co/mail/nguyenphu2476" method="post">
						<div class="form-group form-mail-custom">
							<p></p>
							<label style="font-weight: bold; font-size: 24px; color: #424F7E">Tải xuống Bảng giá căn hộ - Chính sách bán hàng</label>
							<div class="form-group row pl-3">
								<div class="input-group col-lg-4 col-sm-12 mb-3">
									<div class="input-group-prepend">
										<span class="input-group-text"><font-awesome-icon :icon="['fas', 'user']" :style="{color: '#424F7E'}" class="icon alt"/></span>
									</div>
									<input type="text" name="name" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Họ và tên*">
								</div>
								<div class="input-group col-lg-4 col-sm-12 mb-3">
									<div class="input-group-prepend">
										<span class="input-group-text"><font-awesome-icon :icon="['fas', 'phone']" :style="{color: '#424F7E'}" class="icon alt"/></span>
									</div>
									<input type="text" name="phone" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Số điện thoại*">
								</div>
								<div class="input-group col-lg-4 col-sm-12 mb-3">
									<div class="input-group-prepend">
										<span class="input-group-text"><font-awesome-icon :icon="['fas', 'envelope']" :style="{color: '#424F7E'}" class="icon alt"/></span>
									</div>
									<input type="email" name="email" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Email*">
								</div>
							</div>
							<div style="text-align: center">
								<button type="submit" class="btn btn-register-now">TẢI XUỐNG NGAY</button>
								<input type="hidden" name="after" value="https://vinhomestaymo.com.vn/category/notification">
							</div>
						</div>
					</form>
				</div>
			</div>
  		</div>
  		<div class="col-3">
  			<div class="card card-Custom" style="width: 100%">
			  <div class="card-header card-header-sidebar">
			    Tìm hiểu Vinhomes Smart City
			  </div>
			  <!--<ul class="list-group list-group-flush">-->
			    <!--<li class="list-group-item">SUNSINE CTTY - NGHỆ THUẬT SỐNG THƯỢNG LƯU</li>-->
			    <!--<li class="list-group-item">TỔNG QUAN SUNSINE CITY VÕ CHÍ CÔNG</li>-->
			    <!--<li class="list-group-item">MẶT BẰNG VÀ THIẾT KẾ CĂN HỘ SUNSINE CITY</li>-->
			    <!--<li class="list-group-item">CUỘC SỐNG TIỆN NGHI VÀ ĐẲNG CẤP TẠI SUNSINE CITY</li>-->
			    <!--<li class="list-group-item">GIÁ BÁN VÀ TIẾN ĐỘ THANH TOÁN</li>-->
			  <!--</ul>-->
				<button type="button" v-scroll-to="{el: '.content-page-detail', offset: scrollOffset, duration: 1000}" class="btn btn-sidebar-details mb-1 mt-1">VINHOMES SMART CITY</button>
				<button type="button" v-scroll-to="{el: '.content-page-overview', offset: scrollOffset, duration: 1000}" class="btn btn-sidebar-overview mb-1">TỔNG QUAN DỰ ÁN</button>
				<button type="button" v-scroll-to="{el: '.page-smart-vinhome', offset: scrollOffset, duration: 1000}" class="btn btn-sidebar-smart mb-1">TIỆN ÍCH THÔNG MINH</button>
				<button type="button" v-scroll-to="{el: '.content-page-design', offset: scrollOffset, duration: 1000}" class="btn btn-sidebar-design mb-1">MẶT BẰNG VÀ THIẾT KẾ</button>
				<button type="button" v-scroll-to="{el: '.screen-page-pay', offset: scrollOffset, duration: 1000}" class="btn btn-sidebar-pay mb-1">BẢNG GIÁ & CHÍNH SÁCH BÁN HÀNG</button>
			  <!--<div class="card-header logo-banner" @click="btnRegisterBanner"></div>-->
				<img class="card-header logo-banner" :src="require('../../assets/images/banner.jpg')" @click="btnRegisterBanner"/>
			</div>	
  		</div>
  	</div>
	  <ModalDownload></ModalDownload>
  </div>
</template>

<script>
import ModalDownload from '../common/ModalDownload.vue'
export default {
  components: {
    ModalDownload
  },
  data () {
    return {
      scrollOffset: -window.innerWidth * 0.035
    }
  },
  created: function () {
    // console.log(window.innerWidth,this.scrollOffset, 'window width')
  },
  methods: {
  	clickRegister: function () {
  		console.log('123123')
  		$('#exampleModalCenter').modal('show')
  	},
  	btnRegisterBanner: function () {
  		$('#exampleModalCenter').modal('show')
  	}
  }
}
</script>
