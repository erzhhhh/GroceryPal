# GroceryList 🛒🥦

GroceryList is a simple Android app to manage your shopping list. Track items, add new products, and check off what you need — all with a clean UI and smooth interactions.

---

## What it does 📝

* Add, edit, and remove grocery items 🛒
* Check items off your list ✅
* View details for each product 📋
* Persist your list locally with Room 🏠
* Handles UI updates and errors gracefully ⚡

Perfect for practicing Android development and using common architecture patterns like MVVM 😄

---

## Features 🌟

* Create and manage a grocery list 🥦🍎
* Item details screen 📝
* Check/uncheck items ✔️❌
* Local persistence with Room 🏠
* Clean MVVM architecture 🏗️

---

## Tech stack 🛠️

* **Kotlin / Java**
* **Android SDK** 🤖
* **MVVM architecture** 🏗️
* **RecyclerView** for lists 📜
* **ViewModel + LiveData** 🔄
* **Room** for local database 🏠
* **Dagger 2** for dependency injection ⚙️
* **RxJava** for reactive streams ⚡
* **Retrofit / OkHttp** (if network features are added) 🌐
* Gradle build system ⚙️

---

## Getting started 🚀

1. Clone the repo:

   ```bash
   git clone https://github.com/erzhhhh/GroceryList.git
   cd GroceryList
   ```
2. Open in Android Studio 🏗️
3. Sync Gradle and build the project 🔄
4. Run on a device or emulator 📱

> All data is stored locally — no API keys required! 🏠

---

## Project structure 🗂️

```
app/
 ├─ data/        # Room entities & DAO 🏠
 ├─ ui/          # Activities/Fragments for list & detail screens 🖥️
 ├─ viewmodel/   # ViewModels managing UI & data 🔄
 └─ di/          # Dagger setup ⚙️
```

---

## Fun ideas to make it even cooler 🎉

* Add categories for grocery items 🥩🥦
* Dark mode 🌙🖤
* Notifications/reminders for shopping 🛎️
* Sync data to cloud / Firebase ☁️
* Share your grocery list with friends 📱💬

---

Screenshots
-----------

![Start](screenshots/login.png "Login page")
![List of products](screenshots/productsList.png "List of products")
![Choosing products](screenshots/productsChoose.png "Choosing products")
![Create an order](screenshots/productsChoose.png "Create an order")
![Name the order](screenshots/nameTheOrder.png "Name the order")
![List of orders](screenshots/ordersList.png "List of orders")
![Order details](screenshots/orderDetails.png "Detailed information about the order")
![List of products_dark](screenshots/productsListDark.png "List of products with dark mode")
![Order details_dark](screenshots/orderDetailsDark.png "Detailed information about the order with dark mode")
