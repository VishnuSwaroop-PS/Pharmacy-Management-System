# Pharmacy Management System

This Pharmacy Management System is a simple console application written in C. It manages medicines and customers in a pharmacy, providing functionalities for purchasing medicines, viewing medicine details, checking stock, and updating medicine information. The application also supports data persistence by reading from and writing to a file.

## Features

1. **Purchase Medicine**: Customers can purchase medicines by providing either the medicine ID or name. The application generates an invoice with the total price and details of purchased medicines.
2. **Medicine Details**: View detailed information about medicines, including those about to expire.
3. **Stock of Medicine**: Check the current stock and identify out-of-stock medicines.
4. **Update Medicine**: Add new medicines, delete existing ones, and update details of existing medicines.
5. **Data Persistence**: Save and load medicine data to and from a file.

## Getting Started

### Prerequisites

- A C compiler (e.g., GCC)

### Running the Application

1. **Clone the repository**:
    ```sh
    git clone https://github.com/VishnuSwaroop-PS/Pharmacy-Management-System.git
    cd Pharmacy-Management-System
    ```

2. **Compile the program**:
    ```sh
    gcc -o pharmacy_management_system main.c
    ```

3. **Run the program**:
    ```sh
    ./pharmacy_management_system
    ```

## File Structure

- `main.c`: The main source code file containing the implementation of the pharmacy management system.

## Usage

Upon running the application, you will be presented with a menu of options:

1. Purchase Medicine
2. Medicine Details
3. Stock of Medicine in Store
4. Update Medicine
5. Write To Database

Follow the prompts to perform the desired operations.

### Purchase Medicine

Customers can purchase medicines by providing their details and selecting medicines by ID or name. The application will display the total price and an invoice of the purchase.

### Medicine Details

View detailed information about a specific medicine, including those about to expire.

### Stock of Medicine

Check the current stock of medicines and identify out-of-stock items.

### Update Medicine

Add new medicines, delete existing ones, or update details such as quantity, price, name, company, manufacturing date, expiry date, and additional information.

### Write To Database

Save the current state of the medicine data to a file.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes you would like to make.

1. Fork the repository
2. Create a new branch: `git checkout -b my-feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Submit a pull request

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or suggestions, feel free to contact me at vishnuswaroop20@gmail.com.

---

Thank you for using the Pharmacy Management System!
