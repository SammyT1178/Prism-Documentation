## Point of Sale ##

### Point of Sale ###
- New Transaction
	- Tendering transaction defaults the tender to cash, even when choosing options such as Credit Card or Check
- Transaction Lookup
- Pending Transactions
- New Disbursement
- Dispersement Lookup
- Drawer Open
- Change Till/Drawer
- Check In
	- Works after setting up subsidiary
	- No longer asks for login informaton
- Check Out
	- Works after setting up subsidiary
	- No longer asks for login informaton
- Time Clock
	- Modifying clock in/out time works as anticipated
	- Could be improved by putting the time and date menus on the same window

- Promotions
		
### Customers ###
- Customer Lookup
	- Works as expected
	- New/Edit works 
	- Profile Photo upload works
	- Webcam Photo capture blocked by Chrome, need to test with other browser maybe
	- Title in Customer Details has no options (Assuming it's titles like Mr., Ms., Dr., etc.)
	![image](https://user-images.githubusercontent.com/61430214/209202786-8fcee737-f910-4fe0-9993-77579c2706bb.png)

- Customer Loyalty
	- Have not been able to get into it yet :(
		
### X/Z-Out ###
- X-Out
- Z-Out
		
## Store Operations ##

### Merchandise ###
- Inventory
	- List View
		- Inventory List only shows after filter is applied 
			- See Employee List
		- Filters for Price Level and Season are useful additions
			- Maybe order Season menu option chronologically rather than alphabetically
				- (Winter -> Spring -> Summer -> Fall -> Holiday -> None)?

	- New Inventory
		- Item creation fairly straightforward
		- Functions as expected

	- Edit Inventory
		- Functions as expected

	- Activate/Deactivate
		- Assuming this is used to place items into Active/Inactive tag
		- Functions as expected

	- Item Details
		- Functions as expected

	- Item Lookup/Style Lookup
		- Filters by 
	- Options

- Physical Inventory
- Vendors
- Departments
- Cost Adjustment Memo
- Price Adjustment Memo
- Quantity Adjustment Memo
- Adjustment Memo Lookup
- Price Manager

### Purchasing ###
- New Purchase Order
- Purchase Order Lookup
- Pending Purchase Orders

### Receiving ###
- New Voucher
- Voucher Lookup
- Pending Vouchers
- New ASN
- ASN Lookup
- Pending ASNs

### Transfers ###
- New Transfer Slip
- Transfer Slip Lookup
- Pending Transfer Slips
- Transfer Verification
- New Transfer Order
- Transfer Orders Lookup

### Employees ###
- Employee Management
	- Employee Lookup
		- List View
			- Employee list only shows once filter is applied and SEARCH button is activated. 
			- It's functional, but a filter feels like it should be applied after a list of employees is given. 
			- A more practical UI would default to showing a list of the current active employees.
			- Keep the toggles for Active/Inactive/All, but make the filter change automatic rather than require the use of a SEARCH
			- Selecting the name should work to open the bottom row options like selecting the checkmark. 
			- The filter via First Name/Last Name/Login works nice

		- New Employee
			- Setting new username/password works
				- Test values used: (username/password)
					- (sjt0134/4697!)
					- (ADMIN/ADMIN)
					- (TEST/TEST)
					- (USER/USER)
				- Functions as expected

		- Edit Employee
			- Functions as expected

		- Details 
			- Functions as expected

		- Change Password
			- Functions as expected
### Auto Tools ###
- Auto Min/Max
- Auto PO
		
## Administration Console ##
Country list starts at Tokelau, continues T-Z, then restarts A-T

Error Pop-up Message Duration automatically set to 0. Allowing users to edit the duration for all three pop-up durations is a great addition, but the error pop-up would probably do best to not be set to stay on indefinitely. 

Custom Seasons works as anticipated.
	- Could be good to add the ability to manually sort seasons

## Tech Tool Kit ##
- Links to the Tech Tool Kit
- Functions as anticipated 

## Language ##
- Does not change language (could be some sort of ASCII conversion error?)
- `Tech Tool Kit` and `Change Password` options are available above and below the `Language` option

## Help ##
`Tech Tool Kit` and `Change Password` options are available above and below the `Help` option
	
- Help 
	- Exits the Help menu, seems redundant. A simple back-arrow UI serves the same function and is universally known. 
- Index
	- Links to https://my.retailpro.com/documentation/
	- Works as anticipated
- About
	- Pretty standard credit window
	- Functions as anticipated 
	
## Change Password ##
- Functions as expected

## Logout ##
- Functions as expected
