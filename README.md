# Ex03 Time Table
## Date:

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
<html>
<head>
    <title>Slot Time Table</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 p-4">
    <div class="max-w-4xl mx-auto bg-white p-4 border border-gray-300">
        <h1 class="text-center text-xl font-bold mb-4">SLOT TIME TABLE - SAMEER (24900559)</h1>
        <table class="w-full border-collapse border border-gray-400 mb-4">
            <thead>
                <tr>
                    <th class="border border-gray-400 p-2 bg-purple-300">Day/Time</th>
                    <th class="border border-gray-400 p-2 bg-purple-300">Monday</th>
                    <th class="border border-gray-400 p-2 bg-purple-300">Tuesday</th>
                    <th class="border border-gray-400 p-2 bg-purple-300">Wednesday</th>
                    <th class="border border-gray-400 p-2 bg-purple-300">Thursday</th>
                    <th class="border border-gray-400 p-2 bg-purple-300">Friday</th>
                    <th class="border border-gray-400 p-2 bg-purple-300">Saturday</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="border border-gray-400 p-2 bg-purple-300">8-10</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">WEB</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2 bg-purple-300">10-12</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">EVS</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">COMPUTER ARCHITECTURE</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">EDM</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">C PROGRAM</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">WEB</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2 bg-purple-300">12-1</td>
                    <td colspan="6" class="border border-gray-400 p-2 bg-red-300 text-center">L U N C H</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2 bg-purple-300">1-3</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">C PROGRAM</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">PROBABILITY</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">MENTOR</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">PROBABILITY</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">EDM</td>
                    
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2 bg-purple-300">3-5</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">COMPUTER ARCHITECTURE</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                    <td class="border border-gray-400 p-2 bg-cyan-300">FREE SLOT</td>
                </tr>
            </tbody>
        </table>
        <table class="w-full border-collapse border border-gray-400">
            <thead>
                <tr>
                    <th class="border border-gray-400 p-2 bg-gray-200">S. No.</th>
                    <th class="border border-gray-400 p-2 bg-gray-200">Subject Code</th>
                    <th class="border border-gray-400 p-2 bg-gray-200">Subject Name</th>
                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="border border-gray-400 p-2">1.</td>
                    <td class="border border-gray-400 p-2">19AI414</td>
                    <td class="border border-gray-400 p-2">Fundamentals of Web Application Development (FWAD)</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2">2.</td>
                    <td class="border border-gray-400 p-2">19AI302</td>
                    <td class="border border-gray-400 p-2">ENGINEEERING MECHANICS AND DEVELOPMENT (EDM)</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2">3.</td>
                    <td class="border border-gray-400 p-2">19AI304</td>
                    <td class="border border-gray-400 p-2">FUNDAMENTALS OF C PROGRAMMING (C)</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2">4.</td>
                    <td class="border border-gray-400 p-2">19HS801</td>
                    <td class="border border-gray-400 p-2">PROBABILITY AND QUELEING MATRIX (PB)</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2">5.</td>
                    <td class="border border-gray-400 p-2">19AI303</td>
                    <td class="border border-gray-400 p-2">ENGINEEERING MECHANICS AND PRODUCT DEVELOPMENT (EMPD)</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2">6.</td>
                    <td class="border border-gray-400 p-2">19CS305</td>
                    <td class="border border-gray-400 p-2">COMPUTER ARCHITECTURE (CA)</td>
                </tr>
                <tr>
                    <td class="border border-gray-400 p-2">7.</td>
                    <td class="border border-gray-400 p-2">19CY801</td>
                    <td class="border border-gray-400 p-2">ENVIRONMENTAL SCIENCE AND SUSTAINABILITY (EVS)</td>


                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
                
            


## OUTPUT
![Screenshot 2025-03-13 094831](https://github.com/user-attachments/assets/00c42165-1ec0-4f6f-b33e-baa077d31031)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
