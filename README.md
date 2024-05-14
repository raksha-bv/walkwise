# WalkWise


WalkWise, our shoe-selling website, seamlessly blends frontend excellence with Flask's backend flexibility. My role centered on implementing Flask to manage product data, orders, and user interactions, ensuring a smooth shopping experience. The frontend was carried by my teammate who curated a visually engaging interface using HTML, CSS, and JavaScript, with carefully chosen brand colors, fonts, and layouts to enhance user experience. Together, we created a cohesive and functional e-commerce platform aligned with WalkWise's style and customer-focused ethos.
The Website is live on  - https://walkwise.onrender.com/



## Features

1. *User Authentication*: Users can sign up, log in, and log out securely.
2. *Product Management*: Admins can add, edit, and delete products.
3. *Shopping Cart*: Users can add products to their cart and proceed to checkout.
4. *Image Upload*: Cloudinary is used to store uploaded images for products.
5. *Database Handling*: SQLAlchemy is used to manage the database, ensuring efficient data handling.



## Technologies Used

- *Frontend*: HTML, CSS, JavaScript, Bootstrap
- *Backend*: Flask
- *Database*: MYSQL
- *Image Storage*: Cloudinary
- *Libraries*: Flaticon (for icons), Bootstrap (for styling)



## Installation

1. Clone the repository:

   bash
   git clone https://github.com/raksha-bv/walkwise.git

2. Install dependencies
   
   bash
   pip install -r requirements.txt

3. Set up Cloudinary:

   Create a Cloudinary account at cloudinary.com

   Configure Your app.py
   
   app.py
   cloudinary.config( 
    cloud_name = "your cloud_name", 
    api_key = "your_api_key", 
    api_secret = "your_api_secret_key"
   )

4. Run the application

   bash
   python app.py

5. Access the application at http://localhost:5000
   
   Incase of errors make sure all the modules that need to be imported are already imported if not manually import them using pip install.



## Contributing

We welcome contributions to improve WalkWise. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-improvement).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature-improvement).
6. Create a new Pull Request.



## License

This project is licensed under the MIT License - see the LICENSE file for details.



## Contact

For any inquiries or suggestions regarding WalkWise, please contact https://www.linkedin.com/in/adityaanand-sahil/



### Credits
  Thanks To My Wonderful Teammate without whom this website wouldnt be possible:  
    Aditya Anand 
  https://www.linkedin.com/in/adityaanand-sahil/
 
 https://github.com/AdityaAnandCodes
