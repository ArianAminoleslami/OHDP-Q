**How to run the EHR's data harmonization app using an existing variable details sheet**

1. Run the app, choose large pipe-delimited CSV's, Multiple, and .sqlite (as shown in the picture).
2. item Add the path to the folder where your original file/files are located.
3. item Add a path to a desired .sqlite database (you don't need to create the database, the app does that automatically and you only need to put .sqlite extension at the end of the path.)

![1](https://github.com/ArianAminoleslami/OHDP-Q/assets/137816738/05553d72-bd3b-4502-a678-44fa05dfadbc)

4. In the "variable details sheet" tab, upload your existing variable details sheet.

<img width="877" alt="2" src="https://github.com/ArianAminoleslami/OHDP-Q/assets/137816738/e756a6b1-7fa6-4ce7-8eb3-4564a55151df">

5. Make sure to add the database name of your existing details sheet in the top box of the sidebar panel.
6. To add an existing derived variable from the Derived Variables Library (DVL), add the path to the library (a .csv file), and select your preferred derived variables, add to the table and update your existing details sheet.

![3](https://github.com/ArianAminoleslami/OHDP-Q/assets/137816738/c9e16328-7dc7-413b-a182-fbc683d142a4)

7. Finally, in the "Recodeflow" tab, adjust the chunk size (number of rows that are imported, recoded, and stored) considering your avalable memory, and click on the "Recode the dataset!" button. 
