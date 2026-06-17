# Car-Seat-Covers

Ganesh Seat is an Android application developed for efficient car seat inventory and management. The app allows managing car brands, their models, and model-wise seat data with advanced filtering and bulk operations.

---

## 🚀 Features

### 🔹 Brand Management

* Add, edit, and delete car brands
* Each brand includes:

  * Brand name
  * Brand image
* Display list of all available brands

### 🔹 Model Management (Brand-wise)

* Add, edit, and delete models based on the selected brand
* Each model includes:

  * Model name
  * Model image
* Display models according to the selected brand

### 🔹 Seat Management (Model-wise)

* Display seats data in a **GridView** based on the selected model
* **Quality-based filtering** using TabLayout
* Additional availability filters:

  * Available seats
  * Out of Stock seats

### 🔹 Bulk Seat Operations

* Select multiple seats at once
* Perform bulk actions:

  * Share selected seat images
  * Delete selected seat data

### 🔹 Seat Detail Screen

* Zoom-in feature for detailed seat image viewing
* Manufacturer list displayed for each seat
* Individual seat actions:

  * Share seat details
  * Delete seat data

---

## 🛠 Tech Stack

* **Programming Language:** Kotlin
* **Architecture Pattern:** Clean Architecture with MVVM
* **Dependency Injection:** Dagger-Hilt
* **Networking:** Retrofit
* **Asynchronous Handling:** Kotlin Coroutines
* **State Management:** LiveData & ViewModel
* **Lifecycle Management:** Android Lifecycle-aware components

---

## 🧱 Architecture Overview

The project follows Clean Architecture principles for better scalability, testability, and maintainability:

### Data Layer

* API services using Retrofit
* DTOs and data models
* Repository implementations

### Domain Layer

* UseCases containing business logic
* Domain models

### Presentation Layer

* ViewModels
* UI components (Activities / Fragments)
* LiveData observers

---

 ## Project Images

<div style="display:flex; flex-wrap:wrap; gap:10px;">
<img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/brands.jpeg" width="240" height="500">
 <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/add_brand.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/models.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/add models.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/products.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/add_category.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/add_product_detail.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/out_stock.jpeg" width="240" height="500">
  <img src="https://raw.githubusercontent.com/rjmngr929/Car-Seat-Covers/main/product_detail.jpeg" width="240" height="500">
</div>

## Contact
For any help, contact: prajapat09rahul@gmail.com
