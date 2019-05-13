<template>
    <div class="screen-posts-details">
        <div class="screen-new-posts-details row">
            <div class="col-lg-9 col-sm-12 posts-details">
                <div class="title-posts-details mb-3">Ngân hàng có hỗ trợ vay vốn khi mua nhà tại dự án Vinhomes Smart City</div>
                <p>Khi tìm hiểu và lựa chọn mua nhà điều đầu tiên khách hàng quan tâm đó là họ có nhận được những ưu đãi khi mua nhà hay không? Liệu phía ngân hàng có hỗ trợ vay vốn hay không? Nếu có thì chính sách vay vốn có ưu đãi gì hay không? Tất nhiên với dự án vinhomes Tây Mỗ cũng không ngoại lệ. Đã có rất nhiều nhiều khách hàng bày tỏ băn khoăn không biết phía ngân hàng có hỗ trợ vay vốn khi mua nhà tại dự án Vinhomes Tây Mỗ hay không? </p>

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




                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/cs100.jpg')" />
                                <b-card-footer style="text-align: center;">Thanh toán sớm 100%</b-card-footer>
                    </b-card>
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/cstd.jpg')" />
                                <b-card-footer style="text-align: center;">Thanh toán theo tiến độ</b-card-footer>
                    </b-card>
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/csvaynh.jpg')" />
                                <b-card-footer style="text-align: center;">Vay ngân hàng</b-card-footer>
                    </b-card>

             

              

             
                <form style="border: 1px solid #A0A7BE; padding: 1em; text-align: center" action="https://jumprock.co/mail/nguyenphu2476" method="post">
                    <h4>Đăng ký tư vấn miễn phí - Tải trọn bộ tài liệu Bảng giá - Chính sách bán hàng</h4>
                    
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text"><font-awesome-icon :icon="['fas', 'user']" :style="{color: '#424F7E'}" class="icon alt"/></span>
                        </div>
                        <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Họ và tên*">
                    </div>
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text"><font-awesome-icon :icon="['fas', 'phone']" :style="{color: '#424F7E'}" class="icon alt"/></span>
                        </div>
                        <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Số điện thoại*">
                    </div>
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text"><font-awesome-icon :icon="['fas', 'envelope']" :style="{color: '#424F7E'}" class="icon alt"/></span>
                        </div>
                        <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Email*">
                    </div>
                    <button type="submit" class="btn btn-register-posts-details">ĐĂNG KÝ NGAY</button>
                    <input type="hidden" name="after" value="https://vinhomestaymo.com.vn/category/notification">
                    <h3 class="mt-4" style="color: #424F7E">Hotline: 094.550.5885</h3>
                </form>
            </div>
            <div class="col-3">
                <div class="sidebar-posts-details">
                    <img class="details-new-posts-image" :src="require('../../assets/images/bannerto.jpg')" @click="showModal()"/>
                </div>
            </div>
        </div>
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
      }
    },
    methods: {
      showModal: function () {
        $('#exampleModalCenter').modal('show')
      }
    }
  }
</script>
