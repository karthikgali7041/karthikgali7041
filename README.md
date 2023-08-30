import phonenumbers
from phonenumbers import geocoder
phone_number1 = phonenumbers.parse("+919912969660")
phone_number2 = phonenumbers.parse("+917780387945")
phone_number3 = phonenumbers.parse("+916303390114")
phone_number4 = phonenumbers.parse("+1(314)655-8495")
print("\nphone numbers location\n")
print(geocoder.description_for_number(phone_number1,"en"))
print(geocoder.description_for_number(phone_number2,"en"))
print(geocoder.description_for_number(phone_number3,"en"))
print(geocoder.description_for_number(phone_number4,"en"))
