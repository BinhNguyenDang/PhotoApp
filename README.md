# photoApp
- This app(photoApp) Build with RubyOnRails & Bootstrap
- Use Devise for authentication
- Use Stripe API for accept payment
- In this app main functionality is integrate of payment API, account confirmation and password reset.

# Getting Started
To get started with this project, follow these instructions:

# Prerequisites
Make sure you have the following installed on your system:

- Ruby (version 3.3.0)
- Rails (version 7.1.3 or higher)
- SQLite3 (version 1.4)
- Puma (version 5.0 or higher)

# Installation
1. Clone the repository to your local machine:
   ```
   git clone <repository_url>
   ```
2. Install the project dependencies using Bundler:
   ```
   bundle install
   ```
3. Set up the database:
   ```
   rails db:migrate
   ```
4. Edit Stripe credentials ( developer mode for test ):
   ```
   EDITOR="code --wait" rails credentials:edit
   ```
   and edit the credentials.yaml file
   ```
   stripe:
    publishable_key: <your_publishable_key>
    secret_key: <your_secret_key>
   ```
# Running the Application
Start the Rails server:
```
rails server
```
You can now access the application at http://localhost:3000.
# Features
- Devise: User authentication
- Twitter Bootstrap: Frontend framework for styling
- CarrierWave: Image uploader gem
- MiniMagick: Image resizing gem
- Stripe: Payment processing integration
- Stimulus-Rails: Modest JavaScript framework
- Importmap-Rails: JavaScript with ESM import maps
- JBuilder: Building JSON APIs
# Demo 

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/e70c2216-bc83-4808-b821-1ec2e5fae28e)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/73cfd115-6fb6-4377-9302-eb9bd5db56e5)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/887ed230-b2f1-4bb4-ae7d-456977e2bd76)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/484b4361-a756-4b47-af3b-2ac70bbbe895)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/c110c2e7-5c82-4c92-9aac-22687cb09622)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/2bc72703-ed21-4ee3-ba6f-58719d9ffbdd)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/2c3a2163-43b7-496e-86c9-97a47f65f2e2)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/ff9a6dbe-f910-49c2-9bb3-920e5154d7a2)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/9743444e-133c-4ad7-aa7a-318a236a9312)

![image](https://github.com/BinhNguyenDang/PhotoApp/assets/146049423/e09cfea0-e466-444a-8446-2f6033c5ba54)









