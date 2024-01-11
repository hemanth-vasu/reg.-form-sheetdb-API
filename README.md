# reg.-form-sheetdb-API
# Webinar Registration Form

This project allows you to create a simple webinar registration form using HTML and connect it to a Google Spreadsheet using the **SheetDB API**. Participants can fill out the form with their details, and upon submission, the information is stored in the connected Google Spreadsheet. Additionally, a registration successful page opens in a new tab to confirm the successful submission.

## How to Run

1. **Create a Google Spreadsheet:**
   - Create a new Google Spreadsheet.
   - Rename the file as per your requirement.
   - Copy the `name` attribute value of each input element in the HTML file and paste it as the heading cell of the corresponding column in the spreadsheet. Ensure the names match exactly to map internally.
   - Copy the URL of the Google Spreadsheet.

2. **Log in to SheetDB:**
   - Log in to [SheetDB](https://sheetdb.io/) using your Google account.
   - Click on "Create new API."

3. **Create SheetDB API:**
   - Paste the copied Google Spreadsheet URL in the provided field.
   - Click on "Create."

4. **Copy the ENDPOINT URL:**
   - After creating the API, copy the provided ENDPOINT URL.

5. **Update HTML Form Action:**
   - Open the `webinar-registration-form.html` file.
   - Assign the copied ENDPOINT URL to the `action` attribute of the `<form>` tag.

6. **Run the Project:**
   - Open the `webinar-registration-form.html` file in a web browser.
   - Fill out the form with participant details.
   - Upon submission, the information will be stored in the Google Spreadsheet, and a new tab will open showing the "Registration Successful" page.


## Screenshots

### Model
![img](https://github.com/hemanth-vasu/reg.-form-sheetdb-API/assets/108590416/d5366bf3-5411-4167-88ed-358253d38232)

### Webinar Registration Form
![form](https://github.com/hemanth-vasu/reg.-form-sheetdb-API/assets/108590416/0bc16da8-08f9-4c2d-bcc8-fc3c29cc820e)


### Registration Successful Page
![reg-success](https://github.com/hemanth-vasu/reg.-form-sheetdb-API/assets/108590416/f3fc8614-759e-404b-8866-a5d0d5f505fa)

### Google Spreadsheet - after submission
![gSheet](https://github.com/hemanth-vasu/reg.-form-sheetdb-API/assets/108590416/e1e8111b-60b5-41d4-89df-17b07d767c30)


Feel free to customize the form, styles, and additional features according to your project requirements.
