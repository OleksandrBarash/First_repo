import random

def get_numbers_ticket(min, max, quantity):
    # Перевіряємо, чи параметри відповідають заданим обмеженням
    if not (1 <= min <= max <= 1000) or quantity > (max - min + 1) or quantity < 1:
        return []
    
    # Генеруємо унікальні випадкові числа
    numbers = random.sample(range(min, max + 1), quantity)
    
    # Сортуємо список чисел
    return sorted(numbers)
    