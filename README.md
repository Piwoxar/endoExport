# endoExport
Export workouts from Endomondo as xml files

# Prerequsits
Excel 2013. Probably Excel 2010 will also works but I could not test it up to now.

You need to allow the execution of macros at least for this Excel file.

At the Endomondo web site you need to mark 'Try our cool new workout page' in Endomondo->Settings

# Steps
Open the Excel file EndomondoWorkouts.xlsm.

In the menu choose 'Endomondo -> Endomondo -> Read Workouts'

At the popup enter your endomondo user and password.

Now all your workouts will be loaded and saved as a xml file.

The Excel sheet 'Workouts' shows your workouts

To get the details you can select a line and choose 'Endomondo -> Endomondo -> Read Workout Details'

The details will be displayed in the sheet 'Workout'.

The workout details are also stored as a xml file

To download all workout details you can select the whole column 'WorkoutId' at sheet 'Workouts' and choose 'Endomondo -> 
Endomondo -> Read Workout Details'

You will find the xml files in the folder where you Excel file is located under Workouts\user_&lt;your endomondo user id&gt;.

If you run the export some times later again only the new workouts will be exported.

You can also show the content of the xml file. Choose 'Endomondo -> Xml -> Read Workouts' or 'Read Workout Details'

# Disclaimer
These macros worked for me. Endomondo can easily change something on their website so these macros are not work anymore, so I offer no guarantee that it will work for you, too. You use this macros at your own risk. 
