# Dymohod
Расчет дымохода по шведской формуле
По заданным высоте и площади помещения расчитаем требуемую конструкцию дымохода.
h - высода здания (м),
S - площадь здания (кв. м),
По шведской формуле 3 объема помещения со скоростью V = 1,5 м/сек должны покинуть помещение
через дымоход за 1 час.
Тогда производительность дымохода Q = 3 * S * h (куб. м / час).
Значит сечение дымохода F = Q / (3600*V) (кв. м).
С учетом, что на каждые 50 кв. м площади помещения по СНИПу должна быть
минимум 1 труба дымохода, определим число труб:
N = INT(S / 50) + 1.
Следовательно площадь одной трубы Sтр = S / N.
Отсюда диаметр трубы d = sqr (4 * Sтр / pi), где pi = 3,141549...
