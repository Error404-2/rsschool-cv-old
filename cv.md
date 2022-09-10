23:45 10/09/22 from local VSCode 
Vas Kast
@kastvs (telegram)
Закрываю свой гештальт - стать программистом. Пробую себя во фронтенде и бэкенде. Получаю удовольствие от обучения новому, поэтому IT это то направление, с которым я хочу связать своё будущее. Опыт работы в продажах 15 лет, карьера от менеджера до коммерческого директора. Внедрил ряд проектов (выход на новые рынки, развитие взаимоотношений с ключевыми клиентами, вывод новой продукции, выход напрямую на поставщиков-производителей, оптимизация ассортиментной линейки, переход на комплексную автоматизацию учёта, внедрение системы менеджмента качества), периодически пересекался и с разработчиками но в качестве заказчика, составлял ТЗ, корректировал работу исполнителей. 
Python (основы, ООП), github (основы)

Примеры кода на Python
class Box:

    def __init__(self):
        self.__box = []
        pass

    def add_thing(self, *obj):
        for piece in obj:
            self.__box.append(piece)

    def get_things(self):
        return self.__box

    def __eq__(self, other):
        if not isinstance(other, Box):
            raise TypeError("Неверный формат")
        if self.__box.sort() == other.__box.sort():
            return True
        else:
            return False


class Thing:

    def __init__(self, name, mass):
        self.__name = name
        self.__mass = mass

    def __eq__(self, other):
        if not isinstance(other, Thing):
            raise TypeError("Неверный формат")
        if self.__name.lower() == other.__name.lower() and self.__mass == other.__mass:
            return True
        else:
            return False

b1 = Box()
b2 = Box()
print (b1, b2)
cup = Thing('кружка', 150)
soap = Thing('мыло', 100)
brush = Thing('щётка', 50)
teapot = Thing('чайник', 500)
teapot2 = Thing('чайник', 500)
print(teapot==teapot2, teapot!=cup, soap==brush)
b1.add_thing(cup)
b2.add_thing(cup)
print(b1==b2)

https://www.codewars.com/users/Error404-2

Опыта в разработке пока нет, добавил только несколько строчек в телеграмм-бота в чужом репозитории. Прохожу курсы на степике. 

Образование. Высшее экономическое. СПбГУЭФ. Master of Science "Wirtschaftswissenschaft", Fernuniversitaet Hagen, Deutschland. Курсы Сергея Балакирева по Python на stepik.org. 
Немецкий язык (в стадии "консервации" из-за отсутствия практики, ранее владел свободно) 
Английский язык (самостоятельное изучение, А2+ согласно тесту https://test.str.by/, могу немного говорить, понимать устную речь, написанное на английском - понимаю суть без словаря, отдельные словаря перевожу. Опыт переписки с китайским поставщиком по проектированию, разработке и поставке оборудования.
