# 🧪 HW: Group Words by Character Signature

## 🎯 วัตถุประสงค์:

ให้นักศึกษาสร้างฟังก์ชันสำหรับจัดกลุ่มคำภาษาอังกฤษตาม “ลักษณะของตัวอักษรที่ประกอบอยู่ในคำ” โดยคำที่อยู่ในกลุ่มเดียวกันจะต้องประกอบด้วย **ตัวอักษรชุดเดียวกันทุกตัว** ไม่สนลำดับ

---

## 🧾 ข้อกำหนดชื่อฟังก์ชัน:

```python
def group_by_signature(words: list) -> list:
    pass

if __name__ == "__main__":
    # Example 1
    words = ["abc", "bca", "cab", "bac", "xyz", "yxz", "zxy", "dog"]
    print(group_by_signature(words))
    # Output: [["abc", "bca", "cab", "bac"], ["xyz", "yxz", "zxy"], ["dog"]]

    # Example 2
    words = ["apple", "pale", "leap", "plea", "papel", "hello"]
    print(group_by_signature(words))
    # Output: [["apple", "papel"], ["pale", "leap", "plea"], ["hello"]]
```


---

## 📘 คำอธิบายโจทย์:

เขียนฟังก์ชันที่รับลิสต์ของคำ และจัดกลุ่มคำที่ประกอบด้วยชุดตัวอักษรเดียวกันให้อยู่กลุ่มเดียวกัน เช่น:

- `"abc"`, `"cab"`, `"bca"` → กลุ่มเดียวกัน
- `"ab"`, `"ba"` → กลุ่มเดียวกัน
- `"abc"` กับ `"abd"` → คนละกลุ่ม

---

## 🧪 คำสั่ง Run:

```bash
python GroupBySignature.py
```

## 🧪 คำสั่ง Test:

```bash
python -m unittest test_GroupBySignature.py
```

---


## 📌 หมายเหตุ:

- ให้ข้ามคำที่ว่างหรือมีอักขระนอกเหนือจาก a-z หากต้องการตรวจสอบเพิ่มเติม
- ใช้เวลาประมวลผลและหน่วยความจำอย่างมีประสิทธิภาพ
- สามารถใช้ Python มาตรฐาน ไม่ต้องใช้ไลบรารีภายนอก

---
