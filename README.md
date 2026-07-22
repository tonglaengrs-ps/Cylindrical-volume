import math

print("===== โปรแกรมคำนวณปริมาตรทรงกระบอก =====")

# รับค่าจากผู้ใช้
radius = float(input("กรอกรัศมี (cm): "))
height = float(input("กรอกความสูง (cm): "))

# คำนวณปริมาตร
volume = math.pi * radius**2 * height

# แสดงผล
print("\n========== ผลการคำนวณ ==========")
print(f"รัศมี = {radius:.2f} cm")
print(f"ความสูง = {height:.2f} cm")
print(f"ปริมาตร = {volume:.2f} cm³")
print("================================")
