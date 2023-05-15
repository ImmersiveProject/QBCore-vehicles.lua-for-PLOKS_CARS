# QBCore vehicles.lua-for-PLOKS_CARS
This is the code you need in order to have PLOKS_CARS made available at vehicle shops in your city.

All cars have beem organized by brand name and sorted into vehicle shops. Higher end cars are available at Luxury shop all others at PDM.
Cars prices were searched on Google for average pricing, please change the prices if you don't like them.


# Getting Started
Copy the contents of the vehicles.lua and paste it above  "--Compacts" in your qb-core/shared/vehicles.lua. </br>
All the vehicles are labeled by brand for easy finding and editing.


# You will need to the categories in your qb-vehicleshop/config.lua</br>

These go here for example.</br>
```
 ['Job'] = 'none', -- Name of job or none
        ['ShopLabel'] = 'Luxury Vehicle Shop',
        ['showBlip'] = false, -- true or false
        ['blipSprite'] = 326, -- Blip sprite
        ['blipColor'] = 3, -- Blip color
        ['Categories'] = {-- Categories available to browse
            ['am'] = 'Aston Martin',
            ['bugatti'] = 'Bugatti',
            ['ferrari'] = 'Ferrari',
            ['jaguar'] = 'Jaguar',
            ['koenigsegg'] = 'Koenigsegg',
            ['lamborghini'] = 'Lamborghini',
            ['lotus'] = 'Lotus',
            ['maserati'] = 'Maserati',
            ['mclaren'] = 'MCLAREN',
            ['porsche'] = 'Porsche',
            ['rollsroyce'] = 'Rolls Royce'
        },
        ['TestDriveTimeLimit'] = 0.5,
```

pdm categories </br>
```['Categories'] = {-- Categories available to browse
            ['acura'] = 'Acura',
            ['audi'] = 'Audi',
            ['bentley'] = 'Bentley',
            ['bmw'] = 'BMW',
            ['cadillac'] = 'Cadillac',
            ['chev'] = 'Chevrolet',
            ['dodge'] = 'Dodge',
            ['ford'] = 'Ford',
            ['honda'] = 'Honda',
            ['jeep'] = 'Jeep',
            ['lexus'] = 'Lexus',
            ['landrover'] = 'Land Rover',
            ['mazda'] = 'Mazda',
            ['benz'] = 'Mercedes Benz',
            ['nissan'] = 'Nissan',
            ['rangerover'] = 'Range Rover',
            ['subaru'] = 'Subaru',
            ['suzuki'] = 'Suzuki',
            ['tesla'] = 'Tesla',
            ['toyota'] = 'Toyota',
            ['volvo'] = 'Volvo'
```                
luxury categories </br>
```['Categories'] = {-- Categories available to browse
            ['am'] = 'Aston Martin',
            ['bugatti'] = 'Bugatti',
            ['ferrari'] = 'Ferrari',
            ['jaguar'] = 'Jaguar',
            ['koenigsegg'] = 'Koenigsegg',
            ['lamborghini'] = 'Lamborghini',
            ['lotus'] = 'Lotus',
            ['maserati'] = 'Maserati',
            ['mclaren'] = 'MCLAREN',
            ['porsche'] = 'Porsche',
            ['rollsroyce'] = 'Rolls Royce'        
```
Remember in these tables, every brand should have a comma (,) at the end except for the last one!
