ab3p
====

C++ code here : ftp://ftp.ncbi.nlm.nih.gov/pub/wilbur

Incomplete.

Rules for porting:

	remove all const key words
	
	split between interface and implementation where possible, for example
	    - header file -> interface
	    - source file -> implementation
	
	primitive*     becomes primitive[]
	std::vector<T> becomes ArrayList<T>
	Clazz a;       becomes Clazz a = new Clazz();
	Clazz* a;      becomes Clazz* a = null;
