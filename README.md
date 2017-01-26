# suntool
python tool to trigger HUE lights on sunrise/sunset offsets


Currently:
 * determines sunrise from local timezone and hard-coded LAT/LONG
 * determines week-day vs week-end
 * determines holidays for locale



## INSTALL

    git clone https://github.com/akhepcat/suntool
    pip install holidays
    pip install pyephem


## CONFIGURE

Adjust the variables at the top of the suntool script for your locale
