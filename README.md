# translate
Переводчик (оффлайн) с арабского языка на татарский.
from googletrans import Translator

translator = Translator()

text = input('введите текст: ')
result = translator.translate('text', src='tr', dest='arab')

print(result)
