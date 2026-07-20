# My STM32 Class Projects 🚀

Welcome to my STM32 repository! This project contains the source code and configurations for various STM32 microcontroller exercises and class assignments.

## 🛠 Hardware & Tools
*   **Microcontroller:** STM32 [Insert your model, e.g., F103C8T6 / F407]
*   **IDE:** [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)
*   **Debugger:** ST-Link V2 (or onboard debugger)
*   **Library:** STM32Cube HAL / LL [Choose one]

---

## 📥 How to Import the Project
To use these files in your own STM32CubeIDE environment, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/DavidRashidi2005/My_Stm32_Class_PJ.git
    ```
2.  **Open STM32CubeIDE.**
3.  **Go to File > Import...**
4.  Select **General > Existing Projects into Workspace** and click Next.
5.  Click **Browse** and select the folder where you cloned the repository.
6.  Ensure the project is checked in the list and click **Finish**.

---

## ⚙️ How to Use & Run
Once the project is imported, follow these steps to see it in action:

### 1. Generate Code (Optional)
If you want to change pin configurations:
*   Open the `.ioc` file (STM32CubeMX configuration).
*   Make your changes.
*   Press `Ctrl + S` or click **Device Configuration Tool > Generate Code**.

### 2. Build the Project
*   Right-click on the project name in the **Project Explorer**.
*   Select **Build Project** (or click the Hammer icon 🔨).
*   Check the Console to ensure there are "0 errors".

### 3. Flash to Board
*   Connect your STM32 board to your PC via ST-Link.
*   Click the **Run** button (Green Play icon ▶️) or **Debug** button (Bug icon 🪲).
*   The IDE will flash the `.elf` or `.bin` file to the microcontroller.

---

## 📂 Project Structure
*   **Core/Src**: Contains the main logic (`main.c`) and interrupt handlers.
*   **Core/Inc**: Header files for the project.
*   **Drivers**: Standard STM32 HAL/CMSIS drivers.
*   **[Project_Name].ioc**: The configuration file for peripherals and clocks.
