import tkinter as tk

def add_student():
    name = name_entry.get()
    age = age_entry.get()
    grade = grade_entry.get()
    # You can store this data or perform actions with it, like adding to a database
    # For now, let's just display the student's information
    info_text.insert(tk.END, f"Name: {name}, Age: {age}, Grade: {grade}\n")
    # Clear entry fields after adding
    name_entry.delete(0, tk.END)
    age_entry.delete(0, tk.END)
    grade_entry.delete(0, tk.END)

# Create the main window
root = tk.Tk()
root.title("Student Management System")

# Labels
name_label = tk.Label(root, text="Name:")
name_label.grid(row=0, column=0)

age_label = tk.Label(root, text="Age:")
age_label.grid(row=1, column=0)

grade_label = tk.Label(root, text="Grade:")
grade_label.grid(row=2, column=0)

# Entry fields
name_entry = tk.Entry(root)
name_entry.grid(row=0, column=1)

age_entry = tk.Entry(root)
age_entry.grid(row=1, column=1)

grade_entry = tk.Entry(root)
grade_entry.grid(row=2, column=1)

# Add student button
add_button = tk.Button(root, text="Add Student", command=add_student)
add_button.grid(row=3, columnspan=2)

# Display area for student information
info_text = tk.Text(root, height=10, width=30)
info_text.grid(row=4, columnspan=2)

# Start the GUI event loop
root.mainloop()
