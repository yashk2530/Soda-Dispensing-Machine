# Soda-Dispensing-Machine
Microprocessor Design Project 
PROBLEM STATEMENT
Three different types of cool drinks can be dispensed by the machine. The cool drink is available in three different quantities: Small, Medium and Large. There are three buttons available to select the cool drink type and another three buttons to select quantity. The user selects the drink, the quantity and then presses a button labelled dispense. LEDs are available with each button. When a choice is made the corresponding LED glows and turns off when the dispensing is completed. There are three more LEDs available that are used to indicate when a particular type of cool drink is not available. The cost is Rs.5.00, Rs.10.0 and Rs15.0 respectively. There is a coin slot that accepts five rupee coins only. User can select type of cool drink, desired quantity and then drop the required number of coins. Each type of cool drink has its own dispenser. Based on the user’s choice of drink the corresponding outlet will be open. The quantity of drink dispensed has to be accurately monitored. The quantity of drink is based on user’s choice and the number of coins dropped in by the user.
ASSUMPTIONS
1. The 3 cold drinks come in 3 quantities each: small (100ml), medium(200ml), large(300ml) and the user can order only 1 drink at a time of selected type and size. All 3 tanks are 10cm (length) x 10cm (breadth) x 15cm (height), and the initial height of liquid in all tanks is 10cm (1 litre).
2. User selects desired drink from a list of 3 drinks and presses the corresponding button and likewise for the desired quantity; an LED is switched on, once a selection is made.
3. The coins are entered after pressing the dispense button.
4. If a user exceeds a time interval of 30 seconds after pressing dispense button, the system automatically resets. This applies to the coin sensor (pressure sensor for measuring the number of coins) as well. If 30 seconds are up
(before entering the required number of coins for the selected quantity of drink), then the inserted coin/s is/are automatically lost (if any entered).
5. If the number of coins inserted is more than what is required based on the user’s selection, drink is dispensed based on keypad selection and the excess coins are lost. If the user inserts less coin/s than what is/are required, then
the dispense LED does not glow hence no liquid will be dispensed and the coin/s will be lost.
6. The coin slot dimension is the same of the Indian 5 rupee coin (To prevent foreign currency and rupee coins of other dimensions).
7. The flow rate of soda from each tank is constant. If quantity of any of the drinks is not sufficient enough to fulfil the user’s choice, the insufficient LED will glow and user can change the type or size of the drink.
8. When dispensing, 100ml is dispensed in 5 seconds, 200ml in 10 seconds and 300ml in 15 seconds taking constant flow rate into consideration.
9. The Ultrasonic Sensor (HCSR 04) is used to detect the quantity of soda left in each of the tanks and also has an inbuilt visible insufficiency LED to indicate refill requirement.
