# Library-Management-System
This code is a part of a Python-based Library Management System project. It handles the main menu navigation by taking user input and performing different library operations based on the selected option.
choice = input("  Enter your choice (1-6): ").strip()

if choice == "1":
    display_all_books()

elif choice == "2":
    add_book()

elif choice == "3":
    issue_book()

elif choice == "4":
    return_book()

elif choice == "5":
    search_book()

elif choice == "6":
    print("\n  Thank you for using Library Management System. Goodbye!\n")
    break

else:
    print("\n  Invalid choice. Please select between 1 and 6.")
