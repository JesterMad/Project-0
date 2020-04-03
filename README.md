# Project-0
Python Learning

"""
This is the version of learning Git and Python coding
Official named by Wojciech Bendza
All right reserved.
"""

from tkinter import *
import tkinter
import tkinter.messagebox
def proces():
    numer1=Entry.get(E1)
    numer2=Entry.get(E2)
    Operacja=Entry.get(E3)
    numer1=int (numer1)
    numer2=int (numer2)
    if Operacja =="+":
        answer=numer1+numer2
    if Operacja == "-":
        answer=numer1-numer2
    if Operacja == "*":
        answer=numer1*numer2
    if Operacja =="/":
        answer=numer1/numer2
    Entry.insert(E4, 0,answer)
    print(answer)
top = tkinter.Tk()
