# kashier-openCart-plugin

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/opencart-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service for merchant operating in Egypt.

- IFrame Integration.

- 3D secure cards authentication support.

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Support multiple payment method.

      1. Card Payments
      2. Wallet Payments
      3. Bank Installments Payment

- Plug and play.

- Customize order state after success payment.

### Installation

- Download kashier.ocmod.zip https://github.com//Kashier-payments/kashier-openCart-plugin/raw/main/kashier.ocmod.zip
- Log into **OpenCart Webstore Admin**.
- Navigate to the **Admin Panel > Extensions > Extension installer**.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/Opencart_ex_installer_v3.png)

- Click the **Upload** button, then select the downloaded **zip** file (Step 1), then click the **Continue** button and wait for the process to complete.
- Navigate to **Extensions > Extensions**.
- On the Extensions page, select **Payments** from the dropdown and install the **Kashier Payment Method** extension you want to install.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/opencart_extn.png)

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/open_cart_kashier.png)

- After installation, proceed for configuration.

### Configuration

- Log into **OpenCart Webstore Admin**.
- Navigate to **Extensions** and then select **Extensions**.
- On the **Extensions** page, select **Payments** from the dropdown and then install the **Kashier Payment Method** extension extension you want to enable.
- Save the configuration below.
  ![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/open_Cart_configuration.png)
  1.  **Merchant ID** - Enter your Merchant ID provided by kashier
  2.  **Test Mode** test mode for testing and development
  3.  **Test Api Key** - Enter your Merchant test Api Key provided by kashier
  4.  **Live Api Key** - Enter your Merchant live Api Key provided by kashier
  5.  **Test secret Key** - Enter your Merchant test Secret Key provided by kashier
  6.  **Live secret Key** - Enter your Merchant live Secret Key provided by kashier
  7.  **Order Success Status** - Order status that will set for Successful Payment
  8.  **Order Failed Status** - Order status that will set for Failed Payment
  9.  **Order Pending Status** - Order status that will set for Panding Payment
  10. **Status** - Keep this Enabled to accept payment through kashier
  11. **Sort Order** - Set ordering in the payment methods list

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/
- Navigate to Integrate now section > payment api keys.
- Generate a new api key with your prefered name that describes your integration channel, there is a default api key you could use that is created when signing up.
  ![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/apikey_mid_test.png)
- Copy Merchant ID visible under your user name "MID-xx-xx".
- Insert the MID and Test Api Key in the Configuration page of the module.
- Make sure the test mode is on.
- set order status that will set for Successful, Failed, and Pending Payment.
- Make sure the status is on to accept payment through kashier
- Save configuration.
  ![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/configuration-test.png)

### Go live

- After activating your account.
- Make sure you are on live mode.
- Navigate to Integrate now section > payment api keys
- Generate a new api key with your prefered name that describes your integration channel, there is 3 default api key you could use that is created when signing up.
  ![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/apikey_mid_live.png)
- Insert Live Api Key in the Configuration page of the module.
- Remove the test mode check.
- Save configuration.
  ![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/configuration_live.png)

### Your kashier Payment Gateway is enabled. Now you can accept payment through kashier.

### Support

- Leave us an inquiry ticket on support@kashier.io for questions.
