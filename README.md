# Пакування та Публікація
    pip install setuptools wheel twine.
Перейдіть в каталог бібліотеки.

    cd InfoTest

### Створіть дистрибуцію
Відкрийте термінал і перейдіть до кореневої директорії вашого проекту.  
Ця команда створять архівні файли дистрибуції вашого пакету.

    python setup.py sdist bdist_wheel

### Опублікуйте пакет
Якщо ви хочете опублікувати свій пакет на Python Package Index (PyPI), використовуйте інструмент twine. 
Спершу встановіть його:

    pip install twine
    twine upload --repository pypi dist/*