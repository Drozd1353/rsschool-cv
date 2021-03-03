# Welcome to my CV #
## *Nikita Drozdovskij* ##
#### Contacts ####
 *My mobile phone **+375291899701** email: **drozdovskij2012@yandex.by***
 #### About me ####

#### My goal: ####
 1. improvement my professional skills 
 2. development within the profession
 
#### My skills ####
 *Now, i know:*
  * C++,
   * basic JS
   * HTML,CSS
   * OOP basic
   
#### Code example #### 
```
class Weapon{
protected:
	string name;
	int hit;
	int protect_power;
public:
	Weapon(int hit,int pp,string Name): hit(hit),protect_power(pp),name(Name){}
	virtual int Strike() = 0;
	virtual int Protect(int power) = 0;
	string getWeapon() { return name; }
	int getHit() { return hit; }
	int getProtect(){ return protect_power; }
};
class Shield :public Weapon//щит
{
public:
	Shield(int hit, int pp,string Name) : Weapon(hit, pp,Name) {};
	virtual int Protect(int power)
	{
		int g;
		srand(time(NULL));
		g = rand() % protect_power;
		protect_power -= g / 10;
		if (power < g)
		{
			return 0;
		}
		else
		{
			return (power - g);
		}
	}
```
#### Experience ####

#### Education ####
*2019--now **BSUIR ASOI SECONDARY COURSE***
#### English ####
 A2+. Now i go to courses in streamline.