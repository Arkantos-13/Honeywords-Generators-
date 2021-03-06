# Honeywords Generators

***UPDATE IN PROGRESS***


Honeywords	are	a	defense	against	stolen	password	files.	Specifically,	they	
are	bogus	passwords	placed	in	the	password	file	of	an	authentication	server to	
deceive	attackers.	Honeywords resemble	ordinary,	user-selected	passwords.	It’s
hard	therefore	for	an	attacker	that steals	a	honeyword-laced password	file	to	
distinguish	between	honeywords	and	true user passwords.	(“Honey” is	an	old	term	
for	decoy	resources in	computing	environments.	To	the	best	of	our	knowledge,	the	
term	“honeywords”	was	coined	in	this	paper.)
For	example,	one	of	the	following	passwords	is	a	true	user	password.	The	rest	are	
honeywords (generated	using	the simple	“chaffing-with-a-password”	algorithm in	
our	paper). Which	is	the	real	password?

kebrton1,
02123dia,
a71ger,
forlinux,
1erapc,
avanture32,
sbgo864959,
aiwkme523

An attacker	that	has	stolen	a	password	file may	crack its	hashed	passwords	(see	
Questions	4	and	5	 below)	and	attempt to	impersonate	users.	Given	the	presence	of	
honeywords,	though,	such	an attacker is	unlikely to	guess	a	user’s true	password	
and	likely	instead	to	submit	a	honeyword.	If	a honeyword-enabled	system	detects	
an	attempt	to	login	using a	honeyword,	it	raises	an	alarm indicating that	the	
password	file	has been	compromised.	
Honeywords	aren’t	visible	to	users and	don’t	in	any	way	change	their experience
when	they	log	in	using	passwords.

For more information you can view the following urls:
1) https://people.csail.mit.edu/rivest/pubs/JR13.pdf
2) https://people.csail.mit.edu/rivest/honeywords/faq.pdf
3) https://people.csail.mit.edu/rivest/honeywords/gen.py

In the file Honeywords Generator 1 we are able to find the dataset of honeywords I use in my code
