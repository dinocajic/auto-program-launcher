# Opens a file in a specific file location. 
- The file is opened during a specific time interval (i.e. every 24 hours).
- To run this program, you'll need to create a JAR file.
- Instructions for creating a JAR file with JetBrains IntelliJ IDEA
1. Click File
2. Click Project Structure
3. Select Artifacts under Project Settings
4. Click on the Plus Sign and Select JAR -> From Modules with Dependencies...
5. Click on the ... next to the Main Class. The class with the main() method will populate. Select it.
6. Click OK
7. Select the checkbox "Build on Make"
8. Click Apply
9. Click OK and the Window will close
10. In the top menu, click Build -> Build Artifacts
11. The action menu will appear. Select Build
12. If you've set this up as a project in IntelliJ, you'll just have to navigate to the /out/artifacts/launch-program.jar/launch-program
13. Click on the launch-program (if that's what you named it)