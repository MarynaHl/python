from simpleicons.all import icons

# Get a specific icon by its slug as:

icons.get('[ICON SLUG]')

# For example:

icon = icons.get('simpleicons')

print(icon.**dict**)

"""
{
'title': 'Simple Icons',
'slug': 'simpleicons',
'hex': '111111',
'source': 'https://simpleicons.org/',
'svg': '<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">...</svg>',
'path': 'M12 12v-1.5c-2.484 ...',
'guidelines': 'https://simpleicons.org/styleguide',
'license': {
type: '...',
url: 'https://example.com/'
}
}
"""

xh = input("Enter Hours: "): Запитує введення користувача в консолі з повідомленням "Enter Hours: ", і зберігає введене значення у змінну xh.

xr = input("Enter Rate: "): Запитує введення користувача в консолі з повідомленням "Enter Rate: ", і зберігає введене значення у змінну xr.

xp = float(xh) \* float(xr): Перетворює введені значення з рядкового типу на числовий (float) і обчислює добуток xh і xr, зберігаючи результат у змінну xp.

print("Pay:", xp): Виводить результат, який збережено в xp, разом із текстовим повідомленням "Pay:". Зверніть увагу, що результат виводиться у вигляді числа з плаваючою точкою, оскільки ми використовуємо тип float. Якщо ви хочете вивести ціле число, ви можете використовувати int(xp) замість float(xp).
