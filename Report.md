## Test task 
## Innoscripta
Watch videos: 
- Find as many bugs as u can;
- Record them; 
- Create bug reports in any convenient form; 
- If you have any proposals to enhance the system - feel free to write them.


### Testing a crm system using pre-recorded videos with a description of the functionality:

# Bug-1
## Description: An empty button is displayed in the selection menu.
### STR:
1. Go to http://crm.innoscripta.com/login
2. Login to the system using valid user data
- Expected Result: All buttons in the menu have an assigned value.
- Actual result: An empty button is displayed in the menu
.
![](https://user-images.githubusercontent.com/77203425/142514946-4f1eba58-7122-4740-ab8d-0aee49f3b086.png)
### Environment:
 Win 7,
Google chrome  96.0.4664.45 
Video 1


# Bug -2
## Description: The text is out of bounds after changing the display type.
### Precondition: You must log in to http://crm.innoscripta.com/login
### STR:
1. Go to Revenue and Planning to the Ideen section.
2. Change the display by clicking on the button under Change View.
- Expected Result: The description text is displayed smoothly.
- Actual result: The text of the description goes beyond the boundaries and is layered on the next one.
![](https://user-images.githubusercontent.com/77203425/142514947-18b2459e-0aab-4aa9-bd5e-46571a6ab3b9.png) 
### Environment:
 Win 7,
Google chrome  96.0.4664.45 
Video 2



# Bug-3
## Description: Language inconsistency in RP section.
### Precondition: You must log in to http://crm.innoscripta.com/login
### STR:
1. Go to Revenue and Planning
- Expected Result: All menu buttons are displayed in English.
- Actual result: Button Ideen - German.
![](https://user-images.githubusercontent.com/77203425/142514949-258a4ded-f333-4642-a3ba-8e6548092b4b.png)
### Environment:
 Win 7,
Google chrome  96.0.4664.45 
Video 2







## Part 2
### Inspect those sites: 
- http://sff.innoscripta.com/ 
- http://ideas.innoscripta.com/ 
- https://innoscripta.com/ 
#### Find as many bugs as you can and record them, create bug records.


# Bug-1
### Description: The input field accepts invalid email values.
### STR:
1. Go to the website https://sff.innoscripta.com/
2. Scroll down to the input field with the inscription "Wir stellen mit Ihnen in einem unverbindlichen Termin fest, ob wir zueinander passen"
3. Enter valid values ​​in the Varname Nachname field
4. In the email field, enter "2"
5. Press "Absenden"

- Expected Result: The email input field is underlined in red, a valid input message appears.
- Actual result: A window for filling in the data is opened.

https://user-images.githubusercontent.com/77203425/142514937-70dac86f-8ecb-46f3-abfb-27a1e869ab9d.mp4
### Environment:
 Win 7,
Google chrome  96.0.4664.45




# Bug-2
### Description: Incorrect university names in the drop-down list.
### STR:
1. Go to the site http://ideas.innoscripta.com/
2. Press the button "Registrieren"
3. In the opened window , open the drop-down list.


- Expected Result: The correct university names have been provided.
- Actual result: Incorrect names are present in the list.
![](https://user-images.githubusercontent.com/77203425/142514945-3456cba7-13ba-4ed3-98b5-495fe6542bdf.png)
![](https://user-images.githubusercontent.com/77203425/142514943-d2ef9d3e-f25b-488f-8124-0801c824098b.png)
### Environment:
 Win 7,
Google chrome  96.0.4664.45 



# Bug - 3
### Description: Incorrect university names in the drop-down list.
### STR:
1. Go to  http://ideas.innoscripta.com/
2. Press the button "Registrieren".
3. In the opened window, fill in the fields with valid data.
4. In the field "telefon" put a "+" sign.
5. Press "Weiter"


- Expected Result: The telephone underlined in red field displays an error message.
- Actual result: The form is completed successfully.

https://user-images.githubusercontent.com/77203425/142514921-3a645769-48c2-47e8-8d6b-f14c20140f79.mp4

### Environment:
 Win 7,
Goofle hrome 96.0.4664.45 

to be end

