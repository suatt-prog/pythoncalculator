from tkinter import *
root=Tk()
ana=Entry(root,width=15)
ana.grid(row=5,columnspan=3)
root.title("TYPEREX")
def tikla(asd):
    global yt
    yt=str(ana.get())
    ana.delete(0,END)
    ana.insert(0,yt+str(asd))
def topla():
    global sayi
    sayi=int(ana.get())
    ana.delete(0,END)
def esit():
    global sayi2
    sayi2=int(ana.get())
    ana.delete(0,END)
    if b==1:
       ana.insert(0,sayi+sayi2)
    if b==2:
       ana.insert(0,sayi-sayi2)
    if b==3:
       ana.insert(0,sayi*sayi2)
    if b==4:
       if sayi2==0:
          ana.insert(0,0)
       else:
          ana.insert(0,sayi/sayi2)
def topla():
    global sayi
    sayi=int(ana.get())
    ana.delete(0,END)
    global b
    b=1
def cikar():
    global sayi
    sayi=int(ana.get())
    ana.delete(0,END)
    global b
    b=2
def carp():
    global sayi
    sayi=int(ana.get())
    ana.delete(0,END)
    global b
    b=3
def bol():
    global sayi
    sayi=int(ana.get())
    ana.delete(0,END)
    global b
    b=4
but1=Button(root,text=1,command=lambda:tikla(1),padx=40,pady=40).grid(row=0,column=0)
but2=Button(root,text=2,command=lambda:tikla(2),padx=40,pady=40).grid(row=0,column=1)
but3=Button(root,text=3,command=lambda:tikla(3),padx=40,pady=40).grid(row=0,column=2)
but4=Button(root,text=4,command=lambda:tikla(4),padx=40,pady=40).grid(row=1,column=0)
but5=Button(root,text=5,command=lambda:tikla(5),padx=40,pady=40).grid(row=1,column=1)
but6=Button(root,text=6,command=lambda:tikla(6),padx=40,pady=40).grid(row=1,column=2)
but7=Button(root,text=7,command=lambda:tikla(7),padx=40,pady=40).grid(row=2,column=0)
but8=Button(root,text=8,command=lambda:tikla(8),padx=40,pady=40).grid(row=2,column=1)
but9=Button(root,text=9,command=lambda:tikla(9),padx=40,pady=40).grid(row=2,column=2)
but0=Button(root,text=0,command=lambda:tikla(0),padx=40,pady=40).grid(row=3,column=0)
butarti=Button(root,text='+',command=topla,padx=40,pady=40).grid(row=3,column=1)
butesit=Button(root,text='=',command=esit,padx=40,pady=40).grid(row=3,column=2)
buteksi=Button(root,text='-',command=cikar,padx=40,pady=40).grid(row=4,column=0)
butcarp=Button(root,text='*',command=carp,padx=40,pady=40).grid(row=4,column=1)
butbol=Button(root,text='/',command=bol,padx=40,pady=40).grid(row=4,column=2)
root.mainloop()
