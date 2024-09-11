from tkinter import*
import time
window=Tk()
window.title("Digital Clock")
window.config(bg="black")
def update():
    display_time=time.strftime("%I:%M:%S %p")
    display_date=time.strftime(" %d/%m/%Y,%A")
    label.config(text=display_time)
    label1.config(text=display_date)
    label.after(1000,update)
    
label=Label(window,font=("arial",80),bg="black",fg="white")
label.pack()
label1=Label(window,font=("arial",40),bg="black",fg="white")
label1.pack()
update()
window.mainloop()
