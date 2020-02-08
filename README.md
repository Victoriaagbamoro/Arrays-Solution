# Arrays-Solution
Arrays Solution
// QUICK SIMPLE ASSIGNMENT
1.
// We have the following arrays
// color = ["Blue ", "Green", "Red", "Orange", "Violet", "Indigo", "Yellow "];

// o = ["th","st","nd","rd"]

// Write a JavaScript program to display the colors in the following way :
// "1st choice is Blue."
// "2nd choice is Green."
// "3rd choice is Red."

// SOLUTION 1-

let color = ['Blue', 'Green', 'Red', 'Orange', 'Violet', 'Indigo', 'Yellow'];

    console.log(' "1st Choice is" ' + color[0] + '.');
    console.log(' "2nd Choice is" ' + color[1] + '.');
    console.log(' "3rd Choice is" ' + color[2] + '.');
    console.log(' "4th Choice is" ' + color[3] + '.');
    console.log(' "5th Choice is" ' + color[4] + '.');
    console.log(' "6th Choice is" ' + color[5] + '.');
    console.log(' "7th Choice is" ' + color[6] + '.');



    // 2.
    // Write a simple JavaScript program to join all elements of the following array into a string. Go to the editor
    // Sample array : myColor = ["Red", "Green", "White", "Black"];
    // Expected Output :
    // "Red,Green,White,Black"
    // "Red,Green,White,Black"
    // "Red+Green+White+Black"
    
    // SOLUTION 2-

    myColor = ["Red", "Green", "White", "Black"];
    console.log(myColor.join());
    console.log(myColor.join(","));
    console.log(myColor.join('+'))

    3.
    employees = [
    {
        id: 1,
        first_name: 'Nestor',
        email: 'nede0@va.gov',
        gender: 'Male',
        age: 35,
        ip_address: '80.95.217.202',
        Car: 'Chevrolet',
        Country: 'Russia',
        Company: 'Ozu',
        Job: 'Research Associate',
        Language: 'Kannada',
        phone: '369-416-1791',
        active: true,
        salary: 350000
    },
    {
        id: 2,
        first_name: 'Boony',
        email: 'bconsidine1@dailymail.co.uk',
        gender: 'Male',
        age: 30,
        ip_address: '158.108.174.143',
        Car: 'Kia',
        Country: 'Indonesia',
        Company: 'Flashspan',
        Job: 'Engineer IV',
        Language: 'Bosnian',
        phone: '878-260-8542',
        active: true,
        salary: 150000
    },
    {
        id: 3,
        first_name: 'Humfrid',
        email: 'hmacaree2@craigslist.org',
        gender: 'Male',
        ip_address: '13.121.145.193',
        age: 25,
        Car: 'Dodge',
        Country: 'China',
        Company: 'Mita',
        Job: 'Web Designer',
        Language: 'Bosnian',
        phone: '721-765-6270',
        active: true,
        salary: 550000
    },
    {
        id: 4,
        first_name: 'Hirsch',
        email: 'halbury3@themeforest.net',
        gender: 'Male',
        age: 21,
        ip_address: '154.153.161.16',
        Car: 'Dodge',
        Country: 'Russia',
        Company: 'Kaymbo',
        Job: 'Software Consultant',
        Language: 'Northern Sotho',
        phone: '515-581-1165',
        active: true,
        salary: 250000.08
    },
    {
        id: 5,
        first_name: 'Granny',
        email: 'gmcsharry4@buzzfeed.com',
        gender: 'Male',
        age: 23,
        ip_address: '171.48.242.209',
        Car: 'Ford',
        Country: 'China',
        Company: 'Youtags',
        Job: 'Senior Quality Engineer',
        Language: 'Swedish',
        phone: '757-973-8706',
        salary: 300000.05,
        active: true
    },
    {
        id: 6,
        first_name: 'Bob',
        email: 'bbortolomei5@stanford.edu',
        gender: 'Male',
        age: 19,
        ip_address: '138.88.133.136',
        Car: 'Honda',
        Country: 'Poland',
        Company: 'Vipe',
        Job: 'Web Designer',
        Language: 'Aymara',
        phone: '227-946-1788',
        active: true,
        salary: 100000
    },
    {
        id: 7,
        first_name: 'Chen',
        email: 'cyurshev6@wikipedia.org',
        gender: 'Male',
        age: 20,
        ip_address: '76.98.240.178',
        Car: 'Audi',
        Country: 'Thailand',
        Company: 'Midel',
        Job: 'Web Designer',
        Language: 'Malagasy',
        phone: '361-127-0004',
        active: false,
        salary: 300000
    },
    {
        id: 8,
        first_name: 'Jacquetta',
        email: 'jtretwell7@macromedia.com',
        gender: 'Female',
        age: 28,
        ip_address: '125.157.172.237',
        Car: 'Ford',
        Country: 'Russia',
        Company: 'Devpoint',
        Job: 'Web Developer',
        Language: 'Papiamento',
        phone: '542-329-7755',
        active: false,
        salary: 130000
    },
    {
        id: 9,
        first_name: 'Marget',
        email: 'msooley8@nba.com',
        gender: 'Female',
        age: 30,
        ip_address: '231.239.40.29',
        Car: 'Pontiac',
        Country: 'Nigeria',
        Company: 'Photobean',
        Job: 'Web Developer',
        Language: 'Hebrew',
        phone: '502-799-5098',
        active: false,
        salary: 750000.5
    },
    {
        id: 10,
        first_name: 'Tomkin',
        email: 'tkohtler9@howstuffworks.com',
        gender: 'Male',
        age: 17,
        ip_address: '121.234.135.93',
        Car: 'Pontiac',
        Country: 'Nigeria',
        Company: 'Jaxbean',
        Job: 'Database Administrator',
        Language: 'Filipino',
        phone: '692-372-4141',
        active: false,
        salary: 50000
    }
]


//   a.) => Return a new array with those employees that are web developers
// SOLUTION 1
// Here array.values() function is called. 
var employeesJob = employees.values();
  
// Here specific elements of the array is being printed. 
    if (employeesJob = employees) {
        // do some array stuff 
        console.log(employeesJob[7]);
        console.log(employeesJob[8]);
        
    }

//   b.) => Return a new array with those employees that are both web developers and from Nigeria
var webDevelopersNotNigeria = employees.values();

if(webDevelopersNotNigeria = employees){
   console.log(webDevelopersNotNigeria[7]);
}

//   c.) => Return a new array with those employees below 20
var employeesBelow20 = employees.values();

if(employeesBelow20 = employees){
    console.log(employeesBelow20[9]);
    console.log(employeesBelow20[5]);
    console.log(employeesBelow20[6]);
}
//   d.) => Return a new array with those employees that are active


function activeEmployees(){
    if(activeEmployee = employees){
        console.log(activeEmployee[0])
        console.log(activeEmployee[1])
        console.log(activeEmployee[2])
        console.log(activeEmployee[3])
        console.log(activeEmployee[4])
        console.log(activeEmployee[5])
    }   
}
activeEmployees();

//   e.) => Find the highest paid developer

var highestPaidSalary = employees.values();
if(highestPaidSalary = employees){
console.log(highestPaidSalary[8]);
};


