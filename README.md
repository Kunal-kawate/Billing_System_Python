# Billing Software

A billing software application built with Streamlit for managing customer details, product selection, and billing operations seamlessly. This application provides an easy-to-use interface to add customer information, select products, and generate detailed bills with PDF download and print options.

## Features

- **Customer Management**: Enter customer name and mobile number.
- **Product Selection**: Choose from predefined categories and subcategories.
- **Cart Functionality**: Add items to the cart with specified quantities and prices.
- **Billing and PDF Generation**: Calculate total, generate a detailed bill in PDF format, download, and print the bill.
- **Reset and Save**: Easily reset fields and cart items for new transactions.

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Used for GUI and web interface.
- **FPDF**: Generates and saves bills as PDF files.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Kunal-kawate/Billing_System_Python.git
    cd billing-software
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application**:
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Enter Customer Details**: Fill in the customer name and mobile number.
2. **Select Products**:
    - Choose a category (e.g., Category01, Category02).
    - Select a subcategory based on the category chosen.
    - Enter quantity and price.
3. **Add to Cart**: Click "Add to Cart" to add products to the bill.
4. **Generate Bill**: Click "Generate Bill" to download the bill as a PDF and automatically open the print dialog.
5. **Reset**: Click "Reset" to clear the form and cart for a new transaction.

## Project Structure

```plaintext
.
├── app.py               # Main application file
├── requirements.txt     # Required libraries for the project
├── README.md            # Project documentation
```

## Contributing

Feel free to submit issues or pull requests for improvement.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
