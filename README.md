# 🌙 Iftar Party Entry Pass System

![C](https://img.shields.io/badge/Language-C-00599C?style=flat-square&logo=c&logoColor=white)
![Type](https://img.shields.io/badge/Type-CLI-lightgrey?style=flat-square)

An admin panel in C for managing entry passes to an Iftar party. The admin can register guests, print a nicely formatted pass, edit details or delete a pass.

I made this to practice **CRUD operations** (create, read, update, delete) on an array of structs, using a real-life scenario from Ramadan events.

---

## ✨ Features

- ➕ **Entry a pass**: name, phone number, email and payment method
- 💳 **Payment options**: bKash, Nagad, Rocket or Cash (a transaction ID is asked for mobile payments)
- 🖨️ **Print a pass** as a boxed ticket in the terminal, and save it as `<pass-id>.txt`
- ✏️ **Edit a pass**: update name, phone number or email
- 🗑️ **Delete a pass**
- 🆔 Every pass gets an auto-generated ID

## 🚀 Run it

```bash
gcc "Iftar Party Entry Pass System.c" -o iftar
./iftar
```

```text
=====Iftar Party Entry Pass: Admin Panel=====
  1. Entry a Pass.
  2. Print a Pass.
  3. Edit a Pass.
  4. Delete a Pass.
  0. Exit
```

## 🧠 What I practiced

- Designing a `struct` around real data
- Basic CRUD logic without a database
- Formatting console output with `printf` width specifiers

> 📝 The guest list itself lives in memory, so it resets when the program closes. Only printed passes are saved as files. Persisting the full list would be the next step.

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
