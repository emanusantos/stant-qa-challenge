# Stant QA Challenge

Repository destined to the technical challenge of the selective proccess for Quality Assurance Jr.

The 3 given applications were treated with the BDD (Behavior-Driven Development) method and then followed some test steps that I designed.

Here's the applications and its rules:

## Application 01 - Life Period

A function that converts an age into a life period. These rules must be followed:

<ul>
  <li>If the age is 0, it should return 'INVALID';</li>
  <li>If the age is greater than 0 and less than 16, it should return 'CHILD';</li>
  <li>If the age is greater or equal to 16 and less than 60, it should return 'ADULT';</li>
  <li>If the age is greater than 60, it should return 'AGED';</li>
</ul>

<hr>

## Application 02 - Thermostat

A software that controls a switch to turn the heaters of a thermostat. These rules must be followed:

<ul>
  <li>If the temperature is greater or equal to 23 °C, the heater should turn off;</li>
  <li>If the temperature is less than 5 °C, the heater should turn on;</li>
</ul>

<hr>

## Application 03 - Interest rate calculator

An interest rate calculator that gets age and deposit value as arguments and then returns an interest rate

<ul>
  <li>Only adults (18 years or older) can make deposits;</li>
  <li>Clients with an age greater than 60 have an fixed interest rate in 2.0%;</li>
  <li>The minimum deposit value is R$100,00;</li>
  <li>The maximum deposit value is R$10.000,00;</li>
  <li>The interest rate depends on the deposited value. For more information, check the Application 03 file in this repository.</li>
</ul>
