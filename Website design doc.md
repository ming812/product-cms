1. Login Page

---------------------------

2. Display All product Page
(
    Display list of product,
    Display list of product by search,
    Edit each product,
    Delete each product
)

2.1 Product Detail Page
(
    product name,
    product images,
    product description,
    price,
    discount,
    category,
    stock qty
)

2.2 Filter and Sorting
(
    Filter Category :
        Boat renting,
        Gear renting,
        Package

    Sorting :
        product name (A-Z) (accending),
        product name (A-Z) (desccending),
        price,
        qty,
)

3. Transaction History Page
(
    Display all the transaction record,
    Display all the transaction record by search,
    Approve or cancel transaction
)

3.1 Transaction Detail Page
(
    customerID,
    customer contact(tel.),
    productName,
    price,
    stock qty,
    transaction status
)

3.2 Filter and Sorting
(
    Filter Category :
        category,
        transaction status,
        product name,
        price,
        customerID

    Sorting :
        product name (A-Z) (accending),
        product name (A-Z) (desccending),
        transaction status,
        customerID,
        price,
        qty,
)

4. User right control Page
(
    Admin - (
        edit and delete user right , 
        edit and delete product ,
        approve and reject transaction
    ),
    Manager - (
        edit 'Senior Staff' and 'Staff' and itself right,
        edit and delete product,
        approve and reject transaction
    ),
    Senior Staff - (
        edit itself right,
        edit and delete product,
    ),
    Staff - (
        edit itself right,
        edit product
    )
)