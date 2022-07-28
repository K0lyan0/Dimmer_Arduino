# Dimmer_Arduino
Диммер на базе Ардуино, Moc3020, PC814, BTA12-600.  Основан на https://github.com/AlexGyver/AC_Dimmer

R1 - 370 ом. Ресистор для ограничения по току светодиода для оптопары Moc3020.
Рассчет: VF Input Forward Voltage от 1.15 вольта до 1.50 вольта, при токе IF = 10 mA. Отсюда: (5 вольт -1.15 вольта) / 0.01 милиампера = 385 ом. Брал 470 Ом. При напряжении в 5 вольт, на оптопару поступало 1.17 вольта.
Плане исходный данных брал из даташита на MOC3010M, MOC3011M, MOC3012M, MOC3020M, MOC3021M, MOC3022M, MOC3023M 6-Pin DIP Random-Phase Triac Driver Output Optocoupler (250/400 Volt Peak) Fairchild.
