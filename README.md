# MedFinder Android Application

<div style="display: flex; flex-wrap: wrap; gap: 32px; align-items: flex-start;">

  <div style="flex: 1; min-width: 300px;">
    <h2>Overview</h2>
    <p><strong>MedFinder</strong> is an Android application designed to help users find the nearest pharmacy with available medicines, skincare products, and other health-related items.</p>
    <ul>
      <li>Medication reminders</li>
      <li>Body Mass Index (BMI) and Basal Metabolic Rate (BMR) calculations</li>
      <li>Medicine search through prescription input or image recognition</li>
      <li>AI-powered diagnosis and medication recommendations</li>
    </ul>
  </div>

  <div style="border: 1px solid #ccc; padding: 8px; border-radius: 8px; text-align: center;">
    <a href="https://github.com/user-attachments/assets/a63eee79-ff53-42a3-8dc8-8489f4890723" target="_blank">
      <video src="https://github.com/user-attachments/assets/a63eee79-ff53-42a3-8dc8-8489f4890723" width="320" alt="MedFinder Demo Video"/>
    </a>
    <p><em>Click image to watch demo</em></p>
  </div>

</div>

## Technologies Used
The application is built using modern Android development practices and technologies:
- **Kotlin** – Primary programming language
- **MVVM Architecture** – For better separation of concerns
- **Clean Architecture & Onion Architecture** – Ensuring maintainability and scalability
- **Room Database** – Local storage for managing data efficiently
- **Retrofit** – REST API integration for fetching pharmacy and medicine data
- **Computer Vision & AI** – Image recognition for prescription scanning
- **Google Maps API** – Location-based pharmacy search
- **XML** – UI design and layout

## Features
- **Pharmacy Finder:** Locate the nearest pharmacy with the required medicines and skincare products.
- **Medication Reminders:** Set alarms for treatment schedules.
- **Health Calculators:** Calculate BMI and BMR for personalized health tracking.
- **Smart Search:** Find medicines via prescription input or AI-powered image recognition.
- **AI Diagnosis:** Get recommendations based on symptoms and prescriptions.

## Installation
Follow these steps to set up the MedFinder app:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/medfinder.git
   ```
2. Open the project in **Android Studio**.
3. Build and run the app on an **Android emulator** or **physical device**.

## Usage
- **Grant Location Access:** Upon launching the app, allow location permissions to enable pharmacy search.
- **Find Nearby Pharmacies:** View pharmacies on a map and tap on markers for detailed information.
- **Set Medication Reminders:** Use the built-in alarm feature to stay on track with your medication.
- **Calculate BMI & BMR:** Input personal health details to track fitness and metabolic rates.
- **Search for Medicines:** Enter a prescription or scan an image for quick lookup.
- **Receive AI-Powered Recommendations:** Get suggestions for medicines based on symptoms and AI analysis.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`):
   ```sh
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```sh
   git commit -m "Add new feature"
   ```
4. Push to your fork:
   ```sh
   git push origin feature-branch
   ```
5. Submit a **Pull Request** for review.

## License
MedFinder is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---
**Note:** This app was initially named *Eshfeeny*, but has since been rebranded to **MedFinder**.

