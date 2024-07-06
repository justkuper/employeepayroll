# Employee Payroll Tracker Starter Code

Update 1 Added code to lines 7-17
const employees = [];
  let addEmployee = true;
  while (addEmployee) { 
    const firstName = prompt("Enter employee's first name:");
    const lastName = prompt("Enter employee's last name:");
    const salary = parseFloat(prompt("Enter employee's salary:"));
    employees.push({firstName, lastName, salary});
    addEmployee = confirm("Would you like to add another employee?");
  }
  return employees;
}

Update 2 Added code to lines 22-25
let totalSalary = 0;
  for (let i = 0; i < employeesArray.length; i++) {
    totalSalary += employeesArray[i].salary
}

Update 3 Added code to lines 36-38
  const randomIndex = Math.floor(Math.random() * employeesArray.length);
  console.log(employeesArray[randomIndex]);
}