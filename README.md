# Run-solution-file-in-VSCode

In this repository I will show how you can run a project in VSCode if you do not have Visual Studio to run a solution (.sln) file, in other words I'll show you how to set up a local testing server.

# Step 1:
- Create a server.bat file using notepad++ and save it in the project folder.

# Step 2:
- Add the following line to the above file and save:
  - python -m http.server

# Step 3:
- Run ./server command in the project terminal and your server will start at localhost 8000.
