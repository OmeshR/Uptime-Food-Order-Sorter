# Uptime Foodify 🚀🍔

### 📋 Overview
The **Uptime Food Order Sorter** is a Python-based application designed to generate daily order reports for food services. It processes Excel files, filters orders by date, and creates detailed, organized reports per restaurant. The reports are saved as images in a dedicated folder on the user’s desktop. With its user-friendly GUI, anyone can upload their data and receive professional reports in no time!

---

### 🌟 Features
- **Excel File Processing:** Upload an Excel file and generate reports seamlessly.
- **Restaurant-specific Reports:** Filters orders by restaurant and organizes them neatly.
- **Dynamic Report Creation:** Automatically creates an “Order Reports dd.mm.yyyy” folder on your desktop with JPEG reports.
- **GUI for Simplicity:** Easy-to-use interface built with Tkinter.
- **Cross-System Compatibility:** Adapts to different systems with dynamic file paths.

  ![image](https://github.com/user-attachments/assets/975f7af0-6aaa-4967-92de-e78630f43de3)


---

### 🖥️ How to Download & Run

#### 1️⃣ Download the Application
1. Navigate to the [Releases Section](#) on this repository.
2. Download the **`Uptime Food Order Generator.7z`** file using the direct Google Drive link.
3. Extract the file to a folder of your choice.

#### 2️⃣ Bypass Windows SmartScreen Protection
1. Locate the extracted `FoodOrderGenerator.exe` file.
2. Double-click to run the file. If Windows SmartScreen protection appears:
   - Click **More Info**.
![image](https://github.com/user-attachments/assets/35158580-02cd-46d4-8ce3-ce2268978e36)
   - Select **Run Anyway**.
![image](https://github.com/user-attachments/assets/5d8cdd9a-1877-4948-a0ba-6c7d193722f1)
3. The application will launch.

---

### 🛠️ Step-by-Step Usage Guide

#### Uploading Your Excel File 📂
1. Launch the application.
2. Click the **Upload** button.
![image](https://github.com/user-attachments/assets/d46a602c-f1a3-49fd-9498-a8185916360c)
4. Select your Excel file that was downloaded in the file picker dialog. Supported formats include `.xlsx`.
![image](https://github.com/user-attachments/assets/92f05730-86da-4bc7-ab14-78da2f6ccb72)
5. Click on "OK" when you get the "success" message.
![image](https://github.com/user-attachments/assets/b778b970-0d1e-4bce-b1a2-447945e6394d)

6. The images with the food order for that day will be on a folder like this in your desktop.

![image](https://github.com/user-attachments/assets/983192f4-8007-4fa2-bfa5-a448504543c9)

#### Generating Reports 📊
1. The program processes the Excel file and filters orders for today’s date.
2. Reports are automatically generated for each restaurant and saved in a folder named:
   - **`Order Reports dd.mm.yyyy`** (e.g., `Order Reports 19.12.2024`).
   - This folder is located on your **desktop**.

#### Accessing Your Reports 📁
- Open the `Order Reports dd.mm.yyyy` folder on your desktop.
- Each report is saved as a **JPEG** file, titled by the restaurant name and date.

---

### 🔍 What the Program Does

1. **Processes Uploaded Excel Files**:
   - Reads data from the uploaded file.
   - Ensures the date format in the `Required Date` column is consistent.

2. **Filters Data by Today’s Date**:
   - Identifies rows matching today’s date based on the `Required Date` column.

3. **Generates Restaurant-specific Reports**:
   - Counts food items based on menu columns.
   - Summarizes data with grand totals.

4. **Creates Image Reports**:
   - Formats data into a readable image.
   - Saves images in a dynamically created desktop folder.

---

### 🖼️ Example Workflow

1. **Input:** An Excel file with columns for restaurants, menus, and required dates.
2. **Process:** The program filters rows matching today’s date and organizes data by restaurant.
3. **Output:** Clean, organized JPEG reports saved in a desktop folder.

---

### 🛡️ Advanced Details for Code Enthusiasts

- **Dynamic File Paths**:
   - Ensures desktop paths adapt to any user’s machine.
   - Relative font paths ensure portability.

- **Error Handling**:
   - Validates Excel formats and prompts users for corrections.
   - Handles missing data or incorrect date formats gracefully.

- **Custom Fonts**:
   - Uses a built-in font for professional, clean report visuals.

- **GUI**:
   - Intuitive interface built with Tkinter.
   - Styled for a modern, vibrant look.

---

### 🧰 Requirements
- **Windows OS** (recommended for the `.exe` version).
- **Python 3.9+** (for developers using the raw script).

---
### IMPORTANT
- ## If you get an error liek the below screenshot:
![image](https://github.com/user-attachments/assets/dc06e203-c7cd-45d0-8905-3e09e7cc4107)

Please note that this is because the excel document you rpovided does not contain any order for today's date. Therefore, please check if anyone has actually put orders for today's date.

Happy sorting! 🎉

