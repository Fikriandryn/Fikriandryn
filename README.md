clc; clear all;
x=input('Enter the values of independent variable x in an array: \n');
% x= [1:1:6]; % Write the values of independent variable x. 
y=input('Enter the values of independent variable y in an array: \n');
% y = [1 8 27 65 123 208]; % Write the values of independent variable y. 
xf=input('Enter the value of x where we want to find the value of(x):');
li=LagrangeI(x,y,xf);
