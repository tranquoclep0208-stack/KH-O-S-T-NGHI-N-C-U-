name: Khảo sát
description: Điền thông tin của bạn
title: "[Form] "
body:
  - type: input
    id: name
    attributes:
      label: Họ tên
    validations:
      required: true
  - type: input
    id: email
    attributes:
      label: Email
  - type: dropdown
    id: major
    attributes:
      label: Ngành học
      options:
        - Kinh doanh quốc tế
        - Kinh tế
        - Khác
    validations:
      required: true
  - type: textarea
    id: feedback
    attributes:
      label: Góp ý
