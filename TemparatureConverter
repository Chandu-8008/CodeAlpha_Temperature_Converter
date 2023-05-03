from tkinter import *
win=Tk()
win.geometry('300x400')
win.title("welcome")
l1=Label(win,text='value:')
l2=Label(win,text='result')
t1=Entry(win,width=30)
t2=Entry(win,width=30)
l1.grid(row=0,column=0,pady=10,padx=5)
l2.grid(row=1,column=0,pady=10,padx=5)
t1.grid(row=0,column=1)
t2.grid(row=1,column=1)
def ktof():
   a=float( t1.get())
   b=1.8*(a-273)+32
   
   t2.insert(END,b)
def ktoc():
    a=float( t1.get())
    b=a-273.15
    
    t2.insert(END,b)
def ktor():
    a=float(t1.get())
    b=a*1.8
    t2.insert(END,b)
def ctok():
    a=float(t1.get())
    b=a+273.15
    t2.insert(END,b)
def ctof():
    a=float(t1.get())
    b=(a*9/5)+32.4
    t2.insert(END,b)
def ctor():
    a=float(t1.get())
    b=(a+273.15)*1.8
    t2.insert(END,b)
def ftok():
    a=float(t1.get())
    b=(a-32)/1.8+273.15
    t2.insert(END,b)
def ftoc():
    a=float(t1.get())
    b=(a-32)*5/9
    t2.insert(END,b)
def ftor():
    a=float(t1.get())
    b=a+459.67
    t2.insert(END,b)
def rtok():
    a=float(t1.get())
    b=a/1.8
    t2.insert(END,b)

def rtof():
    a=float(t1.get())
    b=a-459.67
    t2.insert(END,b)

def rtoc():
    a=float(t1.get())
    b=(a-491.67)/1.8
    t2.insert(END,b)







def cls():
    t1.delete(0,END)
    t2.delete(0,END)

    
def  ext():
    pass
win.protocol('WM_DELETE_WINDOW',ext)
    
    
    
btn1=Button(win,text='kelvin to fahrenheit',command=ktof)
btn1.grid(row=5,column=1)
btn2=Button(win,text='kelvin to celsius',command=ktoc)
btn2.grid(row=5,column=2)
btn3=Button(win,text='kelvin to rankine',command=ktor)
btn3.grid(row=5,column=3)
btn4=Button(win,text='celsius to kelvin',command=ctok)
btn4.grid(row=5,column=4)
btn5=Button(win,text='celsius to fahrenheit',command=ctof)
btn5.grid(row=5,column=5)
btn6=Button(win,text='celsius to rankine',command=ctor)
btn6.grid(row=5,column=6)
btn7=Button(win,text='fahrenheit to kelvin',command=ftok)
btn7.grid(row=5,column=7)
btn8=Button(win,text='fahrenheit to celsius',command=ftoc)
btn8.grid(row=8,column=3)
btn9=Button(win,text='fahrenheit to rankine',command=ftor)
btn9.grid(row=8,column=4)
btn10=Button(win,text='rankine to kelvin',command=rtok)
btn10.grid(row=8,column=5)
btn11=Button(win,text='rankine to fahrenheit',command=rtof)
btn11.grid(row=8,column=6)
btn12=Button(win,text='rankine to celsius',command=rtoc)
btn12.grid(row=8,column=7)
clr=Button(win,text="clearscreen",command=cls)
clr.grid(row=1,column=3)
close=Button(win,text='close',command=win.destroy)
close.grid(row=12,column=4)
ext1=Button(win,text='destroy',command=ext)
ext1.grid(row=13,column=0)
win.mainloop()
