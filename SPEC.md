# Overview
This project calculates the user's BMI, taking into consideration the region they are in, and outputting their BMI itself plus a category label (see below for details)

# Unit differences
If the user's IP address is an American one, display two boxes for height (feet and inches), plus a box for weight (in pounds).
For any other IP address or an unknown IP address, display one box for height (in meters) and one box for weight (in kilograms)
Have each box's units labelled for the user.

# Mathematical details
The ranges are as follows (BMI is the calculated score):
BMI < 18.5: underweight
18.5 <= BMI < 25: normal weight
25 <= BMI < 30: overweight
30 <= BMI < 40: obsese
40 <= BMI: morbidly obese

However, if the user's IP address is in Japan, China, Hong Kong, Taiwan, Singapore, or South Korea, use the following categories:
BMI < 18.5: underweight
18.5 <= BMI < 25: normal weight
25 <= BMI < 30: overweight class I
30 <= BMI < 40: overweight class II
40 <= BMI: overweight class III

# Display details
For the class label, use the following colors:
0x004499 (blue) for underweight, white text
0x00AA33 (green) for normal weight, white text
0xFFFF00 (yellow) for overweight, black text
0xAA0000 (red) for obsese, white text
0x770077 (violet) for morbidly obese, white text

For the East Asian IP addresses, display the same colors (but different actual text) as you would for the normal ranges.
