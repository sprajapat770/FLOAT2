# Float – A Modular PIM & E-Commerce Framework

## Overview

Float is a **modular Product Information Management (PIM) system** designed for businesses to efficiently manage  **products, categories, customers, and orders** . It offers a **scalable, flexible, and extensible** solution where functionalities can be installed or removed based on user needs, ensuring minimal conflicts between modules.

## Key Features

* **Modular Architecture** – Each core functionality (products, categories, orders) is a separate module.
* **Seamless Integration** – Storefront can be installed separately based on business requirements.
* **Customizable Attributes** – Provides only essential attributes; users can create custom attributes.
* **Admin & Storefront Separation** – Admin panel handles data management; the storefront module is optional.
* **Scalability & Extensibility** – Allows easy enhancements through additional modules.
* **SEO & Enhancements** – Additional modules like `module-seo` integrate into products/categories.

## How It Works

1. **Core System** – Provides the base framework, including the admin panel.
2. **Modules** – Products, Categories, Customers, Orders, and other extensions are independent modules.
3. **Storefront (Optional)** – Businesses can install a storefront module to display their products.
4. **Flexible UI** – Storefront UI components are separately installable.
5. **Dynamic Installation** – Modules can be installed, updated, or removed without affecting the core.

## Initial Development Focus

* **Admin Panel & Core Framework Development**
* **Dynamic Module Installation & Management**
* **Database Schema & Models Definition**

## Installation

```sh
# Clone the repository
git clone https://github.com/your-repo/float.git
cd float

# Install dependencies
yarn install

# Setup environment variables
cp .env.example .env

# Run the development server
yarn dev
```

## Future Enhancements

* Advanced Reporting & Analytics
* API-based External Integrations
* Multi-language & Multi-currency Support
* AI-powered Product Recommendations

---

🚀 **Float is built for scalability.** Whether you need a simple PIM or a full-fledged e-commerce system, it adapts to your needs.
