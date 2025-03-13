# Ex03 Time Table
## Date: 13/3/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

### ELAIYAVAN (24900184)
```
<html>
 <head>
  <title>
   Time Table
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
 </head>
 <body style="color: black;">
  <div class="max-w-4xl mx-auto bg-white p-6 shadow-md">
   <div class="text-center mb-4">
    <h1 class="text-2xl font-bold">
     SAVEETHA AUTONOMOUS ENGINEERING COLLEGE
    </h1>
    <p class="text-sm">
     Approved by AICTE | Affiliated to Anna University
    </p>
    <p class="text-lg font-bold mt-2">
     TNEA CODE 1216
    </p>
   </div>
   <h2 class="text-center text-xl font-bold mb-4">
    SLOT TIME TABLE - Elaiyavan(24900184)
   </h2>
   <table class="w-full border-collapse border border-gray-400 mb-4">
    <thead>
     <tr>
      <th class="border border-gray-400 bg-blue-400 p-2">
       Day/Time
      </th>
      <th class="border border-gray-400 bg-blue-400 p-2">
       Monday
      </th>
      <th class="border border-gray-400 bg-blue-400 p-2">
       Tuesday
      </th>
      <th class="border border-gray-400 bg-blue-400 p-2">
       Wednesday
      </th>
      <th class="border border-gray-400 bg-blue-400 p-2">
       Thursday
      </th>
      <th class="border border-gray-400 bg-blue-400 p-2">
       Friday
      </th>
     </tr>
    </thead>
    <tbody>
     <tr>
      <td class="border border-gray-400 bg-blue-400 p-2">
       8-10
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FREE SLOT
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       PHY
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       CHE
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 bg-blue-400 p-2">
       10-12
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       GER
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FREE SLOT
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FWAD
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FWAD
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       PHY
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 bg-blue-400 p-2">
       12-1
      </td>
      <td class="border border-gray-400 bg-white-300 p-2 text-center" colspan="5">
       L U N C H
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 bg-blue-400 p-2">
       1-3
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FREE SLOT
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       MAT
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       MAT
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       SS
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 bg-blue-400 p-2">
       3-5
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FREE SLOT
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       GER
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       CHE
      </td>
      <td class="border border-gray-400 bg-white-300 p-2">
       FWAD
      </td>
     </tr>
    </tbody>
   </table>
   <table class="w-full border-collapse border border-gray-400">
    <thead>
     <tr>
      <th class="border border-gray-400 bg-gray-200 p-2">
       S. No.
      </th>
      <th class="border border-gray-400 bg-gray-200 p-2">
       Subject Code
      </th>
      <th class="border border-gray-400 bg-gray-200 p-2">
       Subject Name
      </th>
     </tr>
    </thead>
    <tbody>
     <tr>
      <td class="border border-gray-400 p-2">
       1.
      </td>
      <td class="border border-gray-400 p-2">
       19AI414
      </td>
      <td class="border border-gray-400 p-2">
       Fundamentals of Web Application Development (FWAD)
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 p-2">
       2.
      </td>
      <td class="border border-gray-400 p-2">
       19EN612
      </td>
      <td class="border border-gray-400 p-2">
       German Basic (GER)
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 p-2">
       3.
      </td>
      <td class="border border-gray-400 p-2">
       19PH206
      </td>
      <td class="border border-gray-400 p-2">
       Physics for Information Technology (PHY)
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 p-2">
       4.
      </td>
      <td class="border border-gray-400 p-2">
       19CY205
      </td>
      <td class="border border-gray-400 p-2">
       Principles of Chemistry in Engineering (CHE)
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 p-2">
       5.
      </td>
      <td class="border border-gray-400 p-2">
       19MA201
      </td>
      <td class="border border-gray-400 p-2">
       Calculus and Matrix Algebra (MAT)
      </td>
     </tr>
     <tr>
      <td class="border border-gray-400 p-2">
       6.
      </td>
      <td class="border border-gray-400 p-2">
       19EY701
      </td>
      <td class="border border-gray-400 p-2">
       Soft Skills (SS)
      </td>
     </tr>
    </tbody>
   </table>
  </div>
 </body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/f6c08963-a1be-4482-9d1c-e01175dae753)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
