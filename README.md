# 271401 AI mini lab
# How to use

# Calibrate (HSV Color & distortion Tuner)
สามารถใช้ slider ปรับค่าสี(HSV) , ค่า distortion , kernel ของ Morphological Operation ได้

บันทึกค่าที่ปรับ ไว้ในไฟล์ hsv_config.json

โปรแกรมจะ return ตำแหน่งของแต่ละสีใน camera frame ออกมา

# Main (Vision and Control)
อ่านภาพจากกล้อง และปรับตามไฟล์ที่จูนมา

มี slider ให้เลือกสีที่จะตรวจจับ

แปลงพิกัดจาก cameara frame เป็นพิกัดใน real-world frame

ส่งข้อมูลให้แขนกล

