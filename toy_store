holiday = float(input())
count_puzzle = int(input())
count_doll = int(input())
count_bear = int(input())
count_minion = int(input())
count_truck = int(input())
price_puzzle = 2.6
price_doll = 3
price_bear = 4.1
price_minion = 8.2
price_truck = 2
rest = 0
needed = 0
total = 0
total_earn = price_puzzle * count_puzzle + price_doll * count_doll + \
             price_bear * count_bear + price_minion * count_minion + \
             price_truck * count_truck
total_count = count_puzzle + count_doll + count_bear + count_minion + count_truck
if total_count >= 50:
    total = total_earn - (0.25 * total_earn)
    rent = 0.1 * total
    total = total - rent
    if total >= holiday:
        rest = total - holiday
        print(f"Yes! {rest:.2f} lv left.")
    else:
        needed = holiday - total
        print(f"Not enough money! {needed:.2f} lv needed.")
elif total_count < 50:
    total = total_earn
    rent = 0.1 * total
    total = total_earn - rent
    if total >= holiday:
        rest = total - holiday
        print(f"Yes! {rest:.2f} lv left.")
    else:
        needed = holiday - total
        print(f"Not enough money! {needed:.2f} lv needed.")
        
       
#Петя има магазин за детски играчки. Тя получава голяма поръчка, която трябва да изпълни. 
#С парите, които ще спечели иска да отиде на екскурзия. 
#Цени на играчките:
#⦁	Пъзел - 2.60 лв.
#⦁	Говореща кукла - 3 лв.
#⦁	Плюшено мече - 4.10 лв.
#⦁	Миньон - 8.20 лв.
#⦁	Камионче - 2 лв.
#Ако поръчаните играчки са 50 или повече магазинът прави отстъпка 25% от общата цена. 
#От спечелените пари Петя трябва да даде 10% за наема на магазина. 
#Да се пресметне дали парите ще ѝ стигнат да отиде на екскурзия.
#Вход
#От конзолата се четат 6 реда:
#⦁	Цена на екскурзията - реално число в интервала [1.00 … 10000.00]
#⦁	Брой пъзели - цяло число в интервала [0… 1000]
#⦁	Брой говорещи кукли - цяло число в интервала [0 … 1000]
#⦁	Брой плюшени мечета - цяло число в интервала [0 … 1000]
#⦁	Брой миньони - цяло число в интервала [0 … 1000]
#⦁	Брой камиончета - цяло число в интервала [0 … 1000]
#Изход
#На конзолата се отпечатва:
#⦁	Ако парите са достатъчни се отпечатва:
#⦁	"Yes! {оставащите пари} lv left."
#⦁	Ако парите НЕ са достатъчни се отпечатва:
#⦁	"Not enough money! {недостигащите пари} lv needed."
#Резултатът трябва да се форматира до втория знак след десетичната запетая.
#
#Вход             Изход
#40.8             Yes! 418.20 lv left.
#20
#25
#30
#50
#10
#--------------------------------------------------
#320              Not enough money! 238.73 lv needed.
#8
#2
#5
#5
#1
