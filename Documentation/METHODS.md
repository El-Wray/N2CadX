# Методы

На данный момент дизассмеблированы следующие методы:

* CADraw_Init (0x10001970) - основная экспортируемая функция из dll-библиотек.
* SetScreenVariables (0x10001000) - установка начальных значений для констант:
  * Ширина экрана (пиксель)
  * Высота экрана (пиксель)
  * Ширина внеэкранной поверхности (байт)
  * Высота внеэкранной поверхности (байт)
  * Прямоугольная область экрана (0, 0, 639, 479)  
