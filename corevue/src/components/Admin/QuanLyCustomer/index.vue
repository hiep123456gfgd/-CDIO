<template>

    <div class="col-12">
            <div class="card  shadow-lg p-3 mb-5 bg-body rounded">
                <div class="card-header mt-2">
                    <div class="row">
                        <div class="col-6">
                            <h5>Quản Lý Khách Hàng</h5>
                        </div>
                        
                    </div>
                </div>
                <div class="card-body">
                    <div class="row">
        <div class="col-lg-12">
            <div class="card">
                <div class="card-body">
                    <table class="table table-bordered mb-0">
                        <thead>
                            <tr class="text-center">
                                <th>#</th>
                                <th>Họ Và Tên</th>
                                <th>Email</th>
                                <th>Số Điện Thoại</th>
                                <th>Trạng Thái</th>
                                <th>Kích Hoạt</th>
                                <th>Action</th>
                            </tr>
                        </thead>
                        <tbody>
                            
                                <tr class="align-middle">
                                    <th class="text-center">#</th>
                                    <td>#</td>
                                    <td>#</td>
                                    <td class="text-center">#</td>
                                    <td class="text-center">
                                        
                                        <button class="btn btn-danger me-1">
                                            Tạm Tắt
                                        </button>
                                    </td>
                                    <td class="text-center">
                                        <button class="btn btn-warning me-1" >
                                            Chưa Kích Hoạt
                                        </button>
                                        
                                    </td>
                                    <td class="text-center">
                                        <button class="btn btn-primary me-1" data-bs-toggle="modal" data-bs-target="#capNhatKhachhangModal">Cập Nhật</button>
                                        
                                        <button class="btn btn-danger"  data-bs-toggle="modal" data-bs-target="#xoaKhachhangModal">Xóa</button>
                                    </td>
                                </tr>
                                <tr class="align-middle">
                                    <th class="text-center">#</th>
                                    <td>#</td>
                                    <td>#</td>
                                    <td class="text-center">#</td>
                                    <td class="text-center">
                                        <button class="btn btn-success me-1">
                                            Hoạt Động
                                        </button>
                                        
                                    </td>
                                    <td class="text-center">
                                        
                                        <button  class="btn btn-primary me-1">
                                            Đã Kích Hoạt
                                        </button>
                                    </td>
                                    <td class="text-center">
                                        <button class="btn btn-primary me-1" data-bs-toggle="modal" data-bs-target="#capNhatKhachhangModal">Cập Nhật</button>
                                        
                                        <button class="btn btn-danger"  data-bs-toggle="modal" data-bs-target="#xoaKhachhangModal">Xóa</button>
                                    </td>
                                </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
                </div>
            </div>
        </div>
    <div class="modal fade" id="capNhatKhachhangModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Cập Nhật Khách Hàng</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="col-md-12 mb-2">
                        <label class="form-label">Họ và Tên</label>
                        <input  type="text" class="form-control">
                    </div>
                    <div class="col-md-12 mb-2">
                        <label class="form-label">Email</label>
                        <input type="email" class="form-control">
                    </div>
                    <div class="col-md-12 mb-2">
                        <label class="form-label">Số Điện Thoại</label>
                        <input  type="text" class="form-control">
                    </div>
                    
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal" >Xác Nhận</button>
                </div>
            </div>
        </div>
    </div>

    <div class="modal fade" id="xoaKhachhangModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Xóa Khách Hàng</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="alert alert-danger border-0 bg-danger alert-dismissible fade show py-2">
                        <div class="d-flex align-items-center">
                            <div class="font-35 text-white"><i class="bx bxs-message-square-x"></i>
                            </div>
                            <div class="ms-3">
                                <h6 class="mb-0 text-white">Cảnh Báo!</h6>
                                <div class="text-white">Bạn Có chắc chắn xóa tài khoản <b> #</b> này không!</div>
                            </div>
                        </div>
                        <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
                    </div>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal" >Xác Nhận</button>
                </div>
            </div>
        </div>
    </div>

    <div class="modal fade" id="doiMatKhauKhachHangModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Đổi Mật Khẩu</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="col-md-12 mb-2">
                        <label class="form-label">Mật Khẩu Mới</label>
                        <input  type="text" class="form-control" placeholder="Nhập vào mật khẩu mới">
                    </div>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal" >Xác Nhận</button>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    
</style>