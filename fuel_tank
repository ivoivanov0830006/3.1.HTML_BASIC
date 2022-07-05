fuel_type = input()
quantity = float(input())
discount_card = input()
gasoline = 2.22
diesel = 2.33
gas = 0.93
discount_gasoline = 0.18
discount_diesel = 0.12
discount_gas = 0.08
final_gasoline = gasoline - discount_gasoline
final_diesel = diesel - discount_diesel
final_gas = gas - discount_gas
total_price = 0
if discount_card == "Yes":
    if fuel_type == "Gasoline":
        if quantity < 20:
            total_price = quantity * final_gasoline
        elif quantity <= 25:
            total_price = 0.92 * quantity * final_gasoline
        else:
            total_price = 0.9 * quantity * final_gasoline
    if fuel_type == "Diesel":
        if quantity < 20:
            total_price = quantity * final_diesel
        elif quantity <= 25:
            total_price = 0.92 * quantity * final_diesel
        else:
            total_price = 0.9 * quantity * final_diesel
    if fuel_type == "Gas":
        if quantity < 20:
            total_price = quantity * final_gas
        elif quantity <= 25:
            total_price = 0.92 * quantity * final_gas
        else:
            total_price = 0.9 * quantity * final_gas
else:
    if fuel_type == "Gasoline":
        if quantity < 20:
            total_price = quantity * gasoline
        elif quantity <= 25:
            total_price = 0.92 * quantity * gasoline
        else:
            total_price = 0.9 * quantity * gasoline
    if fuel_type == "Diesel":
        if quantity < 20:
            total_price = quantity * diesel
        elif quantity <= 25:
            total_price = 0.92 * quantity * diesel
        else:
            total_price = 0.9 * quantity * diesel
    if fuel_type == "Gas":
        if quantity < 20:
            total_price = quantity * gas
        elif quantity <= 25:
            total_price = 0.92 * quantity * gas
        else:
            total_price = 0.9 * quantity * gas
print(f"{total_price:.2f} lv.")


#Напишете програма, която да изчислява, колко ще струва на един шофьор да напълни резервоара на автомобила си, 
#като знаете – какъв тип гориво зарежда, каква е цената за литър гориво и дали разполага с карта за отстъпки. 
#Цените на горивата са както следва: 
#   Бензин – 2.22 лева за един литър, 
#   Дизел – 2.33 лева за един литър
#   Газ – 0.93 лева за литър
#Ако водача има карта за отстъпки,  той се възползва от следните намаления за литър гориво: 18 ст. за литър бензин,
#12 ст. за литър дизел и 8 ст. за литър газ. 
#Ако шофьора е заредил между 20 и 25 литра включително, той получава 8 процента отстъпка от крайната цена, 
#при повече от 25 литра гориво, той получава 10 процента отстъпка от крайната цена.
#Вход
#Входът се чете от конзолата и се състои от 3 реда:
#Типа на горивото – текст с възможности: "Gas", "Gasoline" или "Diesel"
#Количество гориво – реално число в интервала [1.00 … 50.00]
#Притежание на клубна карта – текст с възможности: "Yes" или "No"
#Изход
#На конзолата трябва да се отпечата един ред.
#"{крайната цена на горивото} lv."
#Цената на горивото да бъде форматираната до втората цифра след десетичния знак.
#Вход	        Изход	            
#Gas            22.95 lv.
#30
#Yes
#--------------------------------
#Gasoline       51.06 lv.
#25
#No
#--------------------------------
#Diesel         44.27 lv
#19
#No
