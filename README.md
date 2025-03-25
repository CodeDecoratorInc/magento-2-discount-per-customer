# Magento 2 Discount Per Customer Extension

## Introduction
Magento 2 Discount Per Customer extension allows store owners to set personalized discounts for specific customers or customer groups. This extension enhances customer retention by providing targeted pricing strategies based on purchase behavior. Increase customer loyalty and encourage repeat purchases with dynamic discount rules tailored to individual users.

## How It Works – Magento 2 Discount Per Customer
Magento 2 Discount Per Customer works by enabling merchants to assign unique discount rates to specific customers or groups. The extension integrates seamlessly into the Magento pricing structure, allowing discounts to be applied automatically at checkout. Admins can configure discounts based on fixed amounts or percentage values while ensuring flexibility and ease of management.

## Key Features
- **Custom Discounts for Customers** – Assign personalized discount rules for individual customers or customer groups.
- **Flexible Discount Types** – Offer fixed amount or percentage-based discounts to suit various pricing strategies.
- **Automatic Discount Application** – Discounts are applied automatically during checkout, ensuring a smooth user experience.
- **Admin-Friendly Configuration** – Easily manage discount rules from the Magento admin panel.

## Personalized Discount Rules
Merchants can set custom discount rules per customer, ensuring special offers are applied to loyal or high-value customers.

## Seamless Checkout Experience
The extension ensures that discounts are applied automatically without requiring customers to enter coupon codes.

## Multi-Store Compatibility
Supports multiple store views and currency configurations, making it suitable for global eCommerce operations.

## Boosts Customer Retention
Encourages repeat purchases by rewarding loyal customers with exclusive discounts.

## Extension Installation
To install the Magento 2 Discount Per Customer extension, use Composer, a powerful dependency management tool for Magento 2.

### Step 1: Install the extension using Composer:
```bash
composer require codedecorator/magento2-discount-per-customer
```
For a specific version:
```bash
composer require codedecorator/magento2-discount-per-customer:<version>
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run Magento Setup Commands
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 Discount Per Customer
Follow these steps to configure the Magento 2 Discount Per Customer extension in your store.

**1.​ Enable Extension**

once after successfully install our extension, you will need to enable the
extension from Magento 2 admin. The following steps will guide you for the same.

●​ Login to Magento2 admin.

●​ Click on the Codedecorator Extension menu

![image5](https://github.com/user-attachments/assets/bb0b4f04-e0f2-4da3-9c9e-dbfd14fb3333)

● Click on the Configuration
​ 
Clicking on configuration will redirect you to the customer discount setting
page where you can enable and disable the extension for the entire store.

![image4](https://github.com/user-attachments/assets/4efb6524-d957-4fdc-a0f1-b188d5bcee68)

**2.​ Global Configuration**

![image9](https://github.com/user-attachments/assets/56daa554-6f49-4539-b9b3-c197793bea9c)

**3.​ Assign Discounts to specific Customers**

You assign a percentage of discount for a specific customer by navigating
“Customers -> All customers” menu at the backend.
Edit the customer to whom you want to give the discount.

![image1](https://github.com/user-attachments/assets/83a6b230-fa3c-4309-b2cd-d70338da7e05)

**4.​ Frontend View**

It shows a popup for logged-in customer who has discounts assigned by admin.

![image3](https://github.com/user-attachments/assets/2705bfd6-95ba-4332-a243-707dacb2b3fe)

**5.​ Discount applied on Cart/Checkout**

A percentage discount will be applied once the customer adds the product to the
cart. It will display a discount label which is assigned by admin.
In the following screenshot, it is applying a 10% discount to logged customers.

![image16](https://github.com/user-attachments/assets/362eb4bb-efcb-4acf-a20d-5e5943611779)

![image6](https://github.com/user-attachments/assets/3d9140e8-2e39-4439-be45-42bab9e5f2ea)

**6.​ Discount is shown on the order page**
Discount information will shown in order of detail at the front end and back end.

![image14](https://github.com/user-attachments/assets/477908ed-8fd7-49f3-9eb6-7d26d158ccbd)

![image7](https://github.com/user-attachments/assets/35b882dd-d1fe-4e4c-873d-6f4c51bec4b1)

**User Guide Information:** While some screenshots in this guide may reflect older versions of the
interface, the core steps and fundamentals remain unchanged. If you encounter discrepancies
or need further clarification

## Download Our [Magento 2 Discount Per Customer](https://codedecorator.com/magento-2-discount-per-customer.html) Extension 
