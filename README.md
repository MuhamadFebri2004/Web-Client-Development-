# Web-Client-Development-
Tugas Web Client Development 



function rectangleArea(length, width) {
    return length * width;
}
console.log(rectangleArea(5, 3)); // Output: 15

function circleProperties(radius) {
    let diameter = 2 * radius;
    let circumference = 2 * Math.PI * radius;
    let area = Math.PI * radius * radius;
    return { diameter, circumference, area };
}
console.log(circleProperties(5)); // Output: diameter = 10, circumference ≈ 31.4159, area ≈ 78.539


function thirdAngle(a, b) {
    return 180 - (a + b);
}
console.log(thirdAngle(80, 65)); // Output: 35


function dateDifference(date1, date2) {
    let d1 = new Date(date1);
    let d2 = new Date(date2);
    return Math.abs((d2 - d1) / (1000 * 60 * 60 * 24));
}
console.log(dateDifference("2024-03-19", "2024-03-21")); // Output: 2


function nameInitials(name) {
    return name.split(" ").map(n => n[0].toUpperCase()).join("");
}
console.log(nameInitials("John Doe")); // Output: JD
