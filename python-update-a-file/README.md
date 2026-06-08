## Update a file through a Python algorithm

### Overview
This activity shows a Python algorithm which is designed to manage and update the network allow list. The algorithm removes unauthorized IP addresses listed in a "remove_list" from an allow list stored in a file named "allow_list.txt," ensuring secure access to restricted resources.

---

### Process
- Open and read allow_list.txt.
- Convert file contents into a string and then into a list.
- Iterate through IP addresses in remove_list.
- Remove any matching IP addresses from the allow list.
- Convert the updated list back into a string.
- Write the updated allow list back to the file.

---

### Python Implemented Concept
- File handling: open() and with statement.
- File modes: "r" and "w".
- String methods: .read(), .join().
- List methods: .split(), .remove().
- Loops: for loop.
- Conditional statements: if.

---

### Achieved Outcome
The final product is an updated allow list that excludes all unauthorized IP addresses, improving access control and security for restricted systems.
