

# Picture In Picture Api

![Picture In Picture Api Preview](screenshot.png)
You can check it out [here](https://d-vokic.github.io/Quotations-Generator-App/).

## Author

👤 **Duško Vokić**

* LinkedIn: [Here](https://linkedin.com/in/duško-vokić-0337a2106)
* GitHub: [@D-vokic](https://github.com/D-vokic)

This application enables users to initiate Picture-in-Picture mode using their web browser. The application promotes a simple and intuitive user experience for leveraging Picture-in-Picture functionality within a web browser.

## Usage Instructions
1. Visit the Picture In Picture Api App website.
2. Open the Application: Open the web application in a compatible web browser.
3. Select Media Stream: Click on the designated button labeled "START". This action prompts the browser to ask for permission to capture your screen or a specific application window.
4. Initiate Picture-in-Picture Mode: Once you've selected the desired media stream, click on the button labeled "Start Picture-in-Picture Mode". This action activates Picture-in-Picture mode, displaying the selected media stream in a small floating window.
5. Interact with Picture-in-Picture Window: You can move, resize, or close the Picture-in-Picture window as needed. It will remain visible even if you switch tabs or applications.
6. End Picture-in-Picture Mode: To end Picture-in-Picture mode, simply close the Picture-in-Picture window. This action returns the application to its default state.
7. Repeat Process: If you wish to start Picture-in-Picture mode again or select a different media stream, you can repeat the process by clicking the corresponding buttons.
8. Handle Errors: If you encounter any errors during the process, such as inability to access the media stream, check your browser permissions and ensure that you've granted necessary access.

Following these instructions, you can effectively utilize the Picture-in-Picture functionality provided by the application.

## Additional Details
1. Compatibility: The application utilizes modern web APIs and features, so it works best on up-to-date web browsers that support the necessary APIs for capturing media streams and enabling Picture-in-Picture mode. It's advisable to use the latest versions of popular web browsers like Google Chrome, Mozilla Firefox, or Microsoft Edge for the best experience.
2. Permissions: The application requires user consent to access media devices such as screens or application windows. When prompted by the browser, be sure to allow access to the media stream for the application to function correctly.
3. Picture-in-Picture Controls: While in Picture-in-Picture mode, users may have access to certain controls provided by the browser or the operating system. These controls may vary depending on the platform and browser being used. Users can typically expect options to resize, move, or close the Picture-in-Picture window.
4. User Feedback: The application provides basic console logging for error handling. Users can check the browser console for any error messages if something goes wrong during the process of selecting a media stream or initiating Picture-in-Picture mode.
5. Security Considerations: As with any application that accesses media devices, users should exercise caution and ensure they trust the source of the application. It's recommended to use applications from trusted sources and grant permissions only to applications that require access to specific functionalities.
6. 
By considering these additional details, users can make the most of the application while ensuring a secure and reliable experience when using Picture-in-Picture mode within their web browser.

### Overview
This application features a convenient Dark Mode/Light Mode switch for enhanced user experience customization. Users can seamlessly toggle between Dark and Light modes to suit their preferences and reduce eye strain in different lighting conditions.

### Key Features
1. Media Stream Selection: Users can choose a media stream, such as their screen or a specific application window, to be displayed in Picture-in-Picture mode.
2. Picture-in-Picture Mode Activation: The application enables users to activate Picture-in-Picture mode, allowing the selected media stream to be displayed in a floating window overlaying other content on the screen.
3. Error Handling: The application gracefully handles errors encountered during the process of accessing the media stream or initiating Picture-in-Picture mode, providing feedback to the user through console logging.
4. User Interaction: Users can interact with the Picture-in-Picture window, including moving, resizing, or closing it as needed for optimal viewing and usability.
5. Accessibility: The application aims to provide an accessible and intuitive user experience, making it easy for users to understand and utilize Picture-in-Picture functionality within their web browser.
6. Compatibility: The application is designed to be compatible with modern web browsers that support the necessary APIs for capturing media streams and enabling Picture-in-Picture mode, ensuring a seamless experience across different platforms.
7. Security: While accessing media devices, the application prioritizes user privacy and security, adhering to browser permissions and best practices to protect user data and ensure a safe browsing experience.

These key features collectively enhance the user experience and functionality of the application, empowering users to leverage Picture-in-Picture mode effectively within their web browser environment.

### Usage
1. Accessing the Application:
> Open a compatible web browser.
> Navigate to the URL or webpage where the application is hosted.
2. Selecting Media Stream:
> Upon accessing the application, users encounter an interface featuring a "Select Media Stream" button.
> Click on the "Select Media Stream" button to initiate the process of choosing a media source.
3. Granting Permissions:
> The browser prompts the user to grant permission for the application to access media devices, such as the screen or specific application windows.
> Users need to allow the necessary permissions for the application to proceed.
4. Initiating Picture-in-Picture Mode:
> After granting permissions, users can select the desired media stream.
> Once a media stream is selected, users click on the "Start Picture-in-Picture Mode" button.
> This action triggers the activation of Picture-in-Picture mode, where the chosen media stream appears in a floating window overlaying other content on the screen.
5. Interacting with Picture-in-Picture Window:
> Users can move, resize, or close the Picture-in-Picture window as needed for optimal viewing.
> The Picture-in-Picture window remains visible and accessible even when users switch tabs or applications.
6. Ending Picture-in-Picture Mode:
> To exit Picture-in-Picture mode, users simply need to close the Picture-in-Picture window.
> Once closed, the application returns to its default state, ready for users to start the process again if desired.
7. Handling Errors:
> In case of any errors encountered during the process, users can check the browser console for error messages.
> The application provides basic console logging for error handling, ensuring users are informed of any issues that may arise.
> By following these steps, users can effectively utilize the application to access and enjoy Picture-in-Picture functionality within their web browser environment.

### Benefits
1. **Enhanced Multitasking:** Users can engage in multitasking activities by overlaying a selected media stream, such as a video conference, webinar, or tutorial, on top of other applications or web pages while continuing to work or browse.
2. **Improved Accessibility:** Picture-in-Picture mode enhances accessibility by allowing users to keep important content, such as video lectures or presentations, visible and accessible while simultaneously interacting with other digital resources or applications.
3. **Efficient Learning and Collaboration:** For educational purposes or collaborative work environments, users can benefit from the ability to view instructional videos, share screens, or participate in video calls without interrupting their workflow or switching between different windows.
4. **Flexible Viewing Experience:** Users have the flexibility to resize, move, or close the Picture-in-Picture window according to their preferences and viewing needs, providing a customizable and user-centric viewing experience.
5. **Simplified User Interface:** The application offers a straightforward and intuitive user interface, making it easy for users to select media streams, activate Picture-in-Picture mode, and interact with the floating window without the need for complex configurations or settings.
6. **Cross-Platform Compatibility:** The application is compatible with modern web browsers across different platforms, enabling users to leverage Picture-in-Picture functionality on desktop computers, laptops, and compatible mobile devices, regardless of the operating system.
7. **Privacy and Security:** By utilizing browser permissions and adhering to best practices for data privacy and security, the application prioritizes user privacy and safeguards sensitive information while accessing media streams and interacting with content in Picture-in-Picture mode.

Overall, the application enhances productivity, facilitates seamless collaboration, and provides a versatile viewing experience for users across various digital contexts and workflows.

### Implementation
The application is implemented using HTML, CSS, and JavaScript to enable Picture-in-Picture functionality within a web browser. Here's a brief overview of the implementation:

1. **HTML:**
The HTML file defines the structure of the application with elements such as video containers and buttons.
Elements include:
<video> element for displaying the media stream.
<button> elements for triggering actions such as selecting a media stream and starting Picture-in-Picture mode.
2. **CSS:**
The CSS file styles the HTML elements to create a visually appealing and user-friendly interface.
Styling includes basic layout, button appearance, and responsive design for cross-browser compatibility.
3. **JavaScript:**
The JavaScript file contains the application's logic and functionality.
Event listeners are set up to respond to user interactions with buttons.
Functions are defined to handle actions such as selecting a media stream, initiating Picture-in-Picture mode, and managing errors.
Asynchronous operations (e.g., accessing media devices) are handled using async/await for smooth user experience.
The application logs errors to the console for debugging purposes.
4. **Picture-in-Picture API:**
The application utilizes the browser's built-in Picture-in-Picture API for managing the Picture-in-Picture mode.
This API allows seamless transition to Picture-in-Picture mode, control over the Picture-in-Picture window, and handling events associated with Picture-in-Picture functionality.
5. **Compatibility and Security:**
The application ensures compatibility with modern web browsers and follows security best practices.
Browser permissions are requested for accessing media devices, prioritizing user privacy and security.
6. **Error Handling:**
The application includes error-handling mechanisms to gracefully manage issues that may arise during the process of accessing media streams or initiating Picture-in-Picture mode.
Errors are logged to the console to assist users and developers in identifying and resolving issues.
7. **User Instructions:**
Clear and concise instructions guide users through the process of selecting a media stream, activating Picture-in-Picture mode, and interacting with the Picture-in-Picture window.

In summary, the application combines HTML for structure, CSS for styling, and JavaScript for interactivity to create a user-friendly interface that leverages the browser's Picture-in-Picture API for enhanced viewing experiences. The implementation prioritizes compatibility, security, and efficient error handling for a seamless user experience.

### Integration
Integrate the Picture-in-Picture application by including its JavaScript file for core functionality, embedding HTML markup for media display and user interaction, styling elements with CSS, and implementing error handling, enabling seamless multimedia experiences within existing web applications or websites.

### Conclusion
In conclusion, the Picture-in-Picture application offers users a convenient way to multitask and engage with multimedia content within their web browser, providing enhanced accessibility, flexibility, and user interaction while prioritizing compatibility and security for a seamless and enjoyable viewing experience.

## Technologies and Languages

- HTML5
- CSS3 (Sass)
- JavaScript

## License

This project is licensed under the [MIT License](https://www.mit.edu/~amini/LICENSE.md).

## Contact Information

You can contact me via email: vokic.dusko@gmail.com
