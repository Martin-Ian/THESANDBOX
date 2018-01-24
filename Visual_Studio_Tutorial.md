# How to Create a new win32 C++ Project in Visual Studio 2017
This is a guide on how to create a new **win32 C++ project** in _Visual Studio 2017._
Follow Each step and when you finish, you will have a c++ project to play around in! 

1. The First thing you want to do is open up _Visual Studio 2017._
	
	If you don't own _Visual Studio_, go **[HERE](https://humboldt.onthehub.com/WebStore/Welcome.aspx "HSU's free Software")** to download it.
	
2. Now that you have _Visual Studio_ open, it is time to create a new project!
	1. In the _upper left_, click on **'File'**
	2. Select **'New'** then in the menu select **'Project'**
	3. A new window should appear. for our purposes we want a C++ file.
		1. On the _left_ of the window drop down **'Installed'** and then **'Visual C++'**
		2. Now open **'General'** and select **'Empty Project'**
		3. Go ahead and name your project, and select your desired location
			1. Remember, if you are on a school Lab computer to create a **'bin'** folder!
			
3. A new Project has now been created! We are not done yet...
	1. In order for our project to work properly we need to set it as a console application.
		1. On the _right hand side_ on the window, open the drop down menu for your project
			1. This should be the _second_ line, under the solution.
		2. Right click this folder and select **'Properties'**.
		3. This will open a confusing window, but don't be discuraged!
			1. In **'General'** Make sure that the Visual Studio **'Windows SDK Version'** is the same as your computer's.
				1. If it isn't, you won't be able to compile.
			2. Next, you want to open the drop down menu for **'Linker'**, then select **'System'**
			3. You need to select the **'SubSystem'** and select **'Console'**
			4. Now select **'Apply'** and exit the window.
		4. Now go ahead and start coding! once you are done, its time to compile and run it.
			1. To build and run your code, go to the _upper menu_ and open **'Debug'**.
			2. Now select **'Start Without Debugging'**

			
			
**Congrats! You now have a win32 C++ project in _Visual Studio 2017_!**
