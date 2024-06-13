# MacOS Big Sur Clone 🍎 

A macOS desktop clone. I created this project out of fascination for the Mac/Apple desktop UI and wanted to try to replicate it as closely as possible, even with the dynamic dock behavior.

## 🖥️ Live Demo 

https://macos-aarxa.netlify.app 

## ⚡ Technologies

- `Vite`
- `React.js`
- `TypeScript`
- `Zustand`
- `Framer Motion`

## 🚀 Features 
- **Light and Dark Mode:** Seamlessly switch between light and dark themes for a personalized experience.
- **Custom Background Colors:** Tailor your desktop with the ability to change the background color to suit your style.
- **System Color Preferences:** Customize your system's color scheme with options like blue, green, orange, and more.


## 💭 Process

I began by gathering all the necessary images for the dock and wallpaper. Then, I established constants and implemented Zustand for state management. Next, I worked on the navigation bar and system preference color functionalities. After that, I tackled the dynamic dock, which was a bit challenging to animate. Each dock item scales slightly when selected, creating a realistic effect. I also created a settings modal, allowing users to switch between dark and light modes and change background colors.

## 🤔 How can it be improved?

Start by adding an introductory loading screen, like the one you see on a Mac with the progress bar and Apple's logo. To make this project even better, think about making features like the calculator and calendar docks actually work. In other words, try to make your project function just like the real macOS desktop.

## 🎥 Demo Image
<img width="1851" alt="Screenshot 2024-06-12 at 6 11 14 PM" src="https://github.com/aarxa/macos-big-sur-clone/assets/113505509/faa03394-f91c-4098-a270-f78ba19a059c">
<img width="1985" alt="Screenshot 2024-06-12 at 6 08 52 PM" src="https://github.com/aarxa/macos-big-sur-clone/assets/113505509/0e42477a-86a9-4ee6-b85b-4649ee412fa6">

## 🚦 Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory and run `npm install` or `yarn` to install the required dependencies.
3. Start the project with `npm run dev` or `yarn dev`.
4. Open http://localhost:5173 (or the address displayed in your console) in your web browser to view the application.

