# C/C++ på svenska

`svenska.h` innehåller översättningar av nyckelorden för C och C++. Nyckelorden är uppdelade så att det med lätthet går att ta bort dem för C++ om man bara vill använda dem för C. Nedan följer två små exempelprogram som illustrerar hur fin svensk kod kan vara:

```cpp
#include "svenska.h"
#include <iostream>

hel main()
{
	std::cout << "Hej, världen!" << std::endl;
	returnera 0;
}
```

```cpp
#include "svenska.h"
#include <iostream>

hel main()
{
	för (hel nummer = 1; nummer <= 100; ++nummer)
	{
		om (nummer % 3 == 0 && nummer % 5 == 0)
		{
			std::cout << "fisbus" << std::endl;
		}
		annars om (nummer % 3 == 0)
		{
			std::cout << "fis" << std::endl;
		}
		annars om (nummer % 5 == 0)
		{
			std::cout << "bus" << std::endl;
		}
		annars
		{
			std::cout << nummer << std::endl;
		}
	}
	returnera 0;
}
```

Som ni ser är man fortfarande tvungen att stå ut med engelska, eftersom `svenska.h` bara innehåller nyckelord, och således inte sådant som hanteras av förkompilatorn (såsom include, define, etc.) eller klasser och funktioner från standardbiblioteket. Jag ber om ursäkt för det eventuella smärta och lidande som detta onekligen kommer att orsaka.
