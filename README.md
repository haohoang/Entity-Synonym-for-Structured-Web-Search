Entity Synonymd for Structured Web Search

- Get search resulfs from Bing.ipynb: lấy 50 kết quả tìm kiếm đầu tiên khi truy vấn tên thực thể trên Bing search.
- Crawl IMDB.ipynb: đào nội dung phim trên imdb
- Find synonym candidates.ipynb: tìm kiếm các ứng viên có trong tập Orcas của từng thực thể dựa vào 50 link kiếm được
- Select candidates: tính ipc và icr cho từng candidates
- Model.ipynb: tìm ra thực thể tương đồng cuối cùng và đánh giá kết quả.
- result.csv: kết quả cuối cùng
    + movie: tên thực thể
    + query: tên ứng viên
    + clean_query: tên ứng viên sau khi loại bỏ nhiễu
    + url: các link chung giữa thực thể và ứng viên
    + ipc: chỉ số ipc của ứng viên
    + icr: chỉ số icr của ứng viên
    + similarity: độ tương đồng giữa ứng viên và thực thể được tính theo phương pháp đề xuất
    + trueLabel: cho biết ứng viên này có phải là thực thể tương đồng hay không, được tạo bởi con người. giá trị 'y': có, 'n': không
    + opredict: kết quả dự đoán dựa theo phương pháp gốc.
    + ipredict: kết quả dự đoán dựa theo phương pháp đề xuất.