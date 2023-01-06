import tkinter as tk

# Create the main window

window = tk.Tk()

# Create a button

button = tk.Button(window, text="Welcome to India", width=25, bg="saffron", command=lambda: print("Button clicked!"))

# Center the button

button.pack(side="center", padx=5, pady=5)

# Run the Tkinter event loop

window.mainloop()
