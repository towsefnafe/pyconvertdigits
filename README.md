PYCONVERTDIGITS
===================


**PyConvertdigits** is a module that helps you to translate digits from English to other languages. 

----------

Features
===================

> - Conver English int to other languages and return a string

Install
===================
We recommend install pyconvertdigits through pip install using Python 3.

> $ pip install pyconvertdigits

Example
===================

To see available languages:

    import pyconvertdigits
    convertDigits = pyconvertdigits.conDigits()
    languages = convertDigits.available()
    print(languages)
    #output: ['Bangla', 'Hindi', 'Urdu', 'Malayalam', 'Thai']
To convert English to other languages:

    import pyconvertdigits
    convertDigits = pyconvertdigits.conDigits()

    convertedBangla = convertDigits.to_bangla(1234567890) #convert from English to Bangla
    print(convertedBangla)

    convertedHindi = convertDigits.to_hindi(1234567890) #convert from English to Hindi
    print(convertedHindi)

    convertedUrdu = convertDigits.to_urdu(1234567890) #convert from English to Urdu
    print(convertedUrdu)

    convertedMalayalam = numbers.to_malayalam(1234567890) #convert from English to Urdu
    print(convertedMalayalam)

    convertedThai = numbers.to_thai(1234567890) #convert from English to Urdu
    print(convertedThai)