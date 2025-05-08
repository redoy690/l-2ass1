# 2 . What is the use of the keyof keyword in TypeScript? Provide an example.
Ans: Keyof is a type operator. It creates a union of the property names.

Like type Vehicle = { bike: string; car: string}
type owner2 = keyof Vehicle

# 7 .Provide an example of using union and intersection types in TypeScript.
Ans: Union types: 

type FrontedDevelper = 'fakibazDeveloper' | 'juniorDeveloper'


intersection types:

type FrontedDevelper = {
  name: string;
};

type juniorDeveloper= {
  role: string;
};

type GoodDeveloper= FrontedDevelper & juniorDeveloper;



