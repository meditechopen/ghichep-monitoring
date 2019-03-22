## Giới thiệu tổng quan về bộ công cụ Graphite + CollectD + Grafana


Đây là một bộ công cụ mã nguồn mở dùng để thu thập, thống kê, lưu trữ số liệu của máy chủ và hiển thị một cách trực quan cho người dùng.

**Graphite** 

Là một công cụ cho phép lưu trữ các metric của hệ thống và truy xuất dữ liệu theo thời gian thực.

Nó cũng cung cấp một giao diện web cho phép render đồ thị phục vụ cho nhiều mục đích, cung cấp URL API để có thể nhúng vào các webpages khác, hoặc xuất ra các định dạng file lưu trữ khác nhau như JSON, CSV,...

**CollectD** Dùng để thu thập các metric (có thể thực hiện lưu trữ hoặc không) đẩy về cho graphite, với nhiều các plugin khác nhau, cho phép CollectD thu thập nhiều dạng metric và đẩy về graphite theo nhiều cách khác nhau.

**Grafana** Là một giao diện đồ họa, thực hiện truy xuất vào cơ sở dữ liệu, ở đây là Graphite (ngoài ra còn hỗ trợ để add nhiều loại data source khác), render nhiều loại đồ thị đa dạng trực quan phục vụ theo nhiều mục đích người dùng.

<img src="../img/2.png">