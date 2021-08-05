# README
## INVOICE Generator

### Application Overview
Invoice generator for overseas employment agency. Can register your own company information, client information, worker group sent to overseas and all types of fee.

### Functions
- Login function
- User registration function
  - Username, email address and password required
- Invoice list display function
  - Show the invoice created
  - Can sort by client company name
  - Can delete invoice
- New Invoice create function
  - Can create invoice by worker group and request period
- Invoice edit function
- Client list display function  
  - Show the client registered
  - Can delete client
- New Client create function
  - Can register Client information including bank information
- Client edit function
- Worker Group list display function
  - Show the worker group created
  - Can sort by client company name
  - Can check worker group with company name and fee.
  - Can delete worker group
- New Worker Group create function
  - Can register Japan entry date, start working date and end working date
  - Show the period to request invoice
- Worker group edit function
- Fee list display function
  - Show the fee registered
  - Can delete fee
- New Fee create function
  - Can create fee by client company
- Fee edit function

### Development Language
- Ruby 2.6.5
- Rails 5.2.5

### Employment Term Technology
- AWS EC2
- devise

### Technology outside the curriculume
- PDFkit
- wkhtmltopdf-binary
- render_anywhere

### Execution Procedure
```
git clone https://github.com/ChitSuClover/invoiceapp.git
cd invoiceapp
bundle install
rails db:create && rails db:migrate
rails s
```

### Catalog Design
(https://drive.google.com/file/d/1Jf4zVh7_L_5sePkjvlH4NdtOzQETya8t/view?usp=sharing)

### Table Definition Document
(https://drive.google.com/file/d/1Jf4zVh7_L_5sePkjvlH4NdtOzQETya8t/view?usp=sharing)

### Wireframe
(https://cacoo.com/diagrams/cwrsanNz99Gi7Owb/83CAA)
