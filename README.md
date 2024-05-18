File PySpark.ipynb là một Jupyter Notebook được sử dụng để thực hiện các thao tác trên dữ liệu sử dụng Apache Spark thông qua PySpark.

Các hoạt động chính trong notebook này bao gồm:
  - Khởi tạo một phiên Spark bằng cách sử dụng SparkSession.
  - Đọc dữ liệu từ một file CSV vào một Resilient Distributed Dataset (RDD).
  - Đếm số lượng dòng trong RDD.
  - Thực hiện một thao tác Word Count trên một file văn bản khác. Điều này bao gồm việc tách từ, ánh xạ từng từ với giá trị 1, và sau đó giảm theo khóa để tính tổng số lần xuất hiện của mỗi từ.
