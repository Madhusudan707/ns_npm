![npm(scoped)](https://img.shields.io/badge/Github-https%3A%2F%2Fgithub.com%2FMadhusudan707%2Fns__npm-blue)
![npm(scoped)](https://img.shields.io/badge/npm%20package-1.0.0-green)
![npm(scoped)](https://img.shields.io/badge/Twitter-https%3A%2F%2Ftwitter.com%2Fxdev__200-blue)
# Number System Convertor

> A number system conversion library. Supports binary, octal, decimal and hexadecimal

## Installation

$ npm install --save @xdev200/number-system-converter

## Usage

const number_system = require('@xdev200/number-system-converter')

1.Binary To Decimal | Binary To Octal | Binary To HexaDecimal

    let resultB2D = number_system.BinaryToDecimal("1011",2)
    let resultB2O = number_system.BinaryToOctal("1011",2)
    let resultB2HD = number_system.BinaryToOctal("1011",2)


2.Decimal To Binary | Decimal To Octal | Decimal to HexaDecimal

    let resultD2B = number_system.DecimalToBinary_Octal_hexaDecimal("25",2)
    let resultD2O = number_system.DecimalToBinary_Octal_hexaDecimal("25",8)
    let resultD2HD = number_system.DecimalToBinary_Octal_hexaDecimal("25",16)


3.Octal To Binary | Octal To Decimal  | Octal to HexaDecimal

    let resultO2B = number_system.DecimalToBinary_Octal_hexaDecimal(number_system.BinaryToDecimal("17",8),2)
    let resultO2D = number_system.BinaryToDecimal("17", 8)
    let resultO2HD = number_system.DecimalToBinary_Octal_hexaDecimal(number_system.BinaryToDecimal("17",8),16)


4.HexaDecimal To Binary | HexaDecimal To Decimal | HexaDecimal to  Octal

    let resultHD2B = number_system.DecimalToBinary_Octal_hexaDecimal(number_system.hexadecimalToBinary("1C",16),2)
    let resultHD2D = number_system.hexadecimalToBinary("1C",16)
    let resultHD2O = number_system.DecimalToBinary_Octal_hexaDecimal(number_system.hexadecimalToBinary(hexadecimal,16),8)