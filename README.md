- convert male/ female to numeric 1 = male, 0 = female
- drop data with NAN age
- drop column 'Cabin' because alot of NAN
- drop rows with embarked = NAN
- onehotencode embarked column because we want to convert string to numerical values without any specific order
- drop one of the dummy variable column to avoid dummy trap (avoid linearity in the new embarked dummy var columns which might affect our prediction)
- Convert ticket with non numeric values to numeric by splitting string and only taking the numeric part (remove row without the number part)
