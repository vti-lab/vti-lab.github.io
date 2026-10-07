# Nguồn và giấy phép nội dung

VTI Lab là nền tảng ngân hàng kiến thức, đề luyện chứng chỉ và bài thực hành dành
cho đội ngũ VTI. Nội dung CKA được biên soạn lại từ tài liệu công khai. Ngân hàng
câu hỏi AWS được nhập từ nguồn cộng đồng, sau đó phân loại trạng thái kiểm chứng;
đây không phải nội dung chính thức của AWS.

## Nguồn chính

- [Linux Foundation CKA](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/): curriculum CKA v1.35 và trọng số năm domain.
- [Kubernetes v1.35 documentation](https://v1-35.docs.kubernetes.io/docs/): snapshot tài liệu chính thức, CC BY 4.0.
- [jayendrapatil/kubernetes-exercises](https://github.com/jayendrapatil/kubernetes-exercises): khung bài tập theo domain, MIT License, snapshot `380857a`.
- [DiptoChakrabarty/CKA-study-guide-exercises](https://github.com/DiptoChakrabarty/CKA-study-guide-exercises): tình huống và command thực hành, MIT License, snapshot `39c780c`.
- [aeciopires/learning-cka](https://github.com/aeciopires/learning-cka): danh mục nguồn học, GPL-3.0, snapshot `f6c7667`. Không sao chép nội dung GPL vào mã ứng dụng.
- [cncf/curriculum](https://github.com/cncf/curriculum): curriculum CKA v1.35 công khai, snapshot `ccaf7d1`.

## Ngân hàng câu hỏi AWS

- [finbertmds/examtopics](https://github.com/finbertmds/examtopics): dữ liệu cộng đồng cho SAA-C03 và SAP-C02, snapshot tải ngày 2026-07-19.
- [AWS Certified Solutions Architect - Associate (SAA-C03) Exam Guide](https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-associate-03/solutions-architect-associate-03.html): bốn domain và tỷ trọng chính thức.
- [AWS Certified Solutions Architect - Professional (SAP-C02) Exam Guide](https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-professional-02/solutions-architect-professional-02.html): bốn domain và tỷ trọng chính thức.
- License MIT của repository áp dụng cho phần mềm và tài liệu do repository phát hành; VTI Learning Lab không tuyên bố quyền sở hữu hoặc giấy phép đối với nội dung bên thứ ba được dẫn nguồn trong các file dữ liệu.
- Các câu hỏi cộng đồng được VTI Lab phân loại theo nội dung và tỷ trọng exam guide bằng bộ quy tắc tái lập được. Đây là mapping suy luận, không phải nhãn domain chính thức do AWS cung cấp.
- Mọi câu còn hoạt động đều được hiển thị. Câu chưa được kiểm chứng có cảnh báo riêng và không nên dùng làm đáp án chuẩn nếu chưa đối chiếu tài liệu chính thức.
- Bản dịch tiếng Việt và tiếng Nhật phục vụ học tập nội bộ; thuật ngữ sản phẩm và lệnh kỹ thuật được giữ theo tên chính thức khi cần thiết.

## Bài thực hành AWS

Các bài thực hành được biên soạn thành checklist đọc và kiểm chứng từ các repository
`aws-samples` có giấy phép MIT-0:

- [aws-security-hub-workshop](https://github.com/aws-samples/aws-security-hub-workshop)
- [serverless-resilience-workshop](https://github.com/aws-samples/serverless-resilience-workshop)
- [amazon-fsx-workshop](https://github.com/aws-samples/amazon-fsx-workshop)
- [sqs-ec2-graviton-spot](https://github.com/aws-samples/sqs-ec2-graviton-spot)
- [sample-aws-network-security-workshop](https://github.com/aws-samples/sample-aws-network-security-workshop)
- [achieving-operational-excellence-using-automated-playbook-and-runbook](https://github.com/aws-samples/achieving-operational-excellence-using-automated-playbook-and-runbook)
- [net-modernization](https://github.com/aws-samples/net-modernization)

Mỗi câu hỏi trong ứng dụng liên kết tới tài liệu dùng để kiểm chứng kiến thức.
Kubernetes, CNCF và Linux Foundation là nhãn hiệu của chủ sở hữu tương ứng.
AWS và các tên chứng chỉ AWS là nhãn hiệu của Amazon Web Services, Inc.
