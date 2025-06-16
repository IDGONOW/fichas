IDGoNow Application

This application allows users to register individuals (people or pets) and create a digital identification ficha. This ficha helps in quick identification in situations like loss, emergency, or disorientation.

## Functionality

- **User Registration:** Users can register either a person or a pet through dedicated forms.
- **Digital Identification Ficha:** Upon successful registration, a digital identification ficha is generated.
- **Accessibility:** This ficha can be accessed using NFC (Near Field Communication) technology or by scanning a QR code with any mobile device.
- **Purpose:** The primary goal is to provide a quick and efficient way to identify a person or pet in critical situations such as:
    - Cases of getting lost
    - Medical emergencies
    - Instances of disorientation

## Key Files

- **index.html:** This is the main landing page of the application. It provides users with options to navigate to the registration page for either a person or a pet.
- **registro_persona.html:** This page contains the form required to register a person. Users will input necessary details for the creation of the digital ficha.
- **registro_mascota.html:** Similar to registering a person, this page hosts the form for registering a pet, capturing relevant information for its digital ficha.
- **ficha.html:** This HTML file is responsible for displaying the generated digital identification ficha. It is designed to be easily accessible and readable on mobile devices.

## How to Use

1.  **Navigate to the application:** Open the `index.html` file in a web browser or access the application through its deployed URL.
2.  **Choose Registration Type:** On the main page, select whether you want to register a person or a pet.
3.  **Fill out the Registration Form:**
    *   For a person, you will be directed to `registro_persona.html`.
    *   For a pet, you will be directed to `registro_mascota.html`.
    *   Complete all the required fields in the form, including uploading a photo.
4.  **Submit the Form:** After filling out the details, submit the form.
5.  **Access the Digital Ficha:** Once submitted, a digital ficha will be created. This ficha can be linked to an NFC tag or a QR code for easy access. When the NFC tag is tapped or the QR code is scanned, the `ficha.html` page will display the registered information.
