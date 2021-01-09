<h1 align="center">Simple Commerce - Backend - RS09</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 
This is an Back-End application that allow the creation of customers, products and orders, where the customer can generate new purchase orders for certain products, much like a small e-commerce.
  </p>

---

## 📝 Table of Contents

- [Application Routes](#routes)
- [Business Rules](#rules)
- [Author](#authors)
- [Acknowledgments](#acknowledgement)

---

## 🧐 Application Routes <a name = "routes"></a>

- **_POST /customers_**

- **_POST /products_**

- **_POST /orders/_**

## 💼 Business Rules <a name = "rules"></a>

1. should be able to create a new customer
1. should not be able to create a customer with one e-mail thats already registered
1. should be able to create a new product
1. should not be able to create a duplicated product
1. should be able to create a new order
1. should not be able to create an order with a invalid customer
1. should not be able to create an order with invalid products
1. should not be able to create an order with products with insufficient quantities
1. should be able to subtract an product total quantity when it is ordered
1. should be able to list one specific order

## ✍️ Author <a name = "authors"></a>

- [@devfel](https://github.com/devfel) - Luiz Flávio Felizardo

---

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Challenge proposed by Rocket Seat within the gostack 14 bootcamp.
