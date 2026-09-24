[ENG]
This is an implemented aQDMC algorithm that operates based on a predictive model in the form of a step response – a numerical version of the classical DMC algorithm. The implementation uses a gradient algorithm to adapt the parameters of the predictive model in the form of an impulse response, which is then modified to obtain the required step response. The optimization problem is solved using the Hildreth algorithm. It is a multivariable version supporting 4 inputs and 3 outputs. It was used to control a plant consisting of a nonlinear three-tank cascade. The implementation was based on the use of a Scheduler framework, designed to control the load on the controller during each operating cycle.

Key parameters:
prediction horizon - 20,
control horizon - 1,
sampling time - 8 s.

[PL]
Jest to zaimplementowany algorytm aQDMC opierający swoje działanie na modelu predykcyjnym w postaci odpowiedzi skokowej - wersja numeryczna klasycznego algorytmu DMC. W implementacji wykorzystano algorytm gradientowy do adaptacji parametrów modelu predykcyjnego w postaci odpowiedzi impulsowej, która następnie ulegała modyfikacjom, tak aby uzyskać potrzebną odpowiedź skokową. Zagadnienie optymalizacji jest rozwiązywane przy wykorzystaniu algorytmu Hildretha. Wersja wielowymiarowa obsługująca 4 wejścia/3 wyjścia. Posłużył on do sterowania obiektu w postaci nieliniowej kaskady trzech zbiorników. Implementacja opierała się na wykorzystaniu frameworku Schedulera - przeznaczonego do kontrolowanego obciążania sterownika w każdym cyklu jego pracy.

Kluczowe parametry:
horyzont predykcji - 20,
horyzont sterowania - 1,
czas próbkowania - 8 s.
