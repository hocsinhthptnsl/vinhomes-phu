<template>
    <div class="screen-posts-details">
        <div class="screen-new-posts-details row">
            <div class="col-lg-9 col-sm-12 posts-details">
                <div class="title-posts-details mb-3">Cập Nhật Tiến Độ Thi Công Dự Án Vinhomes Smart City Tây Mỗ Đại Mỗ</div>
                <p>Với những khách hàng đang có nhu cầu mua nhà chung cư thì tiến độ xây dựng của dự án đó là điều đáng được quan tâm nhất.</p>

                <p>Khi nhắc tới tập đoàn VinGroup nhiều người thường nghĩ ngay đến những sản phẩm bất động sản cao cấp vô cùng thành công và nổi tiếng trên thị trường và quan trọng hơn hết là mọi dự án của VinGroup đều đạt đúng tiến độ xây dựng cũng như bàn giao nhà cho mọi người như Vinhomes, VinCity, Vincom, Vinpearl.</p>

       
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/tiendo01.jpg')" />
                    </b-card>
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/tiendo02.jpg')" />
                    </b-card>
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/tiendo03.jpg')" />
                    </b-card>

                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/tiendo04.jpg')" />
                    </b-card>
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/tiendo05.jpg')" />
                    </b-card>
                    <b-card no-body>
                                <b-card-img bottom :src="require('../../assets/images/tiendo06.jpg')" />
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
