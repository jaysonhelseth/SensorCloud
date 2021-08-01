# SensorCloud
The cloud portion of the sensor system. This will allow devices with browsers to see the sensor data.

## Collect Data
There will be a webhook that can be called by a client and that data will be stored in a sqlite table. It will always update the same record.

## Displaying Data
A php page will read from the table in sqlite and display the data. The page will use ajax to update the display from the table.

Boostrap and jquery will be used to help make the page more responsive. It will be written for mobile first and desktop second. Or I will have two different landings for each size. I still haven't made my mind up yet.

## Historical Data
In the future I will possibly sign up for a free for life cockroach labs account and store the data in cockroachDB. Then I can search the data for trends or some other meaningful patterns.
