# PDFDataScrapping - UiPath Automation Project

## Description
This UiPath automation project focuses on scraping data from e-commerce websites. The project is built using UiPath Studio and utilizes various UiPath activities for web automation and data extraction.

## Project Details
- **Project Name:** PDFDataScrapping
- **Studio Version:** 19.12.0.61
- **Project Version:** 1.0.0
- **Framework:** Legacy

## Dependencies
- UiPath.Excel.Activities (2.8.0-preview)
- UiPath.Mail.Activities (1.8.0-preview)
- UiPath.System.Activities (19.12.0-preview)
- UiPath.UIAutomation.Activities (20.4.1)

## Features
- Automated data extraction from e-commerce websites
- PDF data scraping capabilities
- Excel integration for data storage
- Email automation support

## Runtime Configuration
- **Auto Dispose:** Disabled
- **Lazy Loading:** Disabled
- **Pausable:** Yes
- **Attended:** No
- **User Interaction Required:** Yes
- **Persistence Support:** No

## Installation & Setup
1. Clone this repository
2. Open the project in UiPath Studio (version 19.12.0 or compatible)
3. Restore NuGet packages
4. Build the project

## Usage
1. Open the project in UiPath Studio
2. Configure any necessary settings in the `Main.xaml` workflow
3. Run the automation

## Project Structure
- `Main.xaml` - Main workflow file
- `project.json` - Project configuration and dependencies

## Security Notes
The project is configured to exclude logging of:
- Private data
- Password information

## Development Profile
- **Profile Type:** Development
- **Output Type:** Process
- **Expression Language:** VisualBasic

## Contributing
Feel free to fork this repository and submit pull requests for any improvements
