# Laundry Service Center

Welcome to the Laundry Service Center repository! This Python script calculates the total charge for laundry services based on customer inputs and provides an estimate of the expected day of return.



## Customer Input Details

- Name of customer [string]
- Contact of customer [integer]
- Email Alphanumeric [string]
- Type of cloth: "Cotton," "Silk," "Woolen," or "Polyester" [string]
- Branded: "0" for unbranded, "1" for branded [Boolean]
- Season: "Summer" or "Winter" [string]

## Charge Calculation

1. **Type of Cloth:**
    - Cotton → 50 Rs
    - Silk → 30 Rs
    - Woolen → 90 Rs
    - Polyester → 20 Rs

2. **Branded:**
    - If True, 1.5 times the charge from step 1. Otherwise, the charge is unchanged.

3. **Season:**
    - If "Winter," the charge is halved from step 2. Otherwise, the charge is two times the charge from step 2.

## Expected Day of Return

- If the total charge is greater than 200, it will print out "To be returned in 4 days."
- Otherwise, it will print out "To be returned in 7 days."

Feel free to contribute and improve the code. If you encounter any issues, please open an [issue](https://github.com/your-username/laundry-service-center/issues).

Happy laundry processing!
