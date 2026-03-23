# Bài tập giỏi 1 - Complex Resources

- TH1: Lấy tất cả lịch hẹn của một bác sĩ cụ thể (theo doctorId):
GET /api/v1/doctors/{doctorId}/appointments

- TH2: Lấy một đơn thuốc cụ thể của một bệnh nhân cụ thể:
GET /api/v1/patients/{patientId}/prescriptions/{prescriptionId}

- TH3: Thêm một đơn thuốc mới cho bệnh nhân:
POST /api/v1/patients/{patientId}/prescriptions
