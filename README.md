# 🌙 Shortcut to Suspend Windows 11/10

![XTDnUtp](https://github.com/user-attachments/assets/e006bd34-9176-4613-9cb6-037fd118a47a)


This project allows you to create a **keyboard shortcut** to quickly and easily suspend Windows 11. 

## 🛠 Creating the Shortcut

1. Right-click on the desktop and select **New > Shortcut**.
2. In the location field, enter:
   ```
   rundll32.exe powrprof.dll,SetSuspendState 0,1,0
   ```
3. Click **Next** and name it as you prefer (e.g., `Suspend Windows`).
4. Click **Finish**.

## ⌨️ Assigning a Keyboard Shortcut

1. Right-click on the created shortcut and select **Properties**.
2. In the **Shortcut** tab, find the **Shortcut key** field.
3. Press the key combination you want to use (e.g., `Ctrl + Alt + S`).
4. Click **Apply** and then **OK**.

## 🚀 Usage

Now you can quickly suspend your PC using the keyboard shortcut you configured. 

## ℹ️ IMPORTANT!!!!
- If suspension does not work, ensure hibernation is disabled by running this command in CMD:
  ```
  powercfg -h off
  ```
- If the **Shortcut key** option does not appear, try moving the shortcut to another location, such as the desktop or the Start menu.



