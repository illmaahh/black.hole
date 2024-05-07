import tkinter as tk
from tkinter import scrolledtext
import time

class BlackHoleInfo:
    def __init__(self, master):
        self.master = master
        master.title("Black Hole Information")

        self.canvas = tk.Canvas(master, width=400, height=400)
        self.canvas.pack()

        self.info_text = scrolledtext.ScrolledText(master, width=40, height=10)
        self.info_text.pack()

        self.create_black_hole()

    def create_black_hole(self):
        self.canvas.create_oval(150, 150, 250, 250, fill="black")
        self.info_text.insert(tk.END, "Black Hole\n\n")
        self.info_text.insert(tk.END, "A black hole is a region of spacetime where gravity is so strong that nothing—no particles or even electromagnetic radiation such as light—can escape from it.\n\n")
        self.info_text.insert(tk.END, "Some key points about black holes:\n")
        self.info_text.insert(tk.END, "- Black holes are formed when massive stars collapse under their own gravity.\n")
        self.info_text.insert(tk.END, "- Black holes have a boundary called the event horizon, beyond which nothing can escape.\n")
        self.info_text.insert(tk.END, "- Black holes come in different sizes, from small stellar-mass black holes to supermassive black holes found at the centers of galaxies.\n")
        self.info_text.insert(tk.END, "- Black holes can't be directly observed, but their presence can be inferred by observing the behavior of nearby objects.\n")
        self.info_text.insert(tk.END, "- Black holes can merge with other black holes, emitting gravitational waves in the process.\n")
        self.info_text.insert(tk.END, "- Black holes can evaporate over time due to a process called Hawking radiation, predicted by Stephen Hawking.\n")
        self.info_text.insert(tk.END, "\nExplore more about black holes to uncover the mysteries of the universe!")

def main():
    root = tk.Tk()
    app = BlackHoleInfo(root)
    root.mainloop()

if __name__ == "__main__":
    main()

