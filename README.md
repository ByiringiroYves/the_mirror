# printf
The project encompasses both standard and derived functions, as well as a man page and a README.md file.

This generates output in accordance with specific format specifiers, as demonstrated below.

     _printf("Length:[%d, %i]\n", len, len);


	printf("Length:[%d, %i]\n", len2, len2);
  
  
	_printf("Negative:[%d]\n", -762534);
  
  
	printf("Negative:[%d]\n", -762534);
  
  
	_printf("Unsigned:[%u]\n", ui);
  
  
	printf("Unsigned:[%u]\n", ui);
  
  
	_printf("Unsigned octal:[%o]\n", ui);
  
  
	printf("Unsigned octal:[%o]\n", ui);
  
  
	_printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);
  
  
	printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);
  
  
	_printf("Character:[%c]\n", 'H');
  
  
	printf("Character:[%c]\n", 'H');
  
  
	_printf("String:[%s]\n", "I am a string !");
  
  
	printf("String:[%s]\n", "I am a string !");
  
  
	_printf("Address:[%p]\n", addr);
  
  
	printf("Address:[%p]\n", addr);
  
  
	len = _printf("Percent:[%%]\n");
  
  
	len2 = printf("Percent:[%%]\n");
  
  
	_printf("Len:[%d]\n", len);
  
  
	printf("Len:[%d]\n", len2);
  
  
	_printf("Unknown:[%r]\n");

This was developed by *Yves BYIRINGIRO* and *Fiston UZABUMWANA*, who are members of ALX cohort 12.
