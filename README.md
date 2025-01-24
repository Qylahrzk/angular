# Angular
# Friendlychat
=======

# FriendlyChat - Angular Firebase Project

This project demonstrates the development of a real-time web chat application using Angular and Firebase. It includes features such as user authentication, real-time messaging, and file sharing, leveraging Firebase's Firestore, Authentication, and Storage services.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.4.

---

## **Project Details**

### **Author Information**
- **Name**: NUR AQILAH BINTI ABDUL RAZAK 
- **Student ID**: 2023239326 
- **Group**: T5CDCS2703B1  
- **Lecturer Name**: SIR MUHAMMAD ATIF BIN RAMLAN  


## **Setup Instructions**

To clone and run the application on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Qylahrzk/angular.git
   cd angular

2. Install the necessary dependencies:
   npm install

3. Start the development server:
   ng serve --open

4. If you encounter host or firewall restrictions, use this command:
   ng serve --open --host 0.0.0.0 --disable-host-check

5. Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

6. To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

7. Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

8. Run `ng build` to build the project. The build artifacts will be stored in the `dist/`directory.

9. Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

10. Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.


## **Project Background**

This project was developed as part of an individual assignment to explore the integration of Angular with Firebase. Following a guided lab activity, the aim was to build a functional web chat application and understand the concepts of real-time database interaction, user authentication, and file storage.


## **Discussion SneekPeek**

The Angular Firebase Web-Friendly Chat lab activity was both challenging and rewarding, expanding my knowledge of Angular and Firebase. The assignment involved using Angular's core concepts, integrating Firebase services like Firestore, Authentication, and Storage, and resolving various technical issues.

**Challenges**
1. Angular Version Compatibility:
The version mismatch between Angular 18 (as per the lab instructions) and Angular 19 on my system led to errors. Downgrading Angular CLI and core packages resolved this issue.

2. Errors During AngularFire Installation:
Syntax errors in the package.json file caused the npm install to fail. Using a JSON validation tool helped identify and fix the issue.

3. Firebase Hosting and AI Features:
The free Firebase plan restricted access to AI features. I focused on local development to test core features like real-time chat and authentication, learning about the limitations of free-tier services.

4. Profile Picture and Image Handling:
Uploading and displaying images in Firebase Storage was problematic due to incorrect URL generation and permission issues. Adjusting storage rules and optimizing image loading resolved the issue, though delays remained.

**Lessons Learned**
1. Angular Core Concepts:
I improved my understanding of Angular's components, services, RxJS, and routing. These concepts are key to building dynamic and scalable web applications.

2. Firebase Integration:
Firebase provided reliable backend services, especially for real-time data storage (Firestore), user authentication, and image management. Understanding Firestore’s data structure and managing storage permissions was crucial.

3. Debugging and Problem-Solving:
This lab sharpened my debugging skills. I used tools like Visual Studio Code, Command Prompt, and Chrome DevTools to diagnose and resolve errors effectively.
   
For a detailed discussion, please refer to the report.
