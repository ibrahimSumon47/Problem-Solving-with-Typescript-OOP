Explain how Access Modifiers work in TypeScript

Access modifier is a important part of OOP. Which also can be used in TypeScript. There are 3 type main access modifier which is public, private and protected.

Public is a default access modifier. Which can be used anywhere on properties and methods.

Private can only used in own class. It can't be used outside of it's class

Protected method can used only it's own class and it's own subclass. It can't be used on outside of it class.

Readonly can be assigned a value inside the constructor. After install it can't be reused.

For better understant we used this example

class Employee {
public email: string;
private salary: number;
protected name: string;
readonly employeeId: number;

    constructor(
        name: string;
        email:string;
        salary:number;
        employeeId: number
    ){
        this.name=name;
        this.email=email;
        this.salary=salary;
        this.employeeId=employeeId
    }

    public getSalary(): number{
        return this.salary;
    }

}

Here, email is publicly accessible, salary is private, name is protected, and employeeId cannot be reassigned after initialization.
