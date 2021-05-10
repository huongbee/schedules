// hàm random 
```
@params arrSource: mảng chứa các phần tử cần random
@params arrExclude: mảng chưa các phần tử loại trừ
@return các phần tử ngẫu nhiên trong arrSource và không nằm trong arrExclude
```

// hàm phân bổ TKB
```
// sắp xếp các tiết học đặc biệt trước (Sắp các môn đặc biệt vào các tiết được thiết lập vào các lớp)

// lặp qua các lớp ở input
  // todo: Kiểm tra số tiết tối thiểu đầu vào với số tiết tối thiểu mà lớp đó phải học (sum: số tiết tối thiểu của mỗi môn đã thiếp lập cho lớp đó)
  // random môn của lớp
  do{
    if(tìm thấy môn){
      // random giáo viên
      do{
        if(lớp học đã được xếp môn này => giáo viên đã được lưu lại => phải sử dụng lại giáo viên này){

        }else{
          // random giáo viên ứng với môn và lớp này
        }
        if(tìm thấy giáo viên){
          // random thứ (ngày trong tuần)
          do{
            if(tìm ra thứ){
              do{
                if(tìm ra tiết){
                  // Kiểm tra điều kiện sắp xếp ( kiểm tra lịch làm việc của giáo viên && kiểm tra tiết này giáo viên đã dạy ở lớp khác chưa)
                  if(thỏa mã điều kiện sắp xếp){
                    // lưu lại và bắt đầu lại bước random môn
                    // đánh dấu môn này đã sắp xếp
                    // lưu lại giáo viên được phân bổ cho môn này
                    // lưu lại tiết và thứ đã phân bổ cho lớp này để loại trừ khi random lần sau
                  }
                }else{
                  //thêm thứ này vào blacklist thứ => danh sách thứ random lần sau sẽ không có thứ này
                }
              }while(Khi tìm ra tiết mà không thoản mãn điều kiện sắp xếp)
            }else{
              // thêm giáo viên này vào blacklist giáo viên => dánh sách random lần sau sẽ không có giáo viên này
            }
          }while(Khi random có thứ nào điều kiện sắp xếp không thỏa mãn )
        }else{
          // thêm môn này vào blacklist môn => danh sách lớp random lần sau sẽ không có môn này
        }
      }while(Khi tìm được giáo viên mà không thoản mãn điều kiện sắp xếp)
    }else{
      Báo lỗi không thể xếp TKB
    }
  }while(Khi tìm random có môn mà không thoản mãn điều kiện sắp xếp)
```
