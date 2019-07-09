from tkinter import *

win = Tk()
win.geometry("600x600")
win.title("Jitter Click | Test Yourself")
win.wm_iconbitmap("icon.ico")
a = 1
def jitter():
    global a
    jitterb["text"] = a
    a += 1

jitterb = Button(win, text= "Click\n{}", bd = 0, bg = "Black", fg = "White", font = ("Arial",20,"bold"),
                 activebackground= "#111111", activeforeground = "White", width = 120, height = 100, command = jitter)
jitterb.pack()
win.mainloop()
