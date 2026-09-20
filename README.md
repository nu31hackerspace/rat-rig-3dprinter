# Інформацію про RatRig V-core 3 Хакерспейсу NU31 в Києві

Адреса принтера [http://ratos.local/](ratos.local)

# Потрібні файли для RatRig в NU31

- [NU31 RatRig 200.json](Файл налштувань принтера для OrcaSliser)
- [printer.cfg](Файл налштувань самого RatRig, трішки відрізняється від того що генерує RatOs wizard)

## Відміності в файлі printer.cfg

Деякі зміни в файлі printer.cfg зроблені руками через те що wizard не підтримує шпильки

```cfg 
rotation_distance: 8      # 4 for TR8*4 lead screws
```

Висталено в 8, тому що в нас однозахідна різьба, значення від wizard 4, тому що про стандарту RatRig використовує двозахідну різьбу


