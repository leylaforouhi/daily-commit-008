def celsius_to_fahrenheit(c):
    return (c * 9/5) + 32

if __name__ == "__main__":
    c = 25
    print(f"{c}°C is equal to {celsius_to_fahrenheit(c)}°F")
