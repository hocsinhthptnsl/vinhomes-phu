<template>
    <div class="screen-posts">
        <div class="screen-new-posts mt-3">
            <h5 class="mb-3">Tin tức</h5>
            <div class="row">
                <div class="col-lg-9 col-sm-12 block-new-posts">
                    <div class="row block-1 mb-3">
                        <div class="col-lg-6 col-sm-12 col-md-12 div-res-image">
                            <img class="posts-image-1" :src="require('../../assets/images/vitri.jpg')" @click="watchDetailsPost()"/>
                        </div>
                        <div class="col-lg-6 col-sm-12 div-res-image">
                            <p style="font-weight: bold; cursor: pointer;" @click="watchDetailsPost()">Vị trí Vinhomes Smart City Tây Mỗ Đại Mỗ tạo nên ước mơ nâng tầm sống đẳng cấp</p>
                            <p>Gần đây, Vingroup đã cho ra mắt hàng loạt các siêu phẩm ấn tượng về lĩnh vực bất động sản. Và một trong những dự án được người dân quan tâm hàng đầu hiện nay chính là Vinhomes Smart City Tây Mỗ Đại Mỗ. Dự án được kì vọng  …</p>
                            <button type="button" class="btn" style="padding: 0 !important;" @click="watchDetailsPost()">Xem chi tiết</button>
                            <br><br><br>
                        </div>
                    </div>
                    <div class="row block-1 mb-3">
                        <div class="col-lg-6 col-sm-12 col-md-12 div-res-image">
                            <img class="posts-image-1" :src="require('../../assets/images/tienich01.jpg')" @click="watchDetailsPost()"/>
                        </div>
                        <div class="col-lg-6 col-sm-12 div-res-image">
                            <p style="font-weight: bold; cursor: pointer;" @click="watchDetailsPost()">Khám phá chuỗi tiện ích hoàn hảo chỉ có tại Vinhomes Smart City Tây Mỗ Đại Mỗ</p>
                            <p>Dự án VinCity Tây Mỗ Đại Mỗ hiện đã chính thức ra mắt trên thị trường với tên gọi Vinhomes Smart City. Lấy cảm hứng từ phong cách Singapore và hơn thế nữa, Vinhomes Tây Mỗ Đại Mỗ được kì vọng …</p>
                            <button type="button" class="btn" style="padding: 0 !important;" @click="watchDetailsPost()">Xem chi tiết</button>
                            <br><br><br>
                        </div>
                    </div>
                    <div class="row block-1 mb-3">
                        <div class="col-lg-6 col-sm-12 col-md-12 div-res-image">
                            <img class="posts-image-1" :src="require('../../assets/images/tiendo01.jpg')" @click="watchDetailsPost()"/>
                        </div>
                        <div class="col-lg-6 col-sm-12 div-res-image">
                            <p style="font-weight: bold; cursor: pointer;" @click="watchDetailsPost()">Cập Nhật Tiến Độ Thi Công Dự Án Vinhomes Smart City Tây Mỗ Đại Mỗ</p>
                            <p>Với những khách hàng đang có nhu cầu mua nhà chung cư thì tiến độ xây dựng của dự án đó là điều đáng được quan tâm nhất …</p>
                            <button type="button" class="btn" style="padding: 0 !important;" @click="watchDetailsPost()">Xem chi tiết</button>
                            <br><br><br>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 sidebar-posts">
                    <img class="details-posts-image" :src="require('../../assets/images/bannerto.jpg')" @click="showBanner()"/>
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
      watchDetailsPost: function () {
        this.$router.push({ name: 'Doitacthicong' })
        console.log('sss')
      },
      showBanner: function () {
        $('#exampleModalCenter').modal('show')
      }
    }
  }
</script>
