# เป้าหมาย: สร้างฟังก์ชัน Python เพื่อคำนวณพื้นที่สี่เหลี่ยมผืนผ้า

def calculate_rectangle_area(length, width):
    """
    คำนวณพื้นที่ของสี่เหลี่ยมผืนผ้า

    พารามิเตอร์:
    length (int/float): ความยาวของสี่เหลี่ยมผืนผ้า
    width (int/float): ความกว้างของสี่เหลี่ยมผืนผ้า

    ส่งคืน:
    (int/float): พื้นที่ของสี่เหลี่ยมผืนผ้า
    """
    area = length * width
    return area

# วิธีใช้งาน:
area_result = calculate_rectangle_area(10, 5)
print(f"พื้นที่คือ: {area_result}") # ผลลัพธ์: พื้นที่คือ: 50
