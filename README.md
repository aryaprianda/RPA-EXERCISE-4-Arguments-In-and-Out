1. Create a Sequence. Give it a name, ArgumentsInOutDemo
2. Drag and drop an Assign activity
3. Create 2 arguments of Integer Type. In_Num1, In_Num2 with the Direction IN
4. Create 1 argument of Integer Type. Out_Outcome with the Direction OUT
5. In the To field, put in the argument Out_Outcome
6. On the other side, put in In_Num1+In_Num2 
7. Save the File
8. Create another Sequence. Give it a name, ArgumentsInOutRunner
9. Create 3 integer variables with names intNum1, intNum2, intOutcome
7. Drag and Drop an Invoke Workflow File. Click the Folder Icon, search for ArgumentsInOutDemo.xaml
8. Click Import Arguments. Change the Value of In_Num1 to IntNum1
9. Change the Value of In_Num2 to intNum2.
10. Change the value of Out_Outcome to intOutcome
11. Close the dialog box
12. Drag and Drop a message box. Put in the value, intOutcome
13. Run the Process