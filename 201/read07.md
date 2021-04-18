# TABLES

A table represents information in a grid format. 

**Examples of tables include financial:** reports, TV schedules, and sports results.
Grids allow us to understand complex data by referencing information on two axes .

### Basic Table Structure

> <table> to create the table

> <tr> to indicate row

> <td> to inter table data

> <th> like <td> but this one for heading

### Long Tables

> <thead> the head

> <tbody> the body of table

> <tfoot> the footer of table

## CREATING AN OPJECT :

### CONSTRUCTOR NOTATION

the new keyword and the opject constuctor creat a blank opjects
you can add roperties and method to the opject

**example :**
``
var hotel = opject() ;
hotel.name = 'Quay';
hotel.rooms=40;
hotel.booked= 25;
hotel.chckAvailability = function(){
return this.rooms - this.booked ;
};
``

***to update the value of properties we use dot like :***

hotel.booked=30;

***to delete properties we use delete keyword like :***
delete hotel.rooms;

***if we want to create many opjects using constructor function like :***

``
function hotel (name , rooms , booked){
this .name = name ;
this . rooms = rooms ;
this .booked = booked ;
this . checkAvailability = function(){
return this.rooms - this.booked ;
}
}
``

***then creating opjects by this function :***

``
var quayHotel = new hotel ('quay',40,25);
var parkHotel = new hotel('park',50,30);
``

## ARRAYS ARE OPJECTS

arrays are actually special type of opject , they hold related set of value/key pairs (like all opject) but the key for each value is its index number

**arrays in and opject :**

the property of any opjects can hold an array

**opjects in an array:**

the value of any element in an array can be an opject
