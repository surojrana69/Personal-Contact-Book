contacts = {}

def show_menu():
    print("\nMenu:")
    print("1. Add a contact")
    print("2. View contacts")
    print("3. Remove a contact")
    print("4. Exit")

def add_contact():
    name = input("Enter the contact's name: ")
    phone = input("Enter the contact's phone number: ")
    contacts[name] = phone
    print(f'Contact "{name}" added!')

def view_contacts():
    if contacts:
        print("\nContacts:")
        for name, phone in contacts.items():
            print(f"Name: {name}, Phone: {phone}")
    else:
        print("No contacts found.")

def remove_contact():
    name = input("Enter the contact's name to remove: ")
    if name in contacts:
        del contacts[name]
        print(f'Contact "{name}" removed!')
    else:
        print("Contact not found!")

while True:
    show_menu()
    choice = input("Choose an option: ")

    if choice == "1":
        add_contact()
    elif choice == "2":
        view_contacts()
    elif choice == "3":
        remove_contact()
    elif choice == "4":
        print("Exiting the application. Goodbye!")
        break
    else:
        print("Invalid choice. Please try again.")
