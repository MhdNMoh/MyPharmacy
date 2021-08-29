# MyPharmacy :
MyPharmacy is an application that helps pharmacies managing their branches and employees along with the customer in a very organized way 

## Features :
1. User Authentication
2. Add your pharmacy details and whereabouts
3. Add branches to your pharmacy
4. Add Employees to any branch in your pharmacy and there are three user types that you can add as a manager 
    - Vendor Manager (manages receiveing products from the vendors and writing an invoice )
    - Employee who is responsible for selling products in the branch and interacting with customers
    - Warehouse Manager who is responsible for managing the products in the warehouse [Still in development]
5. Add Customers to your pharmacy
6. Manage Depts and Returns from customers
7. Write a receipt for the customer and print a PDF copy of it 
8. Add a unique barcode to each receipt and invoice 
9. Scan the products barcode 
10. You can scan the receipt to immediately sell the same products again
11. You can manage expired products either by returning them the the vendor or disposing of them
12. You will get a notification when a product in your branch is almost out 
13. You can see a detailed product report to view information about this product and the branches that sells it
14. You can see a detailed report to view all the sales and returns and the dept informations along with a graph
15. You can view a yearly report of the revenue and the losses of the pharmacy along with a graph for each month
16. You can view information about an employee and see all the sales and purchases they did
17. You can view information about a branch and see all the sales and purchases done from this branch

## Used in this app :
- Architecture :
	- [Lifecycle](https://developer.android.com/jetpack/androidx/releases/lifecycle)
	- [Viewmodel](https://developer.android.com/topic/libraries/architecture/viewmodel)
	- [Retrofit](https://square.github.io/retrofit/)
	- [Firebase Authentication](https://firebase.google.com/docs/auth)
	- [Firebase Realtime Database](https://firebase.google.com/docs/database)
	- [Firebase Cloud Messagin](https://firebase.google.com/docs/cloud-messaging)

- UI :
	- RecyclerView
	- Fragments

- Third party and miscellaneous libraries :
	- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
	- [Android-ProgressViews](https://github.com/zekapp/Android-ProgressViews)
	- [FlexBox Layout](https://github.com/google/flexbox-layout)
	- [ZXING](https://github.com/journeyapps/zxing-android-embedded)
	- [Chip Navigation bar](https://github.com/ismaeldivita/chip-navigation-bar)

## Sreenshot :
### Authentication
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131255140-cd80241d-6009-452f-8493-8b8d2f54f64e.gif" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131254998-2aa23d01-a964-4e73-bda2-df2f5660485c.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131255022-069b3f2c-432b-46c4-b0a8-5f9ef99e0c1a.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131255029-03c07ce5-155a-494f-ad3a-6212fed97779.jpg" width="25%">
</p>
	
### Inventory 
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131258820-7802a52f-87a9-49ac-a99b-c4fd3f8950f2.gif" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131258736-e41f4ecb-a9fd-41f7-90eb-c7f2a728efb1.jpg" width="25%">
</p>

### Sales
#### Adding products to the cart
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131258926-fad9af3d-6b06-4adf-8b5c-2fbd3935c633.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131258925-5c891e8f-6771-49cf-8257-ebf685fc4495.jpg" width="25%">
</p>

#### Setting the customer or adding a new one
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131258949-b76f6603-5e0f-44f2-89c9-982f190a9bb7.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131258950-786c80b0-78ba-4436-b6b0-ead337a9d238.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131258947-f0344922-6e04-400c-bc86-fdaeeda689bc.jpg" width="25%">
</p>

### Customers Informations:
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131259731-5fb90c1f-4624-40b7-909a-40b112ee2245.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131259737-ffef649d-f7dc-4987-8a0e-62e15f864f59.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131259729-1bf702dc-6f9f-441b-b923-b2ff2e200113.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/80918411/131259743-f69f9ad7-d634-4f93-bf7f-9fa4f00dd396.jpg" width="25%">
</p>

