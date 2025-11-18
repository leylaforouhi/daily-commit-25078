def separate_even_odd(number):
    evens = [n for n in numbers if n % 2 == 0]
    odds = [n for n in numbers if n % 2 != 0]
    return evens, odds

if __name__ == "__main__":
    nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    evens, odds = separate_even_odd(nums)
    print(f"Evens: {evens}")
    print(f"Odds: {odds}")
