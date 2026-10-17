# DriveBridge APEX - Oracle APEX Reports to Google Drive

Integrate Oracle APEX with Google Drive to export reports, upload files, and manage Drive files directly from your application.

DriveBridge APEX is an Oracle APEX application that integrates Google Drive with Oracle APEX using the Google Drive REST API and OAuth 2.0 authentication. It enables users to export reports in Excel format, upload files to Google Drive, and manage files and folders directly from the APEX interface.

---
## Features

* **Report Export:** Export Oracle APEX reports in Excel format.
* **Automated Report Upload:** Use Oracle APEX Automation to generate and upload reports to Google Drive.
* **Google Drive Integration:** Upload files directly to a selected Google Drive folder.
* **File Management:** List and view files stored in Google Drive from within the APEX application.
* **File Download:** Download files from Google Drive.
* **OAuth 2.0 Authentication:** Authenticate with Google APIs using OAuth 2.0 access tokens.
* **PL/SQL Integration:** Use Oracle APEX Web Services and PL/SQL to communicate with Google Drive APIs.
* **JavaScript Integration:** Use JavaScript to support Google authentication and Drive operations.

---
## Technologies Used

* Oracle Application Express (APEX)
* Oracle Database
* SQL and PL/SQL
* JavaScript
* Google Drive REST API
* Google Identity Services (GIS)
* OAuth 2.0
* APEX Web Services
* APEX Automation
* APEX Collections
* AJAX Callback

---
## Prerequisites

Before setting up the application, ensure that you have Oracle APEX 26.2 and the following:

* Access to an Oracle APEX workspace and database.
* Permission to import and run an Oracle APEX application.
* A Google account with access to Google Drive.
* Access to the Google Cloud Console.
* The Google Drive API enabled in your Google Cloud project.
* A configured OAuth 2.0 Client ID and Client Secret.
* A Refresh Token and the required access tokens for the authentication flow used by your implementation.

---
## Installation and Configuration

### Step 1: Download the Project
Download the repository as a ZIP file and extract it locally.

### Step 2: Import the Oracle APEX Application
1. Sign in to your Oracle APEX workspace.
2. Navigate to **App Builder**.
3. Find **Import**.
4. Select the application export file included in this repository.
5. Follow the import wizard and click **Install with Supporting Objects**.

### Step 3: Configure Google OAuth 2.0
Google OAuth 2.0 credentials are required to complete the application setup and enable access to Google Drive. Follow the included document for the complete, step-by-step configuration process. The document covers:

1. Creating or selecting a Google Cloud project.
2. Enabling the Google Drive API.
3. Configuring the OAuth consent screen.
4. Creating an OAuth Client ID and Client Secret.
5. Opening Google OAuth 2.0 Playground and generating a Refresh Token.

---
## After Installation and Configuration

1. Open DriveBridge APEX.
2. Complete the Google credentials setup.
3. Navigate to the **DriveBridge Apex** tab.
4. Under **Employee Task**, click the **Upload to Drive** button to export the report in Excel format and upload it to your Google Drive folder.
5. Navigate to **Google Drive Files** to load the files stored in Google Drive.
6. Verify that the uploaded file appears in the application.
7. Test opening and downloading files.
8. Navigate to **Automation Configuration** to run the automation and upload reports to your Google Drive folder.
9. Check the automation execution log.

**Click here to launch the Live Demo**
 [DriveBridge Apex](https://oracleapex.com/ords/r/procurement_foundry/g-drive121148/login?)
 Username: demo
 Password: driveBridge#456
---

If you find this project useful, consider giving the repository a ⭐ on GitHub.
