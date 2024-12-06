CREATE TABLE products (
    product_id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    description TEXT,
    price DECIMAL(10, 2) NOT NULL,
    stock INT NOT NULL
);

#include <iostream>
#include <string>
// ... Include MySQL Connector/C++ headers here ...
// #include <mysql.h> // Example - replace with actual headers

using namespace std;

int main() {
    //  MySQL connection setup ... Replace with your connection details
    // MYSQL* mysql = mysql_init(NULL);
    // if (!mysql_real_connect(mysql, "localhost", "your_user", "your_password", "your_database", 0, NULL, 0)) {
    //     cerr << "Failed to connect to MySQL: " << mysql_error(mysql) << endl;
    //     return 1;
    // }


    // Add a new product
    //string sql_add = "INSERT INTO products (name, description, price, stock) VALUES ('New Product', 'This is a new product', 19.99, 100);";
    // if (mysql_query(mysql, sql_add.c_str())) {
    //     cerr << "Error adding product: " << mysql_error(mysql) << endl;
    // }


    // Fetch all products
    // string sql_select = "SELECT * FROM products;";
    // if (mysql_query(mysql, sql_select.c_str())) {
    //     cerr << "Error fetching products: " << mysql_error(mysql) << endl;
    // } else {
    //     MYSQL_RES* result = mysql_store_result(mysql);
    //     if (result) {
    //         MYSQL_ROW row;
    //         while ((row = mysql_fetch_row(result))) {
    //             cout << "ID: " << row[0] << ", Name: " << row[1] << ", Price: " << row[2] << endl;
    //         }
    //         mysql_free_result(result);
    //     }
    // }

    // ... MySQL connection cleanup ...
    // mysql_close(mysql);

    return 0;
}
