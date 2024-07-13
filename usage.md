# Test Notification

python -m camply test-notifications --notifications pushover
python -m camply campsites --state wa --start-date 2024-07-04 --end-date 2024-07-07

# Check Kalaloach
Kalaloach 232464
    D24: 2576
    D25: 2564
    D26: 2579
    D27: 2577
    D30: 2572
    D35: 3222
    D36: 3223
    E9: 3233
    F6: 3242
    A25: 3104
    A16: 3074
    A22: 3203
    A23: 3102
    A14: 3060
Fairholme Campground 259084
    70: 10169562
    71: 10169563
    72: 10169564
    73: 10169565
    74:
    75:
    76: 10169568
    77: 10169569
    79: 10169571
    80: 10169572
    81: 10169573
    82: 10169574
    83: 10169575
    84: 10169576
    85: 10169577
    86: 10169578
    88: 10169580
    89: 10169581
    90: 10169582

Willaby Campground 119290
    569772, 569773, 569774, 569820, 569821, 569671, 569672, 569673, 569870, 569920

Coho Campground 233384
    79995, 79706, 79618, 80000


Ohanapecosh Campground 232465
White River Campground 259031
Colonial Creek North Campground 246855
Colonial Creek South Campground 255201


``` Kalaloach Fairholme 7-20
hatch shell
python -m camply campsites --campsite 10169577 --start-date 2024-07-19 --end-date 2024-07-21 --continuous --notifications pushover --notify-first-try --search-forever
```

```Ohanapecosh, White River, Colonial Creek North, Colonial Creek South 7-20
hatch shell
python -m camply campsites --campground 232465 --campground 259031 --campground 246855 --campground 255201 --start-date 2024-07-13 --end-date 2024-07-14 --start-date 2024-07-20 --end-date 2024-07-21 --start-date 2024-08-03 --end-date 2024-08-04 --start-date 2024-08-30 --end-date 2024-09-02 --start-date 2024-09-07 --end-date 2024-09-08 --start-date 2024-09-14 --end-date 2024-09-15 --start-date 2024-09-21 --end-date 2024-09-22 --continuous --notifications pushover --notify-first-try --search-forever
```

``` Kalaloach Fairholme 7-20
hatch shell
python -m camply campsites --campsite 2576 --campsite 2564 --campsite 2579 --campsite 2577 --campsite 2572 --campsite 3222 --campsite 3223 --campsite 3233 --campsite 3242 --campsite 3104 --campsite 3074 --campsite 3203 --campsite 3102 --campsite 3060 --campsite 10169562 --campsite 10169563 --campsite 10169564 --campsite 10169565 --campsite 10169568 --campsite 10169569 --campsite 10169571 --campsite 10169572 --campsite 10169573 --campsite 10169574 --campsite 10169575 --campsite 10169576 --campsite 10169577 --campsite 10169578 --campsite 10169580 --campsite 10169581 --campsite 10169582 --start-date 2024-07-13 --end-date 2024-07-14 --start-date 2024-07-20 --end-date 2024-07-21 --start-date 2024-08-03 --end-date 2024-08-04 --start-date 2024-08-30 --end-date 2024-09-02 --start-date 2024-08-30 --end-date 2024-09-02 --start-date 2024-09-07 --end-date 2024-09-08 --start-date 2024-09-14 --end-date 2024-09-15 --start-date 2024-09-21 --end-date 2024-09-22 --continuous --notifications pushover --notify-first-try --search-forever
```

python -m camply campsites --yaml-config campsites.yaml
python -m camply campsites --yaml-config campground.yaml

# Deception Pass
Deception Pass State Park  (#-2147483624)          

```
python -m camply campsites --campground -2147483624 --start-date 2024-07-04 --end-date 2024-07-07 --provider goingtocamp --rec-area 3 --equipment-id -32761 --continuous --notifications pushover --notify-first-try --search-forever
```