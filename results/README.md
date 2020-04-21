# Описание проекта

Лабораторная работа Lab SCR1 sim

## Вариант задания

№ Варианта | Вид исключения | Тест | Reset Vector | Trap Vector | При обработке
---------- | -------------- | ---- | ------------ | ----------- | ------------
7 | Environment call from M-mode | isa/rv32mi/scall.S | 0xB000 | 0xA880 | Вывод строки «envcall»

## Результаты работы

* ./results/test_results.txt - результат симуляции
* ./results/ma_addr.dump - дамп теста
* ./results/trace_mprf_diff_.log - трейслог MPRF
* ./results/trace_csr_.log - трейслог CSR