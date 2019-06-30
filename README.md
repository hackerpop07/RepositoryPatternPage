# RepositoryPatternPage
Repository Pattern
Repository Pattern là một mẫu kiến trúc cho phép chúng ta tách biệt các tầng khác nhau của ứng dụng, giúp cho mã nguồn trở nên trong sáng và dễ duy trì và mở rộng hơn. Các tầng trong repository pattern bao gồm:

Tầng controller: Xử lý request và response của HTTP
Tầng service: Xử lý các logic nghiệp vụ
Tầng repository: Xử lý các thao tác truy xuất CSDL

Triển khai repository pattern trong Laravel

Để triển khai repository pattern, chúng ta lần lượt thực hiện các thao tác sau:
Xây dựng tầng repository
Xây dựng tầng service. Sử dụng cơ chế dependency injection để tiêm repository vào trong service.
Xây dựng tầng controller. Sử dụng cơ chế dependency injection để tiêm service vào trong controller.
