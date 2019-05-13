<template>
    <div>
        <div class="mt-4 screen-footer">
            <div class="layer">
                <div class="row content-footer">
                    <div class="col-lg-4 col-sm-12">
                        <p style="font-weight: bold; font-size: 20px">VỀ CHỦ ĐẦU TƯ</p>
                        <p>VINHOMES SMART CITY TÂY MỖ ĐẠI MỖ</p>
                        <p>Sàn giao dịch bất động sản Vinhomes</p>
                        <p>B2,R3 Royal City, số 72A Nguyễn Trãi, P. Thượng Đình, Thanh Xuân, Hà Nội.</p>
                        <br>
                        <p>Hotline: 094.550.5885</p>

                    </div>
                    <div class="col-lg-4 col-sm-12">
                        <p style="font-weight: bold; font-size: 20px">ĐẠI ĐÔ THỊ THÔNG MINH ĐẲNG CẤP QUỐC TẾ</p>
                        <ul class="footer-commit">
                            <p>Thông tin, hình ảnh, các tiện ích trên website này chỉ mang tính chất minh hoạ tương đối và có thể được điều chỉnh theo quyết định của Chủ đầu tư tại từng thời điểm đảm bảo phù hợp quy hoạch và thực tế thi công dự án. 
Các thông tin, cam kết chính thức sẽ được quy định cụ thể tại Hợp đồng mua bán. Việc quản lý, vận hành và kinh doanh của khu đô thị sẽ theo quy định của Ban quản lý.</p>

                        </ul>
                    </div>
                    <form class="col-lg-4 col-sm-12" action="https://jumprock.co/mail/nguyenphu2476" method="post">
                        <p style="text-align: center; font-weight: bold; font-size: 20px">Đăng ký nhận tư vấn miễn phí</p>
                        <div class="input-group input-group-lg mb-3">
                            <div class="input-group-prepend">
                                <span class="input-group-text"><font-awesome-icon :icon="['fas', 'user']" :style="{color: '#424F7E'}" class="icon alt"/></span>
                            </div>
                            <input type="text" name="name" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Họ và tên*">
                        </div>
                        <div class="input-group input-group-lg mb-3">
                            <div class="input-group-prepend">
                                <span class="input-group-text"><font-awesome-icon :icon="['fas', 'phone']" :style="{color: '#424F7E'}" class="icon alt"/></span>
                            </div>
                            <input type="text" name="phone" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Số điện thoại*">
                        </div>
                        <div class="input-group input-group-lg mb-3">
                            <div class="input-group-prepend">
                                <span class="input-group-text"><font-awesome-icon :icon="['fas', 'envelope']" :style="{color: '#424F7E'}" class="icon alt"/></span>
                            </div>
                            <input type="email" name="email" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Email*">
                        </div>
                        <div style="text-align: center" class="mb-2">
                            <button type="submit" class="btn btn-register-footer">ĐĂNG KÝ NGAY</button>
                            <input type="hidden" name="after" value="https://vinhomestaymo.com.vn/category/notification">
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
  export default {
    data () {
      return {
        // msg: 'Welcome to Your Vue.js App'
      }
    },
    methods: {
      // btnRegister: function () {
      //   // this.$router.go(-1)
      //   console.log('back back')
      // }
      // pushPage: function () {
      //   this.$router.push({ name: 'Notification' })
      // }
    }
  }
</script>
