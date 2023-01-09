# Retail Pro Prism #

## Point of Sale ##

### Point of Sale ###
- New Transaction
	- Tendering transaction defaults the tender to cash, even when choosing options such as Credit Card or Check
		- Could be an issue by not testing with card reader	
	- This can happen (See `Administration Console`)
	![image](https://user-images.githubusercontent.com/61430214/209235985-a9242f13-a717-4915-991c-487028b084fb.png)
	
<!-- - Transaction Lookup 
	- Seems to work as anticipated
- Pending Transactions
	- Seems to work as anticipated
- New Disbursement
	- Seems to work as anticipated  -->
- Dispersement Lookup
	- Not the largest issue, but when viewed in splitscreen, the Reset button no longer lines up with the rest of the buttons
	- Since most POS sales would be done fullscreen, it's not a major issue
	![Disp_Lookup](https://user-images.githubusercontent.com/61430214/209995487-472be05f-52f8-427e-a461-1c12abeda0fc.png)

- Drawer Open
	- Works (allegedly) 
- Change Till/Drawer
	- Seems to work while under an admin account
- Check In
	- Works after setting up subsidiary
	- No longer asks for login information
- Check Out
	- Works after setting up subsidiary
	- No longer asks for login information
- Time Clock
	- Modifying clock in/out time works as anticipated
	- Could be improved by putting the time and date menus on the same window
	- Could also improve by setting the default sort to Event Date Descending
- Promotions
	- Saving promotions seem to work
	- Getting the promotions to show on POS transaction may need to take more testing	
### Customers ###
- Customer Lookup
	- Works as expected
	- New/Edit works 
	- Profile Photo upload works
	- Webcam Photo capture blocked by Chrome, need to test with other browser maybe
	- Title in Customer Details has no options (Assuming it's titles like Mr., Ms., Dr., etc.)
![image](https://user-images.githubusercontent.com/61430214/209202786-8fcee737-f910-4fe0-9993-77579c2706bb.png)
		- Update: After digging through the Admin Console, documentation, and trying every combination of button presses, I managed to get into the menu the user can add titles. There are none by default
![image](https://user-images.githubusercontent.com/61430214/210658196-fc2a64e1-b4b6-411b-8155-32412f533116.png)

- Customer Loyalty
	- Seems to work as expected
### X/Z-Out ###
- X-Out
- Z-Out

Language Option removed from the menu in both X/Z-Out screens

![image](https://user-images.githubusercontent.com/61430214/210091268-d56e61d8-e029-4336-8f29-f40d1516e8ce.png)

Both work as anticipated
## Store Operations ##
### Merchandise ###
- Inventory
	- List View
		- Inventory List only shows after the filter is applied 
			- See Employee List
		- Filters for Price Level and Season are useful additions
			- Maybe order Season menu option chronologically rather than alphabetically
				- (Winter -> Spring -> Summer -> Fall -> Holiday -> None)?
	<!-- - New Inventory
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
		- Filters work as anticipated -->
	- Options
		- The only option available is "Print Tags"
			- Not sure if that's the only Inventory Option, if so ignore this note
			- Else, cut out the middleman by just renaming to Print/Print Tags
- Physical Inventory
	- PI Sheets seem to export to PDF without any issue, will probably print to the printer without issue as well
- Vendors
	- Adding/Editing vendors seem to function without any issues
- Departments
	- Adding/Edition Departments seems to function without any issues	
- Adjustment Memo Lookup
	- Memo lookup works as anticipated 
	- Created date descending is good, sometimes conflicts with Memo No.
	![image](https://user-images.githubusercontent.com/61430214/210389306-b9b64287-20d6-4a2b-bd20-721933c57a0c.png)
- Price Manager
	- Markdown creation and calculations work without issue
### Purchasing ###
- New Purchase Order
- Purchase Order Lookup
- Pending Purchase Orders

All seems to work as expected. Adding a back button would be nice in the details screen so a user isn't forced to choose the menu and retrek back to the lookup screen. 
### Receiving ###
- New Voucher
- Voucher Lookup
- Pending Vouchers
- New ASN
- ASN Lookup
- Pending ASNs

Voucher/ASN menus work as anticipated. Would be good to be able to check multiple items at once. Additionally, adding a button to return to the New Voucher/ASN menu is more intuitive than double-clicking an item after selecting the checkmark.
### Transfers ###
- New Transfer Slip
- Transfer Slip Lookup
- Pending Transfer Slips
- Transfer Verification
- New Transfer Order
- Transfer Orders Lookup

Began testing; New Transfer works as anticipated. Suffers from the same issues as `Receiving` in terms of UX & UI. 
### Employees ###
- Employee Management
	- Employee Lookup
		- List View
			- Employee list only shows once the filter is applied and the SEARCH button is activated. 
			- It's functional but a filter feels like it should be applied after a list of employees is given. 
			- A more practical UI would default to showing a list of the current active employees.
			- Keep the toggles for Active/Inactive/All, but make the filter change automatic rather than requiring the use of a SEARCH
			- Selecting the name should work to open the bottom row options like selecting the checkmark. 
			- The filter via First Name/Last Name/Login works nice
		- New Employee
			- Setting new username/password works
				<!--- Test values used: (username/password)
					- (sjt0134/4697!)
					- (ADMIN/ADMIN)
					- (TEST/TEST)
					- (USER/USER)
				- Functions as expected -->
		- Edit Employee
			- Functions as expected
		- Details 
			- Functions as expected
		- Change Password
			- Functions as expected
### Auto Tools ###
- Auto Min/Max
- Auto PO	

Both seem to function as anticipated

Language Option removed from the menu in both Auto screens

![image](https://user-images.githubusercontent.com/61430214/210091268-d56e61d8-e029-4336-8f29-f40d1516e8ce.png)

## Administration Console ##
Country list starts at Tokelau, continues T-Z, then restarts A-T
![image](https://user-images.githubusercontent.com/61430214/209235620-51168d8a-af4b-4d8b-bb34-305ee3f76df7.png)
![image](https://user-images.githubusercontent.com/61430214/209235702-23567c7e-a0c6-4d6c-a77e-43342bd398b8.png)

Error Pop-up Message Duration automatically set to 0. Allowing users to edit the duration for all three pop-up duration is a great addition, but the error pop-up would probably do best to not be set to stay on indefinitely. 
![image](https://user-images.githubusercontent.com/61430214/209851858-e706e70a-1a4b-4b6c-a30f-e781a1cb6548.png)

Custom Seasons works as anticipated.
	- Could be good to add the ability to manually sort seasons

Password Change requests function as anticipated
## Tech Tool Kit ##
- Links to the Tech Tool Kit
- Functions as anticipated 
## Language ##
- Occasionally does not change the language (could be a language setting on the computer)
- Changing Language in `Administration Console` does not change the language either 
	- Using the Dutch language setting
![image](https://user-images.githubusercontent.com/61430214/209696622-757e0f99-bbfb-43d5-a294-2d7f2ea355c9.png)

- `Tech Tool Kit` and `Change Password` options are available above and below the `Language` option

![image](https://user-images.githubusercontent.com/61430214/209696463-8ff505a0-99fc-4cee-8a9e-eaf95617a6f5.png)
## Help ##
`Tech Tool Kit` and `Change Password` options are available above and below the `Help` option

![image](https://user-images.githubusercontent.com/61430214/209696415-36de6a10-6ebb-488d-af51-b5f57bd554ba.png)
	
- Help 
	- Exits the Help menu, seems redundant. A simple back-arrow UI serves the same function and is universally recognized. 
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

# Retail Pro Reports (Krunch) #

## Installation ##

- Reports download link not being under the `Retail Pro Reports (Krunch)` link could be confusing for those unaware of the Prism association
![reports_krunch_download](https://user-images.githubusercontent.com/61430214/211359097-32db5f5a-1634-4df4-b975-62019be5ca6a.png)
