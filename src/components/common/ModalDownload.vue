<template>
    <div>
        <div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
            <div class="modal-dialog modal-dialog-centered" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h4 class="modal-title" id="exampleModalLongTitle" style="text-align: center; color: #54608A; font-weight: bold">NHẬN NGAY BẢNG GIÁ VÀ TÀI LIỆU - ĐĂNG KÝ THAM QUAN NHÀ MẪU</h4>
                         
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <form class="col-12" action="https://jumprock.co/mail/nguyenphu2476" method="post">
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
                                <input type="text" name="email" class="form-control" aria-label="Amount (to the nearest dollar)" placeholder="Email*">
                            </div>
                            <div class="mb-3" style="text-align: center">
                                <button type="submit" class="btn btn-register-modal-footer">ĐĂNG KÝ NGAY</button>
                                <input type="hidden" name="after" value="https://vinhomestaymo.com.vn/category/notification">
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
  export default {
    data () {
      return {
      }
    },
    methods: {
    }
  }
</script>
