# 💱 My Currency Converter

A desktop-based **Currency Converter Application** developed using **Java Swing** in :contentReference[oaicite:0]{index=0}.  
This project provides a simple and user-friendly interface to convert amounts between multiple international currencies.

---

## 🚀 Features

### ✅ Core Functionalities
- Convert currency values instantly between selected countries.
- Supports multiple countries/currencies.
- Easy dropdown selection for **From** and **To** currencies.
- Fast conversion using button click.
- Clear and simple GUI.

### ✅ Input Handling
- Input validation for empty values.
- Prevents invalid numeric entries.
- User-friendly error messages.

### ✅ UI Features
- Java Swing based graphical interface.
- Centered JFrame window.
- Clean layout with buttons, labels, and dropdown menus.
- Easy to use for beginners.

### ✅ Extra Features Added
- Currency country names support 
- Swap functionality between selected currencies.
- Auto-convert after swap.

---

## 🌍 Supported Countries / Currencies

Currently includes currencies such as:

- 🇮🇳 India (INR)
- 🇺🇸 USA (USD)
- 🇧🇷 Brazil (BRL)
- 🇳🇬 Nigeria (NGN)
- 🇨🇦 Canada (CAD)
- 🇰🇪 Kenya (KES)
- 🇮🇩 Indonesia (IDR)

> More countries can be added easily in the source code.

---

## 🛠️ Technologies Used

- Java
- Java Swing
- AWT
- Event Handling
- NetBeans GUI Builder


========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "Currency_Converter.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
