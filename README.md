# How-to-deploy-on-firebase
1. Install firebase tools, if you haven't installed it yet ```npm install -g firebase-tools```
2. Create build folder for deploying ```npm run build```
3. Enter into your firebase account```firebase login```
4. Setup a firebase context for the current application ```firebase init```
5. Press space to select the features, than enter to confirm your choice.
 
  Select first ```Hoisting```
  
<img width="1410" alt="Screenshot 2023-08-08 at 15 22 31" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/10751b7c-4d92-4505-937a-08a8869d2053">
 
6. Go to the firebase console. And create new project or use an existing project
<img width="726" alt="Screenshot 2023-08-08 at 15 28 17" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/8c9046af-2643-4971-9d49-16b9e65f2df0">

7. Select your project and press enter key.
<img width="726" alt="Screenshot 2023-08-08 at 15 30 04" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/64874216-d4ac-43e5-945e-a8516f2a8750">

8. Type `build` folder. Build is a compiled version of a program.
<img width="726" alt="Screenshot 2023-08-08 at 15 33 46" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/a9d295d8-f0f4-4ee0-803d-658d2cb83244">

9. Configure as a single app --> `yes`.
<img width="726" alt="Screenshot 2023-08-08 at 15 34 19" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/8bad037a-348d-4163-8541-d8e2ed39cbfb">

10. Set up automatic builds and deploys with GitHub --> `no`.
<img width="726" alt="Screenshot 2023-08-08 at 15 35 27" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/ef0366c8-1f49-49b3-bda4-9c4efe86bca7">

11. File build/index.html already exists. Overwrite? --> `no`.
<img width="726" alt="Screenshot 2023-08-08 at 15 36 17" src="https://github.com/SanzharKadyrkulov/How-to-deploy-on-firebase/assets/85862771/cedb7cc3-da46-4cde-a642-4c10aa1ad042">

12. The last part `firebase deploy`.

