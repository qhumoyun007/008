# 008
#1
# savol="parolni kiriting:"
# savol +=("to'g'ri kiriting")
# parol=""
# login=""
# while parol != "333183801qhb" or login != "qhumoyun007":
#     parol=input("parol kiriting:")
#     login=input("login kiriting:")
#     if parol == "333183801qhb" and login == "qhumoyun007":
#         print("muvaffaqiyatli kirdingiz")
#2
# savol="yoshingizni kiriting:"
# savol +="(yoshingiz '18'dan kattami?)"
# ishora=True
# while ishora:
#     yosh=input("yoshingizni kiriting:")
#     if yosh<str(18):
#         ishora=False
#         print("yoshingiz kichik")
#     else:
#         print("marhamat kiring!!!")
#3
# i=0
# while i<10:
#     parol=input("parolni kiriting:")
#     if parol=="333183801qhb":
#         print("marhamat kiring!!!")
#         break
#     i+=1
#     if parol=="exit":
#         i+=11
#4
# for i in range(10):
#     parol=input("parolni kiriting:")
#     if parol=="333183801qhb":
#         print("marhamat kiring!!!")
#         break
#     if parol=="exit":
#         break
#5
# n=int(input("raqamni kiriting:"))
# s=0
# while n>0:
#      if n%10==2:
#          n=n//10
#          continue
#      else:
#          s+=n%10
#          n//=10
# print(s)
#6
# # kalkulator
# while True:
#     a=input()
#     if a!="=":
#         b=input()
#         if b=="+":
#             if b!="=":
#                 c=float(input())
#                 print(float(a)+c)
#             else:
#                 break
#         elif b=="-":
#             if b!="=":
#                 c=float(input())
#                 print(float(a)-c)
#             else:
#                 break
#         elif b=="*":
#             if b!="=":
#                 c=float(input())
#                 print(float(a)*c)
#             else:
#                 break
#         elif b=="/":
#             if b!="=":
#                 c=float(input())
#                 if c!="0":
#                     print(float(a)/c)
#                 else:
#                     print("maxraj nolga teng bo'la olmaydi")
#             else:
#                 break
#     else:
#         break
s=0
while True:
    a=input()
    b=input()
    if b=="+":
        c=input()
        s=float(a)+float(c)
    elif b=="-":
        c=input()
        s=s-float(c)
    elif b=="*":
        c=input()
        s=s*float(c)
    elif a=="/":
        c=input()
        if c!=0:
           s=s/float(c)
        else:
            print("maxraj nol bo'la olmaydi")
    elif b=="=":
        print(s)
    elif a=="=":
        print(s)
    elif c=="=":
        print(s)
