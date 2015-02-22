---
layout: page
title: "modular connector (Used for ethernet/telephone)"
category: ref
date: 2015-02-04 02:38:29
---

http://en.wikipedia.org/wiki/Modular_connector#6P2C

http://en.wikipedia.org/wiki/Registered_jack#Registered_jack_types


# 6P6C family

## Telephone

Do note that telephone plugs typically are called RJ11 (6P2C) , but most are actually sold as 6P4C.

In [the product page for Oregon electronics](http://www.oregon-electronics.com/x/home.php?cat=63), we can see that they refer to 6P4C as RJ11, and 6P6C as RJ12. This is technically inaccurate, but it's how the industry refers to these plugs these days.

## diagrams

```ascii-diagram

	6P2C PORT (Telephone. Typically called as RJ11 ):
	(6 Possible Contacts, 4 Pin Contacts Used)
	        _____
	      _|     |_
	 ____|         |____
	|                   |
	|                   |
	|                   |
	|_ [] [] 2 1 [] [] _|
	
	http://en.wikipedia.org/wiki/Registered_jack#Registered_jack_types
	
```

```ascii-diagram

	6P4C PORT (Telephone. Typically called RJ12):
	(6 Possible Contacts, 4 Pin Contacts Used)
	        _____
	      _|     |_
	 ____|         |____
	|                   |
	|                   |
	|                   |
	|_  [] 4 3 2 1 []  _|
		
	http://en.wikipedia.org/wiki/Registered_jack#Registered_jack_types
	
```

```ascii-diagram

	6P6C PORT (Telephone. Pretty rare):
	(6 Possible Contacts, 6 Pin Contacts Used)
	        _____
	      _|     |_
	 ____|         |____
	|                   |
	|                   |
	|                   |
	|_   6 5 4 3 2 1   _|
		
	http://en.wikipedia.org/wiki/Registered_jack#Registered_jack_types
	
```

# 8P8C (e.g. Ethernet Plug)

Typically referred to as an RJ45 plug

http://en.wikipedia.org/wiki/Modular_connector#8P8C

## diagrams

```ascii-diagram

	8P8C (e.g. Ethernet) PORT:
	(8 Possible Contacts, 8 Pin Contacts Used)
	        _____
	      _|     |_
	 ____|         |____
	|                   |
	|                   |
	|                   |
	|_ 8 7 6 5 4 3 2 1 _|
	
	http://en.wikipedia.org/wiki/TIA/EIA-568#Wiring
	
```

### note:

> [Don't forget the pinout of cat5 with an RJ45 connector - the pairs are not wired to the pins in order. The pairing is AABCCBDD --n1ist](http://www.avrfreaks.net/forum/general-ttl-and-power-over-cat5)

