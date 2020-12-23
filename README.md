# นี่คือตัวอย่างโปรแกรมสำหรับการเรียน    OOP
### วิธีติดตั้ง

เปิด CMD / Terminal

```python
pip install angryduckschool
```

### วิธีเล่น

เปิด IDLE ขึ้นมาแล้วพิมพ์...

```python
from angryschool import Student, SpecialStudent

print('========1 Jan========')
student0 = SpecialStudent('Mark Zuckerberg','Bill Gates')
student0.AskEXP()
student0.ShowEXP()
student1 = Student('Albert')
print(student1.name)
student1.Hello()

print('------------')
student2 = Student('Steve')
print(student2.name)
student2.Hello()
print('========2 Jan========')
print('------uncle: ใครอยากเรียนโค้ดดิ้ง?---(ให้ 10 exp)----')
student1.AddEXP(10)

print('========3 Jan========')
student1.name = 'Albert Einstein'
print('ตอนนี้ exp ของแต่ละคนได้เท่าไรกันแล้ว')

print(student1.name, student1.exp)
print(student2.name, student2.exp)
print('========4 Jan========')

for i in range(5):
	student2.Coding()

student1.ShowEXP()
student2.ShowEXP()
```



พัฒนาโดย: Angryduck888
FB: N/A
YouTube: N/A