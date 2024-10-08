# AviLog

## Project Overview

AviLog is a logbook entry application designed for pilots to track their flight information. The app allows users to log various aspects of their flights, including landings, instrument approaches, aircraft category, instrument time, and flight time. The app also provides a summary view where users can see totals for different categories and filter the summary by date range.

## Features

- **Flight Information Entry:** Log details such as date, aircraft model, ID number, departure and arrival points, and stops.
- **Landings:** Track both day and night landings.
- **Instrument Approaches:** Record the number and type of instrument approaches.
- **Aircraft Category:** Log time spent in various aircraft categories (Single-Engine, Multi-Engine, etc.).
- **Instrument Time:** Track time spent under actual, hooded, and simulator conditions.
- **Flight Time:** Record various aspects of flight time including PIC, Solo, and Dual Received.
- **Summary View:** Calculate totals for all logged entries and filter results by a date range.
- **Log Entry View:** Displays all log entries in a table-like view, with key columns visible and the option to download all entries as a CSV file.
- **CSV Export:** Export log entries in CSV format.

## Installation

### Setting Up Your Development Environment
Ensure you have Xcode installed on your macOS machine. Clone this repository, open it in Xcode, and press the Run button.
1. **Clone the Repository:**

    ```bash
    git clone https://github.com/noturlluvia/pilot-logbook-app.git
    ```

2. **Open the Project in Xcode:**

   - Open `AviLog.xcodeproj` in Xcode.
   - Ensure that all dependencies are resolved and the project builds successfully.

3. **Run the App:**

   - Select your target device or simulator in Xcode.
   - Click the run button to build and launch the app.

### Running the App on an iOS Device or iPad
To run the app on your iOS device or iPad, follow these steps:

1. **Connect Your Device**:
   - Connect your iOS device or iPad to your Mac via a USB cable.
   - Unlock your device and, if prompted, choose to trust this computer.
   
2. **Select Your Device**:
   - In Xcode's top device toolbar, select your connected device (iPhone or iPad).
   
3. **Build and Install the App**:
   - Press the 'Run' button in Xcode to build and install the app on your device.
   
4. **Trust Your Developer Profile**:
   - If necessary, go to `Settings` > `General` > `Device Management` on your iOS device, and trust your developer profile before opening the app.

**Note**: This project is developed under Xcode 13.4.1 and does not support iOS versions beyond iOS 15.

## Usage

1. **Log Entry:** Fill in the flight details in the form and save the entry.
2. **Summary View:**
   - Access the summary view to see total hours and other statistics.
   - Use the date range picker to filter the summary based on specific dates.
3. **Log Entry View:**
   - View all your logged entries in a table format.
   - Export your data in CSV format for offline analysis or backup.

## Future Enhancements

- **Graphical Reports:** Add charts to visualize weekly, monthly, and yearly flight data.
- **Improved Data Presentation:** Refine the log entry view for better readability on small screens.
- **Cloud Sync:** Integrate cloud storage to sync data across devices.
- **Enhanced CSV Export:** Improve export options, such as filtering data before export.

## Known Issues

- **CSV Export:** The current implementation allows exporting all data, but it may not work as expected on all devices.
- **Data Visualization:** The current view for log entries is functional but may need adjustments for readability and presentation, particularly with plot options.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
