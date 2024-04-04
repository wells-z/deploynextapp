# deploynextapp

Steps:

1.Install Node.js(My version is v21.5.0)

2.Download and Install HttpPlatformHandler v1.2 from Offical Website.

3.Create app using "npx create-next-app@latest".

4.Execute "npm i".

5.Modify "next.config.mjs" and set basePath as '/AppWithNode1'.

6.Execute "npm run build".

7.Copy .next and node_modules folder, and paste it into a new folder which will be the root of sub application.

8.Config IIS(Install IIS, add website and add application pointed to the folder created in Step 5).

9.Add a new web.config(update Node.exe location, mine is C:\Program Files\nodejs\node.exe ).


IIS setting.jpg --- IIS settings(Port:8912). 

Error message.jpg --- Error message. 

Release Folder --- Release Folder Structure

web.config
